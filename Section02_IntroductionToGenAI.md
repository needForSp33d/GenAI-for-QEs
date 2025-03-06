# Section 2 - Introduction to GenAI

## What makes up AI?


### Where do LLMs fit into AI?

- ML - deriving algorithmic insights from data permitting prediction
- DL - neural networks
- GEN AI - LLMs power this layer but are a fraction of the wider AI field.

### Introduction to Natural Language Processing & Generation:

- NLP
- Subfield of AI allowing comprehension, interpretation, and generation of human-readable language.
- NLP: Prompt > 'Decomposition' > machine analysis (lexical, semantic, pragmatic, disclosure) > insert into model.
- NLG: Foundation model > generate content > response.

### Types of ML

In essence, 'learn' from data that has been input, and generate an output based on applied algorithms. 

Supervised ML
- Machine 'learns', but is 'supervised' by a person/system.
- Data input is predefined in some way - for example labelled in order to train and ensure machine 'interprets' data correctly.

Unsupervised ML
- As above, but without outside intervention.
- Algorithms stills applied to support machine independent identification of patterns.
- To general labels and 'reasons' for the classification.

Reinforced ML
- Combines ML + AI/human oversight to support/corroborate results. This provides feedback to the machine.

Deep Learning
- Variant of Reinforced ML, but progressive move through different layers of analysis to ensure fine-tuning.

### ML - Supervised

### ML - Unsupervised

### ML - Reinforced

Rapid feedback loop - trial & error mechanism exploited, but at vast pace.

Self-driving car used to explain this - the car and the environment it operates in. Feedback of the latter is used to further train the former. The +ve and -ve reinforcement then alters the state of the AI system. This gives the appearance of 'learning'.

In each instance of 'decision' made by the AI system, the basis or context of this is known. The reward feedback further trains the AI and shapes future interpretation of similar external factors/settings.

### Neural Networks & Deep Learing

Neural network comprised of:
- Input layer
- Hidden/Decision layer
- Output layer

Decision layer uses probabilitic techniques to assign weights/values to the inputs in order to refine and direct the decision-making.

Within this decision layer, as processing occurs, the weightings and values are updated. By this mechanism, the decision layer matures and refines its predictive capability. Statistics & mathematics are the basis of all of this though.

###  Importance of Training Data

Standard ETL Process

Data Extraction - derived from a dataset and the relevant data should be extracted for the model in question.

Data Transform - shuffling, batching, augmenting, clarifying, sanitising, correcting etc.

Data Load - insertion of the training data into the AI model.

### Generative AI - What It Is

- The model is exposed to labeled, and unlabeled data as well as a code base.
- the foundation model is then prompted to generate content - whether speech, code, text, images etc.

### Transformer Architecture Model

https://www.youtube.com/watch?v=ZXiruGOCn9s

### How to achieve repeatable & consistent GEN AI Outputs

- Setting the 'temperature' parameter when interacting with the ChatGPT model as close to '0' as possible.
- The closer to '2.0', the more 'creative' the GPT responses will be.
- When needing data 'purity', disable historic data so as not to have distorted results.
- Using 'context' settings and specifying the format of the output will help to improve response consistency and predictability.

### Hallucinations

- As the models rely on statistical probability and determining the 'next best token' to output, the models are prone to making things up in their outputs.

### Privacy

- If you are using a free GPT model, the data you input might be exposed, and the only way to guard against this is to use a private LLM.
