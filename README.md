# BigContest

- 9월 4일(목): Repository 생성
- 9월 8일(월): 대회 데이터 불러오기

```
# 파일 DataFrame로 불러오는 방법
# 판다스 임포트
import pandas as pd

# 파일 경로 지정
# (.. 은 폴더 한칸 위로 올라간다고 생각)
# (파일명과 형식까지 꼭 지정)
file_path = '../Data/big_data_set1_f.csv'   # 1, 2, 3을 꼭 바꾸기

# pd의 read_csv로 DataFrame화
# (file_path 대신 직접 경로를 입력해도 무방)
# (대회 데이터는 cp949로 인코딩 되어 있어요)
pd.read_csv(file_path, encoding='cp949')   # 해당 정보를 변수에 저장하기

# 더 좋은 방식이 있다면 얼마든지 알려주세요!
```

