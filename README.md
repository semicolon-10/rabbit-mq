# Rust Rabbit MQ Setup

This repository contains a Rust application that sets up a Rabbit MQ environment with producer and consumer functionalities.

## Prerequisites

Before running the application, make sure you have the following installed:

- Docker
- Rust (if you want to modify or compile the Rust code)

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/semicolon-10/rabbit-mq.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd rabbit-mq
    ```

3. Start the Rabbit MQ Container

    ```bash
    docker run -d --name rabbitmq -p 5672:5672 rabbitmq:latest
    ```
    
4. Run App:

    ```bash
    cargo run
    ```

# Subscribe to my youtube Channel 🎥

[Semicolon](https://www.youtube.com/@Semicolon10)
