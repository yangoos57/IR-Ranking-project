# Sentence Bert from scratch

- `Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks`논문을 코드로 구현하였습니다.

- Sbert를 기반으로 도서 키워드 추출 모델을 제작하였고, 이를 활용해 [도서관 컴퓨터 & 데이터 분야 장서를 추천하는 서비스](https://github.com/yangoos57/dodomoa)를 개발하였습니다.

> Sentence Bert에 대한 상세한 정리는 [Sentence Bert 구조 소개 및 코드 구현](https://yangoos57.github.io/blog/DeepLearning/paper/Sbert/Sbert)을 참고바랍니다.

<br/>

## 프로젝트 상세

#### sbert_tutorial

- Bi-Encoder와 Cross-Encoder를 코드로 구현하고, 논문을 코드 기반으로 이해할 수 있도록 튜토리얼을 작성하였습니다.

  <br/>

  <img src='images/Bi_vs_Cross-Encoder.png' alt='Bi_vs_Cross-Encoder' width='400px'>

  <em>사진 출처 : sbert.net</em>

  <br/>

#### keyword_extraction_using_sbert

- Bi-Encoder를 활용해 도서 핵심 키워드를 추출하는 모델을 구현하였습니다.

  <img src='images/key_extraction.png' alt='key_extraction' width='350px'>

## 참고한 라이브러리

- [sentence Bert](https://github.com/UKPLab/sentence-transformers)

- [KeyBert](https://github.com/MaartenGr/KeyBERT)
