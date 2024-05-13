# evol-ruozhiba

### 弱智吧问题来源 Source Question of "ruozhiba"

[COIG-CQIA](https://github.com/paralym/COIG-CQIA)是一个开源的高质量指令微调数据集，旨在为中文NLP社区提供高质量且符合人类交互行为的指令微调数据。COIG-CQIA以中文互联网获取到的问答及文章作为原始数据，经过深度清洗、重构及人工审核构建而成。数据集可以从[这里](https://huggingface.co/datasets/m-a-p/COIG-CQIA)获取。

[COIG-CQIA](https://github.com/paralym/COIG-CQIA) is designed to provide the Chinese NLP community with high-quality and human interaction-aligned instruction fine-tuning data. 
These data are deeply cleansed, restructured, and manually reviewed to ensure quality, diversity, and relevance.
It is notable that we only use the part of this dataset related to ruozhiba.
This dataset can be acquired from [here](https://huggingface.co/datasets/m-a-p/COIG-CQIA).

### 广度扩展的提示 Prompt of Breadth Expansion

-----------------------

我希望你可以作为一个的问题生成专家。

你的目标是充分理解提供的问题示例#Question Examples#，并挖掘问题示例#Question Examples#背后蕴含的复杂逻辑，以生成一条具有**相似**逻辑的问题#Generated Prompt#。

你需要确保生成的问题#Generated Question#必须是那些著名的人工智能系统（例如GPT4、Claude3 Opus和Gemini1.5pro）难以处理和回答的，即使它们进行了更深入的思考和反思。

你需要确保生成的问题#Generated Question#必须是合理的，必须是符合真实世界逻辑的，必须是人类能够理解和回答的。

你不可以让生成的问题#Generated Question#变得冗长。

你只需要按照要求生成问题#Generated Question#，不需要给出任何不必要的解释。

#Question Examples#

{examples}

#Generated Question#

-----------------------

### 深度扩展的提示 Prompt of Depth Expansion

-----------------------

我希望你可以作为一个的问题生成专家。

你的目标是充分理解提供的问题示例#Question Examples#，并挖掘问题示例#Question Examples#背后蕴含的复杂逻辑，以生成一条具有**更复杂**逻辑的问题#Generated Prompt#。

你需要确保生成的问题#Generated Question#必须是那些著名的人工智能系统（例如GPT4、Claude3 Opus和Gemini1.5pro）难以处理和回答的，即使它们进行了更深入的思考和反思。

你需要确保生成的问题#Generated Question#必须是合理的，必须是符合真实世界逻辑的，必须是人类能够理解和回答的。

你不可以让生成的问题#Generated Question#变得冗长。

你只需要按照要求生成问题#Generated Question#，不需要给出任何不必要的解释。

#Question Examples#

{examples}

#Generated Question#


-----------------------
