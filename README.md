# 일래스틱을 활용한 벡터 검색 실무 가이드

<a href="https://www.packtpub.com/product/vector-search-for-practitioners-with-elastic/9781805121022?utm_source=github&utm_medium=repository&utm_id=9781805121022"><img src="https://content.packt.com/B20870/cover_image_small.jpg" alt="Vector Search for Practitioners with Elastic" height="256px" align="right"></a>

여기는 [일래스틱을 활용한 벡터 검색 실무 가이드](https://www.packtpub.com/product/vector-search-for-practitioners-with-elastic/9781805121022?utm_source=github&utm_medium=repository&utm_id=9781805121022) 에 대한 코드 저장소 입니다. 

**벡터 검색을 활용한 검색, 가관측성 및 보안을 위한 자연어 처리 솔루션 구축 도구 모음**

## 이 책은 무엇에 관한 내용인가요?
자연어 처리(NLP)는 주로 검색 사례에서 사용되지만, 이 책은 벡터를 사용해 가관측성과 사이버 보안과 같은 중요한 분야의 도전을 극복하도록 영감을 주려 합니다. 
각 장에서는 검색과 함께 가관측성 및 사이버보안 기능을 개선하기 위해 엘라스틱과 벡터 검색을 통합하는 데 초점을 맞춥니다.

이 책은 다음과 같은 흥미로운 기능을 다룹니다.
* 벡터 검색을 활용한 성능 최적화
* 이미지 벡터 검색과 그 응용 탐구
* 개인 식별 정보 탐지 및 마스킹
* 차세대 가관측성을 위한 로그 예측 구현
* 사이버 보안을 위한 벡터 기반 봇 탐지 사용
* 벡터 공간 시각화하고 Elastic과 Search.Next 탐구
* Streamlit을 사용한 RAG 강화 애플리케이션 구현

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## 지침
모든 코드는 폴더에 정리되어 있습니다.

코드는 다음과 같이 표시됩니다.
```
{'_source':
 {
'redacted': '<PER> called in from 001-<PHONE>x1311. Their account
number is <SSN>'
'status': 'active'
}
```


**이 책의 대상 :**
일래스틱 가관측성, 검색 또는 사이버 보안 경험이 있는 데이터 전문가로서 벡터 검색에 대한 지식을 확장하고자 하는 경우 이 책이 적합합니다. 이 책은 검색 애플리케이션 소유자, 제품 관리자, 가관측성 플랫폼 소유자, 보안 운영 센터 전문가에게 유용한 실용적인 지식을 제공합니다. Python 사용, 기계 학습 모델 활용, 데이터 관리 경험이 있으면 이 책을 통해 더 많은 것을 얻을 수 있습니다.

다음 소프트웨어 및 하드웨어 목록을 사용하면 책에 있는 모든 소스코드(1-10장)를 실행할 수 있습니다.


### 필요한 소프트웨어와 하드웨어

이 책을 충분히 활용하려면 기본적으로 일래스틱서치 작업, 파이썬 프로그래밍, 검색 개념을 이해하고 있어야 합니다. 이런 기본 지식을 바탕으로 책에서 다루는 고급 기술과 응용 방법을 더욱 효과적으로 이해할 수 있습니다.

시스템 요구사항은 아래와 같습니다.

| 소프트웨어/하드웨어  | 운영체제 요구사항             |
|------------------|----------------------------|
| 일래스틱서치 8.11+ | Windows, Linus, and  MacOS |
| 파이썬 3.9+       |                            |
| 주피터 노트북      |


## 저자 소개
**바할딘 아자르미(Bahaaldine Azarmi)** : 일래스틱의 글로벌 고객 엔지니어링 부사장으로 기업이 데이터 아키텍처, 분산 시스템, 머신러닝, 생성형AI를 잘 활용하게 안내합니다. 클라우드 사용에 중심을 둔 고객 엔지니어링 팀을 이끌고 AI 분야에서 숙련된 커뮤니티를 구축하고 영감을 주려고 지식을 공유하는 데 열정을 쏟고 있습니다.

**제프 베스탈(Jeff Vestal)** : 금융 거래 회사에서 10년 이상의 경력을 쌓으며 얻은 풍부한 배경지식과 일래스틱서치에 대한 폭넓은 경험을 갖추고 있습니다. 운영 능력, 엔지니어링 기술, 머신 러닝 전문 지식이라는 독특한 조합을 가지고 있습니다. 일래스틱서치의 수석 고객 엔터프라이즈 아키텍트로 일하면서 일래스틱서치의 고급 검색 기능, 머신 러닝 기능, 생성형 AI 통합을 활용해 사용자가 복잡한 데이터 문제를 실행할 수 있는 인사이트로 전환할 수 있도록 능숙하게 안내하는 혁신적인 솔루션을 만드는 데 탁월한 역량을 발휘합니다.
