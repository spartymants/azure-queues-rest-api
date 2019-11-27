# Blueprism - Azure Queues REST API
This VBO provides a simplified mechanism for interacting with Azure Queues via their exposed REST API. 

## Usage
The VBO includes the following endpoint actions:

* **Retrieve Messages** - Retrieves the specified number of messages from the queue and makes them invisible to other consumers for the specified number of seconds.
* **Retrieve Next Message** - Retrieves the next available message from the queue and makes it invisible to other consumers for the specified number of seconds.
* **Peek Messages** - Retrieves the specified number of messages from the queue but does not alter their visibility so they remain available for other consumers to work.
* **Peek Next Message** - Retrieves the next available message from the queue but does not alter its visibility so it remains available for other consumers to work.
* **Add Message** - Adds a message to the queue.
* **Update Message** - Updates a message in the queue.
* **Delete Message** - Deletes a message from the queue.
* **Delete All Messages** - Deletes all messages from the queue.
