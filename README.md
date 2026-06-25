This script automates the process of replying to comments on YouTube videos using ChatGPT model. It performs the following actions:

Opens YouTube Studio using an existing Chrome profile.

Switches to a selected YouTube channel.

Retrieves all visible comments.

Sends each comment to ChatGPT.

Generates a natural language reply.

Posts the generated reply back to YouTube.

After doing all the above it starts another instance where it accesses the next channel if it exists and performs the above actions again

'instance manage.py' is responsible for handling the cycles
