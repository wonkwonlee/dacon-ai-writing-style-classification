# DACON 소설 작가 분류 AI 경진대회

2021.04.23부터 2021.04.30까지 진행된 멋쟁이사자처럼 소설 작가 분류 AI 경진대회

지난 2020년 10월 29일부터 2020년 12월 4일까지 진행된 [DACON 소설 작가 분류 AI 경진대회](https://dacon.io/competitions/official/235670/overview/description/)를 바탕으로 진행헸다.

![timeline](eda/timeline.png)

[최종 프레젠테이션 PDF](submission/nlp_writing_style_presentation.pdf)
    
## 소설 작가 분류 데이터 시각화
### 작가 별 최다 사용 단어 상위 10개 (불용어 포함)
![most_words_w_stopword](./eda/most_words_w_stopword.png)
### 작가 별 최다 사용 단어 상위 10개 (불용어 미포함)
![most_words_wo_stopword](./eda/most_words_wo_stopword.png)
### 작가 별 최다 사용 단어 상위 10개 (불용어 미포함, 문장부호 포함)
![most_words_w_punctuation](./eda/most_words_w_punctuation.png)
### 작가 별 최다 사용 단어 상위 10개 (불용어 미포함, 콜론, 세미콜론 포함)
![most_words_final](./eda/most_words_final.png)


## 소설 작가 분류 데이터 형용사/부사 시각화
### Adjective
![1](eda/word_cloud_adj.png)
![2](eda/words_adj.png)

### Adverb
![3](eda/word_cloud_adv.png)
![4](eda/words_adv.png)


## 소설 작가 분류 실험 결과

### Word2Vec + LSTM
![01](result/01_word2vec+lstm.png)
### Glove + LSTM
![02](result/02_glove+lstm.png)
### Word2Vec + LSTM Modified
![03](result/03_word2vec+lstm_modified.png)
### Glove + LSTM Modified
![04](result/04_glove+lstm_modified.png)
### Word2Vec + GLU Modified
![05](result/05_word2vec+gru.png)
### Word2Vec + CNN
![06](result/06_word2vec+cnn.png)
### Glove + CNN
![07](result/07_glove+cnn.png)
### Word2Vec + CNN Modified
![08](result/08_word2vec+cnn_modified.png)
### Glove + CNN Modified
![09](result/09_glove+cnn_modified.png)
### Word2Vec + Bi-LSTM
![10](result/10_word2bec+bi-lstm.png)
### Glove + Bi-LSTM
![11](result/11_glove+bi-lstm.png)
### Word2Vec + Bi-LSTM Modified
![12](result/12_word2bec+bi-lstm_modified.png)
### Glove + Bi-LSTM Modified
![13](result/13_glove+bi-lstm_modified.png)
### Word2Vec + Bi-LSTM Modified (RMSProp optimizer)
![14](result/14_word2bec+bi-lstm_rmsprop.png)
### Glove + Bi-LSTM Modified (RMSProp optimizer)
![15](result/15_glove+bi-lstm_rmsprop.png)
### Word2Vec + Bi-LSTM Modified (RMSProp optimizer, lr = 0.001)
![16](result/16_word2bec+bi-lstm_rmsprop.png)
### BERT model
![17](result/17_bert_summary.png)
![18](result/18_bert.png)
### Accuracy Result
![19](result/19_all_accuracy.png)
