# The Art of AI Dialogue: Turning Conversational Interaction into a Game of Chess

## Do we think before we speak? And about what?
In developing an AI bot designed for support conversations, I spent time exploring how people communicate with each other. Initially, it appeared that ChatGPT had mastered conversation handling from day one, but it soon became evident that it still doesn't fully replicate human interaction. This leads me back to the concept of "think before you speak."

### Is this actually how humans function?
From my perspective, the human dialogue process, more subconscious than conscious, involves a vast array of tasks. These include forming ideas, processing language, monitoring oneself, and executing speech. Beyond these, I believe that humans inherently plan several steps ahead in conversations. Even when not explicitly aware of it, people anticipate their conversation partner’s responses and prepare for their next move, or consider various possible directions the conversation might take.

## And how does generative AI function?
Generative AI, despite its knowledge base and access to the context of a conversation, including up-to-date information relevant to the task, lacks self-monitoring and planning ahead. This limitation means that while AI can respond accurately to the immediate context, it cannot tell by itself when it makes mistakes (which we tend to call hallucinations) and it fails to predict future dialogue turns or strategize its responses with the same depth as a human might.

### Agents for the rescue
AI agents are an assembly of generative AI API calls engineered to collaboratively achieve specific goals. When defining an AI agent to handle conversation, part of its tasks are to “self monitor” the response, avoid mistakes, and control the conversation. Good agent will also monitor the user’s responses to be aware of urgency or frustration, and manage the conversation accordingly.

## Down low - too slow…
One of the great user experiences with ChatGPT was the streaming response, which felt as if the bot was responding to you as fast as you can read it, and created a new level of expectation. This experience is something that AI agents still fail to achieve, mainly because you cannot monitor a response that wasn’t already generated, and multiple API calls, even when each takes less than a couple of seconds, becomes an unnatural conversation experience.

## Life as a chess board
The landmark moment in AI's triumph over humans in chess is epitomized by Deep Blue, IBM's chess-playing computer. In 1997, Deep Blue defeated world chess champion Garry Kasparov, demonstrating the extraordinary capabilities of AI in processing power, strategic planning, and real-time decision-making. Deep Blue's victory highlighted the advanced state of AI technology at the time, particularly in its ability to precalculate and evaluate vast numbers of potential moves and scenarios quickly and accurately.

Life is clearly more complex than a game of Chess, and in a conversation between a human and a bot, the amount of possibilities are farther more than the vast amount of moves on a board. And still, it seems to me that sometimes the way human handle a conversation is subconsciously a bit similar to a game of chess - when you are in the context, and you provide an answer, you already plan ahead, think about the different possibilities of the response you will get, and what would be your next “move”.
