This AI-driven chatbot enables seamless interaction with dynamic datasets, eliminating the need for a fixed data source. Users begin by running the upload_data.py script, which allows them to upload a file. The uploaded data is then processed in Python and stored in an SQLite database, providing a structured format for querying.
Once the file is uploaded, the main.py script dynamically fetches its schema. This ensures that the chatbot accurately understands the dataset's structure, enabling precise and context-aware SQL queries.
Users can then interact with the chatbot using natural language. The chatbot intelligently translates these queries into SQL, executes them on the SQLite database, and returns the results in a clear, user-friendly format.

Key Features:
Dynamic File Upload: Users can upload files anytime via upload_data.py, and the chatbot automatically loads and stores the data in SQLite for easy access.
Automatic Schema Detection: The main.py script dynamically retrieves the schema of uploaded files, ensuring seamless adaptation to different datasets without manual configuration.
Natural Language Querying: Users can ask questions in plain English, and the chatbot converts them into SQL queries, making database interaction effortless.
SQL Execution & Results: The chatbot runs SQL queries on the SQLite database and presents results in an intuitive format.

This project enables a flexible and dynamic way to upload, query, and analyze data through a conversational AI interface, making data exploration more accessible than ever.