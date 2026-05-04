print("🤖 Smart Chatbot (type 'exit' to quit)")

while True:
    user = input("You: ").lower()

    if user == "exit":
        print("Chatbot: Goodbye!")
        break

    elif "hello" in user:
        print("Chatbot: Hi there!")

    elif "what is ai" in user:
        print("Chatbot: AI means Artificial Intelligence.")

    elif "python" in user:
        print("Chatbot: Python is a programming language.")

    elif "who are you" in user:
        print("Chatbot: I am your assistant.")

    else:
        print("Chatbot: I can answer basic questions only.")
