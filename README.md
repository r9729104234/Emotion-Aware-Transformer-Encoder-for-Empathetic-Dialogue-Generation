# Emotion-Aware-Transformer-Encoder-for-Empathetic-Dialogue-Generation

Modern-day conversational agents are trained to emulate the manner in which humans communicate while addressing user concerns that may range from medical assistance to customer care service. To gain human trust, and emotionally bond with the user, these virtual agents need to be aware of the affective state of the user. Transformer-based dialogue generators are the recent state of the art in sequenceto-sequence learning that involves training an encoder-decoder model with word embeddings from utterance-response pairs. We propose an emotion-aware transformer encoder for capturing the emotional quotient in the user utterance in order to generate human-like empathetic responses. The contributions of our paper are as follows: 
1) An emotion detector module trained on the input utterances determines the affective state of the user in the initial phase 
2) A novel transformer encoder is proposed that adds and normalizes the word embedding with emotion embedding thereby integrating the semantic and affective aspects of the input utterance 
3) The encoder and decoder stacks belong to the Transformer-XL architecture which is the recent state of the art in language modeling.

Experimentation on the benchmark Facebook AI empathetic dialogue dataset confirms the efficacy of our model from the higher BLEU-4 scores achieved for the generated responses, as compared to existing methods. Emotionally intelligent virtual agents are now a reality and inclusion of affect as a modality in all human-machine interfaces is foreseen in the immediate future.

