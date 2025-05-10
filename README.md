# Custom ChatGPT - work in progress

This project is a custom-built chatbot application that mimics the functionalities of ChatGPT for personal use. It's built using Python, Django for the backend, and React with Next.js for the frontend. The application provides regular chatting capabilities with history stored in the database, streaming responses, and auto-generated titles using gpt3.5. It also allows for title editing, conversation deletion, and messages regeneration. Project currently supports model selection between gpt3.5 and gpt4. It also features a custom Django admin page for managing conversations, versions, and messages.

It is a work in progress, with plans to add more features and functionalities.

The idea behind this project is to experiment with Next.js and create a personal version of ChatGPT with custom functionalities and features.


# Technologies

## Backend
- Python
- Django
- Django Rest Framework

## Frontend
- Next.js
- React

## Database
- SQLite for now -> will be changed to PostgreSQL

# Functionalities

- Regular chatting with history stored in DB as well as with different versions of conversation: while regenerating messages (or editing existing ones), the new version is created for given conversation
- Streaming responses
- Auto generated titles using gpt3.5
- Title edition for given conversation
- Deletion of given conversation
- Assistant messages regeneration
- User messages edition
- Models selection: currently gpt3.5 or gpt4
- Custom django admin page for managing conversations, versions and messages
