# IBAbooth

## 선택지
연상 연하 동갑

## matrix 구성
### 선호나이차 칼럼 인코딩
연상 +1
동갑 0
연하 -1

### 남자 선호기준 matrix
1. 남자 행렬 reshape
2. (남-여) 나이차 행렬: 남자(row)&여자(col)
3. 참가자들의 실제 나이차 행렬
4. 실제 나이차 행렬 인코딩: 남-녀>0면 -1(상대가 연하이므로)
5. 선호 나이차=실제 나이차: 50점 부여, 나머지 0점

### 여자 선호기준 matrix
1. 여자 행렬 reshape
2. (여-남) 나이차 행렬: 여자(row)&남자(col)
3. 이하 남자기준 행렬과 동일

### 0 matrix

## 최종 matrix: concat

row,col=남20 여20 

0 남자기준
여자기준 0

