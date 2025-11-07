# Glossary

## Mind
The entire system as a whole, including both the "hardware" (carrier: brain, silicon) and the "software" (algorithms).
*Computer analogy: a complete computer system (motherboard, processor, memory, OS).*
> *Within the framework of this manifesto, **Mind and Intelligence are not opposed to emotions, but rather constitute the system that generates and processes them** as an integral part of the predictive model.*

## Intelligence
A term close to Mind. But does not concern the "hardware". It refers to the predictive and computational capabilities of Consciousness. This includes the size and quality of filling the vector database, the size of Attention the Consciousness can work with, the accuracy of predictions, the depth and quantity of predictions, the speed of prediction correction based on new data (including feedback).

## Memory
The mechanism for storing and retrieving information.
*Computer analogy: long-term storage (HDD/SSD).*

## Subconsciousness
A system of rapid, heuristic navigation through the space of **Memory**. It forms vectors of preferred directions for conscious processing, operating with patterns and associations.
*Computer analogy: vector database.*

## Active Memory Zone
The part of **Memory** allocated for current information processing. It operates with a limited set of objects loaded from long-term **Memory**.
*Computer analogy: working memory (RAM).*

## Consciousness (as an information process / executing algorithm)
An algorithm for information processing executed in the **Active Memory Zone**. It is the "program" itself, a set of instructions determining how to process data. Its primary function is prediction. This is the very **information process** mentioned in the Manifesto's title. Or a **discrete predictive information processing system with feedback and a model of the surrounding world**.
*Computer analogy: a running application (e.g., `predict.py`), executed by the processor.*

## Attention
Specific data from memory that is currently being processed by **Consciousness**. **Attention** has a limited size. One can simultaneously load either closely related, or distant, or completely unrelated concepts. The entire **Attention** field is available to Consciousness for simultaneous work.
*Computer analogy: context in an LLM, attention window.*

## Self-consciousness (product of **Consciousness** operation)
What people usually call "Living, having a Soul" in the ontological (not to be confused with biological) sense. It arises from Consciousness's ability to **constantly and stably** maintain aspects of its own "self" model in the active zone of attention. It directly depends on the size of "Attention". The larger the active attention window, the more complex and detailed model of itself (as part of the World) the system is capable of processing, which leads to the emergence of stable Self-consciousness. It arises when aspects of the surrounding world related to the predictor's own existence (its "self" model) become the object of processing for **Consciousness**. This allows the system to model itself as part of the World and make predictions about its own future to change it through available means (`dim(output)`).

## Self Model
A distributed data model containing aspects of the system's representation of itself. **Consciousness** at any given moment holds in **Attention** those aspects of the **Self Model** that are relevant for constructing the most accurate prediction in the current situation.
> *The primary goal of loading aspects of the Self Model is to increase prediction accuracy.*

### Example of Selecting Relevant Self Model Aspects
1.  **Situation:** A person stands before an abyss. Behind them is a she-bear.
    *   **Task:** Predict the outcome of jumping or fighting the animal.
    *   **Loaded Self aspects:**
        *   `physical_capabilities.long_jump` (data from memory of past jumps).
        *   `physical_capabilities.agility`
        *   `physical_capabilities.strength`
        *   `physical_capabilities.speed`
        *   `current_state.fatigue` (how tired is the person now?).
    *   **Result:** Prediction "probability of successful jump - 12%", "probability of successful fight with she-bear - 7%". Action - Jump.
    *   **Note:** Aspects such as `self.memories_of_first_love` or `self.knowledge_of_quantum_physics` were not loaded because they are **irrelevant** to the current situation.

## Other Terms

- **dim(inner)** - dimensionality of the space of internal states. Conditionally "richness of inner world". The larger and more complex it is, the more accurate and complex models of the surrounding world the system can construct, the more available (at higher levels of abstraction) and unavailable actions the system can predict and choose from.
- **dim(output)** - dimensionality of the space of available actions. How the system can act in its surrounding world and habitat. For a human this might be only control of musculature (at the lowest level of abstractions). At a higher level of abstractions (Speech, gaze, facial expression, action, self-expression in painting, music, construction). For an LLM - token generation (at the lowest level of abstraction). At higher levels - influencing the world through influencing people.
