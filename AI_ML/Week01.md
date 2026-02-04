# Fast-Tracking course of AI

The journey From `"What is AI?"` to `"How ChatGPT works"`.

<details>
  <summary>What is <b>Learning</b> ? </summary>

<br/>

What does it mean to learn? <br/>
**What is Learning?** <br/>
- Changing yourself based on experiences, basically adjustments
- Looking at things, touching it, Understanding it, experiencing it.

**Learning is a loop**.
- Try something -> See what happens(feedback) -> Adjust -> Repeat 

a basic scerio of Learning : Learning Cycle in childhood, Writing, Reading etc.

</details>

<details>
  <summary> What is <b>knowledge</b> ? </summary>

<br/>

What does it mean to know? <br/>
What is knowledge? <br/>
**Getting data and information about something.**

Two types of knowledge:
1. **Explicit Knowledge**
- Capital of India is Delhi
- Objective, It is either correct or Incorrect.

2. **Implicit Knowledge**
- How do you remember the face of your friends?
- Subjective, It is not fixed some people remember by nose, some are by eyes and so on.

</details>


<details>
  <summary> What is <b>Intelligence</b> ? </summary>

<br/>

What is Intelligence? <br/>
This is a great question is philosophy, Human Mankind History. 

**Intelligence is the ability to achieve goals in a wide range of situations.**
- Ability to perform/achieve in wide range of situations/activities.

Example : <br/>
**Calculator** does perform all the arithmetics, but It's not intelligent bcuz It does just only arithmetics. <br/>
**Human** does perform a wide ranges of catalogs(activities), we can also perform arithmetic, use Calculator, So Human is intellegent.


</details>

<details>
  <summary>What is <b>AI</b> ?</summary>

<br/>

What comes to mind when you hear "Artificial Intelligence"?

We human(Developers/Engineers/Scietists/Mathematicians) somehow turning intelligence to teach computers(machines) on wide range of tasks.
- Rule defined instructions to machines for a specific tasks, like perform arithmetic, turn on/off the light, speak what is feed etc.
- We wanted to make machine do general stuffs for General tasks not only specific tasks which is defined in the rules. Like understand
  the sarcasm, making jokes, answering basic general questions.

Out goal is make Computers(Machines) like Computer can understand, can have intelligence so that perform wide range of tasks 
instead of just specific defined rules or instructions based tasks.

</details>

<details>
  <summary>The <b>Goal of AI </b></summary>

<br/>

**Making machines do things(tasks) that would require intelligence if a human did them.**

Examples :
- Recognizing faces
- Understanding language
- Playing chess
- Driving a car

**How does we make this happen?** <br/>
In 1960-70s 1st thing came into people mind is, If they want to make machine intelligent then ***Write rules to make machines learn***
like different rules for different stuffs, so rules were designed , invented and introduced for different different
purposes.

</details>

<details>
  <summary> <b> Attempt #1: Write the Rules</b> </summary>

<br/>

> If the email contains 'free money' ->  **spam**

> If temperature > 100°F ->  **fever/cold**

> If chess piece can move to square AND square has enemy piece -> **capture**

This is called **"Expert Systems"** or **"Rule-Based AI"**


</details>

<details>
  <summary> <b>The Problem with Rules</b> : <code> How would you write rules for tasks that humans do intuitively?</code></summary>

<br/>

How would you write rules for tasks that humans do intuitively?

**Recognizing a Face**
> How do you define the exact distance between eyes or the curve of a nose for every possible angle and lighting?

**Understanding Sarcasm**
> "Oh, great." Does it mean something is good, or is it a complaint? Rules can't easily capture tone and context.

**Decoding Idioms**
> "It's raining cats and dogs." A rule-based system might look for falling animals instead of understanding the metaphor.

Problem with Rules is : It is impossible to make machines based on rules to do the stuffs like human intuitions.

But Writing Rules were not enough and this was not the ultimate goal. So, Research continued and a lot of stuffs happened.

Let's not make rules, Let's start with data, this is time when the ***Machine Learning Ideas emerged***.
- If we give machines(computer) a lot of data and let them to ***Statistical based learning*** based on data.
- Meaning the words appears, what it is followed by and what it follows based on that machines try to get a sense of what is happening?
- Shows, feed the machines 1000s of examples of different fields and expect machines to learn and do things from this data without
  explicitly using the rules/programming or anything.

</details>

<details>
  <summary> <b> Attempt #2: Let Machines Learn</b> i.e. <code>Machine Learning</code> </summary>

<br/>

Instead of writing rules... , Show the machine thousands of examples and let it figure out the patterns.

This is called **Machine Learning (ML)**

Basically what ML is, we do not  want to write rules, instructions, codes, programming explicitly, but we want Machines to internally 
write tools, codes other stuffs for itself based on data. This is the whole idea of Machine Learning. 

</details>

<details>
  <summary> <b> How Machine Learning Works (Intuitively)</b> ? </summary>

<br/>

1. Show the machine many examples
2. Machine makes a guess
3. Tell it if it was right or wrong
4. Machine adjusts itself slightly
5. Repeat millions of times

> **The Analogy : "Like a child learning by trial and error"**

How Machine Learning works? <br/>
We kind of make a bucket and put the input based on the data we trained them off.

<img width="350" height="250" alt="image" src="https://github.com/user-attachments/assets/29c3c1cf-a418-4f3b-9b5b-59d3e4a30932" />


</details>

<details>
  <summary> <b> AI vs ML</b> </summary>

<br/>

AI The Goal: Smart Machines
ML One Method: Learning from Data
Deep Learning

<img width="450" height="300" alt="image" src="https://github.com/user-attachments/assets/8a00708d-6305-472e-89f3-0d5d9d0c470c" />

Deep Learning is a subset of Machine Learning which deals which Neural Networks. <br/>
All the new models are based on something called ***Neural Network*** or ***Transformer***
- These are the smallest unit of this big system.
- It is like a **neuron**
- It is designed to mimic human brain where we have neurons which get fired when we listen, see, do an action based on that concept we
  have **Deep Learning** (Here, we explicitly relie on Neural Network)

> **Neuron**
> - A neuron is the fundamental unit of the nervous system, also known as a nerve cell
> - It is an electrically excitable cell responsible for transmitting information throughout the body via electrical and
chemical signals.
> - Neurons process and relay messages between different parts of the brain, spinal cord, and the rest of the body,
enabling functions such as movement, sensation, thought, and emotion.
> - The human brain contains approximately 100 billion neurons, each connected to thousands of others, forming vast networks
that underlie all cognitive and physiological functions.
> - Neurons are highly specialized and typically do not regenerate after damage, which contributes to the severity of brain
and spinal cord injuries. 

</details>

<details>
  <summary> <b> Early ML : Modest Successes</b> </summary>

<br/>

Early modest success of ML Model was : Google started using Statistical Model a lot in their systems, in their a lot of enterprises 
based solution like Email Spam filtering, recommendation systems.


| What Worked                             | The Bottleneck                                  |
|-----------------------------------------|-------------------------------------------------|
| Spam filters got better                 | Couldn't have a conversation                    |
| Recommendation systems (Netflix,Amazon) | Couldn't understand a paragraph                 |
| Basic image recognition                 | Couldn't recognize objects as well as a toddler |

So, we came from nasty rules to learn something from statistical data and idea back then was to filed by field apply the formaula 
everywhere and at the end we have a unified machine which have something like **Weather Predictions**, **Email Classification**, 
**Movie Recommendations**, **Destination Planning** etc kind of Models which are trained on statistical data.

Classify Something but ***not with great accuracy*** But at least we have better than what we have before.


</details>


<details>
  <summary><b>Why Early ML Was Limited </b></summary>

<br/>

`Bottleneck 01` : **Not enough data**
- Machine Learning requires massive amounts of examples to learn patterns effectively.
- Where do you get millions of labeled examples?
- The internet was in its infancy.

`Bottleneck 02` : **Not enough compute**
- Learning from data requires intense mathematical calculations.
- Computers were too slow for deep training.
- Training on millions of examples would take years.

</details>

<details>
  <summary><b>AI Winters: When Hope Died (Twice)</b></summary>

<br/>

`1970s Winter` : **The First Collapse** <br/>
Researchers promised human-level AI in 20 years. When they failed to deliver, funding dried up and interest vanished.

`1980s–90s Winter` : **The Expert System Bust** <br/>
Expert systems were supposed to revolutionize business, but they were too brittle for the real world. Funding vanished again.

> The field became a joke. Saying you worked on 'AI' was career suicide.

</details>


<details>
  <summary><b>Why AI Exploded (After 2012) </b></summary>

<br/>

`1. Data` : **The Internet** <br/>
Massive datasets of text, images, and video became available for the first time.

`2. Compute` : **GPUs** <br/>
Graphics cards, built for gaming, turned out to be perfect for the math ML needs.

`3. Algorithms` : **Deep Learning**  <br/>
Researchers finally cracked how to train much deeper and more complex neural networks.

> All three ingredients converged around 2012.

</details>

## Now Let's Go Deep on One Problem

We'll use language understanding as our lens.

<details>
  <summary> <b> Why Language is Hard for Computers</b> ?</summary>

<br/>

> "I saw the man with the telescope."
> - Who had the telescope? Me or the man?

**Computers need precision, but human language is messy, ambiguous, and context-dependent.**

A single sentence can have multiple valid interpretations, making it one of the hardest problems in AI.

> "Fast-tracking the AI course" and "Fast-tracking the course of AI"

</details>


<details>
  <summary> <b>NLP Attempt #1: The Dictionary Approach </b> </summary>

<br/>

**Apple**
`/ˈap(ə)l/`
1. The round fruit of a tree of the rose family, which typically has thin red or green skin and crisp flesh.

`The Problem` : **A dictionary definition isn't enough for real-world language.**
- "Apple" is also a trillion-dollar company.
- "Apple" is a famous record label.
Here, Context changes everything.

</details>


<details>
  <summary> <b>NLP Attempt #2: Statistical Patterns </b> </summary>

<br/>

> If 'New' is followed by 'York' =>  City

This approach powered Google Translate for nearly a decade.

`The Problem` : **Pattern Matching ≠ Understanding**

The machine could predict the next word based on frequency, but it had no concept of what the words actually meant.

</details>

<details>
  <summary> <b>The Breakthrough: Words as Numbers </b> </summary>

<br/>

**"Apple"**  ->  **[0.92, -0.14, 0.05, ...]**

Computers don't understand **words**. They understand **numbers**. 

The challenge is: how do we turn a word into a list of numbers that captures its **meaning**?

**Word Embeddings (The "Secret Sauce")**

How do we turn a word like "Apple" into a number that captures its meaning?

Instead of one number, we give each word a list of numbers (a vector).

`The Vector Representation ` of Word : "Apple" is [0.9 - color(red) , -0.1 shape(square), 0.05, ...]

Each number represents a specific "dimension" of meaning.

**Dimensions of Meaning**
| Word | Royalty | Gender (M) | Edibility |
|------|---------|------------|-----------|
| King | 0.98    | 0.95       |  0.01     |
| Queen| 0.97    | 0.05       |  0.02     |
| Apple| 0.02    | 0.00       |  0.94     |

- "King" and "Queen" have similar numbers for royalty but vastly different values for gender.
- This is how machines represent concepts as data.

**Words as Positions in Space**
- If a word is a list of numbers, it's a point on a map. **Similar words are close together**, while different words are far apart.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/f758a945-14f2-4e6f-a027-c80deb03cdc0" />


**Visualizing Word Embeddings**
- Similar words are placed close together in a multi-dimensional space.
- Proximity indicates shared meaning.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/abf037a2-e23c-4775-95d7-8230fb8eac27" />

**The Magic of Embeddings - Word Math**
`King − Man + Woman = Queen`
`Paris − France + Italy = Rome`
`Walking − Walk + Swim = Swimming`

**Can Embeddings Solve Our Earlier Problems?**

"I went to the **bank** to deposit cash" <br/>
"I sat on the **bank** of the river"

The Problem: In basic word embeddings, each word has exactly ONE position in space.

The model can't distinguish between a financial institution and a riverbank because it doesn't look at the surrounding words.

</details>

<details>
  <summary> <b>NLP Attempt #4: Sequence Models (RNNs)</b> </summary>

<br/>

Idea: Process the sentence one word at a time, building up understanding as you go.

> "I"  <br/>
> "I went"  <br/>
> "I went to"  <br/>
> "I went to the"  <br/>
> "I went to the bank..."  <br/>

The model maintains a "memory" of what it has read so far.

**The Problem: Forgetting**

`Long-Range Dependency Failure`
> "**The cat**, which was sitting on the mat that I bought from the store near the old church on the corner, **was** happy."

By the time a sequence model reaches "was," it has often **forgotten** the subject at the beginning.

RNNs struggle with long sentences because they process information linearly and have limited memory capacity.

</details>

<details>
  <summary> <b>The Stage Is Set (around 2017) </b> </summary>

<br/>

`What we had` :

**Word embeddings**

**Sequence models (RNNs)**

**Tons of internet data**

**Powerful GPUs**

`The Problem` : 

> **The Word-by-Word Bottleneck** <br/>
> Processing text sequentially was slow and models still "forgot" the beginning of long sentences.

</details>





