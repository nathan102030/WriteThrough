# WriteThrough
The following research initiative is an attempt to formalize the handwriting recog-
nition and recommendation process through the chaining of optical character
recognition (OCR) models, word embeddings, and conditional general adversar-
ial networks (cGANs). The report will outline a proposed pipeline for converting
images of handwriting to handwritten recommendations of the next word in the
sentence, tackle strengths and limitations of the proposed pipeline, while also dis-
cussing published research initiatives tackling similar issues. Through the chain-
ing of a Transformer-based OCR model, a tri-gram word embedding, and a con-
ditional GAN for generating handwritten letters, our team was able to build a
pipeline that successfully provided pseudo-handwritten next-word recommenda-
tion for a handwritten sentence.
