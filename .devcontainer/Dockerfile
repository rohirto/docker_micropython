# Use an official Python base image
FROM python:3.9-slim-buster

# Install debugging tools (pdb and ptvsd for VS Code)
RUN pip install ptvsd

# Install Git
RUN apt-get update && apt-get install -y git


# Expose port 5678 for remote debugging
EXPOSE 5678

# Entry point to keep the container running
CMD ["tail", "-f", "/dev/null"]