# AI Experiments with LLMs.

In the notebooks folder, you will find my notebooks on AI experiments in the following areas:

- Tool calling with the Llama 3.1 model.
  - You will find a sample for an AI Ticket Agent.
  - I also developed some ideas to test the AI Ticket Agent.
- Image recognition with local multimodal LLMs.

**Requirements**

* Install the latest [Visual Studio Code](https://code.visualstudio.com/).
* Install the latest [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download).
* Install the Polyglot Notebooks extension from the [marketplace](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode).

**Get Started**

To use the notebooks, clone the repository. Start Visual Studio Code. Open the folder notebooks.
Open the example notebook (.dib file).

The examples are:

* get_weather.dib: Basic example to do tool calling with Llama 3.1.
* create_ticket.dib: Simple AI Ticket Agent for Llama 3.1 used to create a ticket and send it to a ticket system.
* test_create_ticket.dib: Test data and automatic tests for AI Ticket Agent.
* image_to_text.db: Example of image recognition with the local multimodal model LLAVA 1.6.

The notebook tools.dib contains some helper methods and a basic agent class. It is imported in the notebooks to avoid boilerplate code in the examples.

**Articles for LinkedIn (in German)**

You can find the contributions here:

[Basics](https://www.linkedin.com/pulse/funktionsaufrufe-mit-dem-llama-31-modell-andreas-wenzel-h2txc/?trackingId=4zky1ob2tbwO%2FiEurGsXhQ%3D%3D)

[Ticket Agent](https://www.linkedin.com/pulse/ki-ticket-agent-mit-meta-llama-31-andreas-wenzel-pxstc/)

[Tests](https://www.linkedin.com/pulse/testen-eines-ki-ticket-agenten-andreas-wenzel-4780c)

Experiments are done for the new generation of CAFM software created by [net-haus](https://net-haus-software.de/).