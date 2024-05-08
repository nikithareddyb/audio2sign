Audio2Sign: Using Transformer and ASLGAN

Approximately five percent of the world's population is hearing-impaired and often depends on middlemen to translate speech. However, learning sign language is a challenging task, resulting in limited and sometimes unreliable translators. With an objective to reduce the communication gap, the research proposes a novel Speech to Sign Language Video Production system. The proposed system leverages deep learning approaches in each part of a multi-stage Sign language production. A primary stage is a text-to-pose translation that uses the Transformer model to generate gloss words that enhance translation performance. The gloss words are further mapped from the skeleton pose sequences database. The established database is created from an overlapped gloss vocabulary of ASLG-PC12 (text-to-gloss) and ASLLVD (gloss-to-sign language videos). DWPose plays an essential role in performing the data processing step of deriving the skeleton image from each frame of the sign video dataset In a secondary stage, input of the skeleton sequence uses the state-of-the-art Conditional Generative Adversarial Networks to infer and construct a realistic video. The existing systems in SLP are rather complex for a hearing impaired to interpret and adapt towards their usability, hence proposed research emphasizes a simplistic approach with an uncompromised video quality production. The proposed system takes an input of English speech and translates it into an American Sign Language (ASL) video. For the lingual (gloss) sign output, the BLEU metric is used to compute a precision score. A BLEU score of 61 is achieved with a trained transformer model. ASLGAN architecture is introduced as a conditional image generation model which is fine-tuned on an ASLLVD dataset to produce a promising SSIM score of 0.93.
