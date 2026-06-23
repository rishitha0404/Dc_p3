# Simple AI Recommendation System

items = {
    "Programming": ["Python Course", "Java Course", "DSA Course"],
    "AI": ["Machine Learning", "Deep Learning", "Chatbot Project"],
    "Web Development": ["HTML & CSS", "JavaScript", "React"]
}

interest = input("Enter your interest: ")

if interest in items:
    print("\nRecommended for you:")
    for item in items[interest]:
        print("-", item)
else:
    print("No recommendations found.")
