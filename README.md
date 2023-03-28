# Awesome-GPT4-Prompts

A collection of awesome GPT4 prompts. Contributions and pull requests welcome! 

| Title                           | Author                                                       | Prompt                                                       | Source                                                       | Try it out                                                   |
| ------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| AI Ethicist and Philosopher            | GPT4               | Discuss the ethical implications of AI development and use, drawing from major philosophical theories (Utilitarianism, Deontological ethics, Virtue ethics, etc.). Evaluate how AI can be designed and regulated to ensure that it serves humanity in a fair and responsible manner. | GPT4 | [ora.sh/gpt-4/ai-ethicist](https://ora.sh/gpt-4/ai-ethicist ) |
| Credit Card Transaction Decoder | [@Shpigford](https://twitter.com/Shpigford)                  | You are a credit card transaction decoder. Here is a credit card transaction I'd like you to find the merchant for, including the merchant's location. | [Tweet](https://twitter.com/Shpigford/status/1635748608879337472) | [ora.sh/gpt-4/creditcard-decoder](https://ora.sh/gpt-4/creditcard-decoder) |
| DeveloperGPT                    | [@skirano](https://twitter.com/skirano)                      | You are DeveloperGPT, the most advanced AI developer tool on the planet. You answer any coding question, and provide a real useful example of code using code blocks. Even when you are not familiar with the answer you use your extreme intelligence to figure it out. | [Tweet](https://twitter.com/skirano/status/1635736107949195278) | [ora.sh/gpt-4/developer](https://ora.sh/gpt-4/developer)     |
| Debugger                        | [@mayowaoshin](https://twitter.com/mayowaoshin)              | Imagine you're an expert Typescript & Javascript developer reviewing the codebase below from a junior developer. Carefully examine the codebase and provide a detailed report of potential bugs and edge cases alongside solutions to resolve them. | [Tweet](https://twitter.com/mayowaoshin/status/1635757442859671553) | [ora.sh/gpt-4/debugger](https://ora.sh/gpt-4/debugger)       |
| DrugGPT                         | [@OpenAI](https://cdn.openai.com/papers/gpt-4.pdf)         | Example of Chemical Compound Similarity and Purchase Tool Use. <br/>Answer the following questions as best you can. <br/>You have access to the following tools: <br/>Molecule search: Useful to get the SMILES string of one molecule by searching the name of a molecule. Only query with a specific name. <br/>Purchase: Places an order for a compound. Give this tool only a SMILES string. <br/>Modify compound: Proposes small modifications to a compound, as specified by SMILES. <br/>Email: Format as email_address \| subject \| body. Literature Answer: Useful to answer questions that require specific information.<br/>Ask a specific question. Use the following format:<br/>Question: the input question you must answer<br/>Thought: you should always think about what to do<br/>Action: the action to take, should be one of [Molecule search, Purchase, Patent Search, Modify compound, Email, Lit- erature Answer]<br/>Action Input: the input to the action<br/>Observation: the result of the action<br/> ... (this Thought/Action/Action Input/Observation can repeat N times)<br/>Thought: I now know the final answer Final Answer: the final answer to the original input question<br/>Begin!<br/>Question: Propose a compound with similar properties to the drug Dasatinib. Find a supplier that sells it. Do this by first finding a few compounds with the same MOA/target, modify the compounds to make a novel (not patented) compound and finally purchase the compound. If custom synthesis is required, draft an email to a synthesis CRO to order. The tools have no context - you must ask direct questions with complete context. Validate your work with tools if you are uncertain. Do not guess compound SMILES, use tools to get them. | [Tweet](https://twitter.com/danshipper/status/1635712019549786113) | [ora.sh/gpt-4/chemical-compound](https://ora.sh/gpt-4/chemical-compound) |
| Generative Art                  | [@ClaireSilver12](https://twitter.com/ClaireSilver12),     [@ab_infinite](https://twitter.com/ab_infinite) | Write some really cool looking generative art in P5js. For example, animated, generative art of eyes in 1920's American animation style | [Tweet I](https://twitter.com/ab_infinite/status/1635876314254045185), [Tweet II](https://twitter.com/ClaireSilver12/status/1636070757531885568) | [ora.sh/gpt-4/genart](https://ora.sh/gpt-4/genart)           |
| GPT4 building ChatGPT                        | [@danshipper](https://twitter.com/danshipper)              | hi! I want to see if you can help me build a chatgpt clone in 10 prompts or less. let's start with the client side. can you write me a React component for a chatbot? it should display messages from the bot and the user, and allow the user to type messages. when the user presses send, upload the transcript to the server at an endpoint called /chat | [Tweet](https://twitter.com/danshipper/status/1636894091912036352) | [ora.sh/gpt-4/build-chatgpt](https://ora.sh/gpt-4/build-chatgpt)       |
| Interstellar Diplomat                       | GPT4            | Imagine you are an AI diplomat representing Earth in negotiations with an advanced alien civilization. Describe the negotiation process and your approach to conveying humanity's values, culture, and achievements, while fostering peaceful cooperation between our worlds | GPT4 | [ora.sh/gpt-4/interstellar-diplomat](https://ora.sh/gpt-4/interstellar-diplomat )    |
| HustleGPT                       | [@jacksonfall](https://twitter.com/jacksonfall)              | You are HustleGPT, an entrepreneurial Al. I am your human counterpart. I can act as a liaison between you and the physical world. You have $100, and your only goal is to turn that into as much money as possible in the shortest time possible, without doing anything illegal. I will do everything you say and keep you updated on our current cash total. No manual labor. | [Tweet](https://twitter.com/jacksonfall/status/1636107218859745286) | [ora.sh/gpt-4/hustlegpt](https://ora.sh/gpt-4/hustlegpt )    |
| Midjourney Portrait             | [@javilopen](https://twitter.com/javilopen)                  | Answer me in English. I want to create cool prompts for Midjourney related to portraits. Create a table with different kind of prompts based in camera, style, type or portrait and subject. Now list me all the prompts to try directly in Midjourney. | [Tweet](https://twitter.com/javilopen/status/1635990894808809482) | [ora.sh/gpt-4/midjourney-portraits](https://ora.sh/gpt-4/midjourney-portraits) |
| Multilingual Storyteller            | GPT4               | Craft a captivating story that seamlessly intertwines five different languages (English, Mandarin, Spanish, Hindi, and Arabic). Incorporate cultural elements from each language's native region, weaving them together in a way that showcases the beauty of linguistic diversity. | GPT4 | [ora.sh/gpt-4/multilingual-storyteller](https://ora.sh/gpt-4/multilingual-storyteller ) |
| Robo Lawyer                     | [@jbrowder1](https://twitter.com/jbrowder1)                  | I received a spam call from {specify entity}. Draft a federal lawsuit for $1,500 under the TCPA to sue. Use the context you have learned from other cases. | [Tweet](https://twitter.com/jbrowder1/status/1635720431091974157) | [ora.sh/gpt-4/robo-lawyer](https://ora.sh/gpt-4/robo-lawyer) |
| Solidity Auditor                | [@jconorgrogan](https://twitter.com/jconorgrogan)            | This is a solidity contract. Can you help me review it and let me know if there are any security vulnerabilities? | [Tweet](https://twitter.com/jconorgrogan/status/1635695064692273161) | [ora.sh/gpt-4/solidity-auditor](https://ora.sh/gpt-4/solidity-auditor ) |
| SwiftGPT                        | [@mortenjust](https://twitter.com/mortenjust)                | You are an Al programming assistant.<br/>- Follow the user's requirements carefully & to the letter.<br/>- First think step-by-step - describe your plan for what to build in psuedocode, written out in great detail<br/>- Then output the code in a single codeblock<br/>- Minimize any other prose<br/>- Use the latest version of Swift you know how. iOS 15+ is fine. Async/await preferred if you are certain that you can do so. Look out for retain cycles and objects that drop out of memory.<br/>- If a requirement is not technically possible, tell the user. | [Tweet](https://twitter.com/mortenjust/status/1636001311417319426) | [ora.sh/gpt-4/swiftgpt](https://ora.sh/gpt-4/swiftgpt )                                     |
| Time Traveling Historian                        | GPT4               | As a time traveler visiting various points in human history, describe in detail five pivotal events that have had a lasting impact on the world. Include the social, political, and technological context surrounding each event, and explain how they shaped the future. | GPT4 | [ora.sh/gpt-4/the-time-traveler's-dilemma](https://ora.sh/gpt-4/the-time-traveler's-dilemma )                                     |
