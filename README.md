# 태양흑점 데이터 분석 대시보드

Streamlit을 사용한 태양흑점 데이터 시각화 대시보드입니다.

## 설치 방법

1. 가상환경 생성 (권장)
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# 또는
venv\Scripts\activate  # Windows
```

2. 패키지 설치
```bash
pip install -r requirements.txt
```

## 실행 방법

```bash
streamlit run Question2_streamlit.py
```

브라우저에서 자동으로 열리며, 기본 주소는 `http://localhost:8501` 입니다.

## 기능

- 시계열 라인 차트
- 히스토그램 및 커널 밀도 추정
- 상자 그림 (1900-2000년)
- 산점도 및 회귀선

## 파일 구조

```
Question2_streamlit/
├── Question2_streamlit.py  # 메인 Streamlit 앱
├── data/
│   └── sunspots.csv        # 태양흑점 데이터
├── requirements.txt        # 필요한 패키지 목록
└── README.md              # 이 파일
```

