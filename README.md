# 강의 계획서: 단일 세포 시퀀싱 응용을 통한 대용량 생물학을 위한 응용 통계

## 강사

Levi Waldron, PhD  
생물통계학 교수
City University of New York School Graduate of Public Health and Health Policy  
New York, NY, U.S.A.  

이메일: lwaldron.research@gmail.com

## 요약

본 과정은 생물학자 및 생물정보학자에게 단일 세포 시퀀싱에 중점을 둔 응용 프로그램을 사용하여 대용량 생물학적 데이터의 엄격한 분석을 수행하는 데 필요한 실용적인 통계 및 데이터 분석 기술을 제공합니다. 본 과정은 유전체학 및 R 프로그래밍에 대한 약간의 친숙도를 가정하지만 사전 통계 교육을 가정하지는 않습니다. 탐색적 데이터 분석, 선형 모델링, 범주형 변수 분석, 주성분 분석 및 기타 차원 축소 방법, 다중 가설 검정, 배치 효과 등 유전체 기술로 생성된 고차원 데이터를 설계하고 분석하는 데 필요한 통계적 개념을 다룹니다.

## 교재

* 주교재: Irizarry 및 Love의 [Biomedical Data Science](https://genomicsclass.github.io/book/) ([Leanpub의 ePub 버전](https://leanpub.com/dataanalysisforthelifesciences/))
    + [소스 저장소](https://github.com/genomicsclass/labs)
* 부교재: Holmes 및 Huber의 [Modern Statistics for Modern Biology](https://www.huber.embl.de/msmb/)
* 실습 자료: Amezquita, Lun, Hicks, Gottardo, O’Callaghan의 [Orchestrating Single-Cell Analysis with Bioconductor](https://bioconductor.org/books/release/OSCA/) (OSCA)

## 실습

매일 [Orchestrating Single-Cell Analysis with Bioconductor](https://bioconductor.org/books/release/OSCA/)의 실습 세션이 포함되며, 학생들은 전체 내용을 시도해야 합니다.

## 일별 세션 세부 정보

강의 자료는 https://waldronlab.io/AppStatBio/ 에서 HTML 형식으로 제공됩니다.

1. 소개
- 무작위 변수
- 분포
- 하나 또는 두 개 샘플에 대한 가설 검정 (t-test, Wilcoxon test 등)

2. 차원 축소
- 고차원의 거리
- 주성분 분석 및 특이값 분해
- 다차원 스케일링
- t-SNE 및 UMAP

3. 선형 모델링
- 다중 선형 회귀
- 모델 공식
- 일반화 선형 모델
- 다중 가설 검정

4. 탐색적 데이터 분석 및 배치 효과
- 탐색적 데이터 분석을 위한 플롯
- 배치 효과에 대하여
