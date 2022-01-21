<div align=center>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F6mini%2Ffancim-project&count_bg=%23AAAAAA&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Hits&edge_flat=false)](https://github.com/6mini/fancim-project)

![image](https://user-images.githubusercontent.com/79494088/149819931-86a61380-4b43-45cf-9f47-48b76dca3dac.png)
    
# Fancim-Project
일리오의 팬심M 마케팅을 위한 데이터 분석 및 감정 분석 협업 프로젝트

<table>
    <tr height="160px">
        <td align="center" width="150px">
            <a href="https://github.com/ljs7463"><img height="120px" width="120px" src="https://avatars.githubusercontent.com/u/87054081?v=4"/></a>
            <br />
            <strong>박나현</strong>
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/leehj01"><img height="120px" width="120px" src="https://avatars.githubusercontent.com/u/79494088?v=4"/></a>
            <br />
            <strong>이윤민</strong>
        </td>
        <td align="center" width="150px">
            <a href="https://github.com/reeesource"><img height="120px" width="120px" src="https://avatars.githubusercontent.com/u/76740971?v=4"/></a>
            <br />
            <strong>이윤수</strong>
        </td>
    </tr>
    <tr height="50px">
      <td align="center">
          자연어 처리 모델링
           <br />
        </td>
        <td align="center">
            데이터 엔지니어링
            <br />
        <td align="center">
            데이터 분석
            <br />
        </td>
    </tr>
        <tr height="50px">
        <td align="center">
            <a href="https://github.com/nicolenahyun"> GitHub</a>
            <br />
        </td>
        <td align="center">
            <a href="https://github.com/6mini"> GitHub</a>
            <br />
        <td align="center">
            <a href="https://github.com/Yuns-u"> GitHub</a>
            <br />
        </td>
    </tr>
</table>

</div>

# 일리오 채팅 데이터 감정 분석 프로젝트

## 기업 소개
- 한국 1인 미디어 위주의 팬슈머(Fan과 consumer의 합성어) 시장에서 팬과 셀럽(1인 미디어 방송인)의 커뮤니티를 관리하고 그들의 상호작용을 통해 수익을 창출하는 스타트업

## 시장 니즈
- 기존의 팬들이 셀럽에게 선물하는 것외에도 셀럽이 팬들에게 선물 등의 상호작용을 안전하게 할 수 있는 플랫폼
  - 일리오: 팬케어의 일부인 역조공 서비스 개편
  - 일리오는 역조공 서비스를 개편한 뒤 유료 셀럽 사용자가 급증함

- 일리오는 셀럽이 팬들에게 선물이나 호의적인 행동을 했을 때 후원금, 선물, 팬 증가수에서 유의미한 성과(팬케어를 하지 않았을 때보다 팬관리를 했을 때 더 큰 금액, 선물 횟수, 팬 증가수를 보인다.)를 얻는다고 주장한다.

## 기업 포지셔닝
- 유튜브, 트위치 등의 미디어 채널은 팬의 유입을 도모한다면 팬심은 일반적인 의미의 팬보다 더 높은 충성도를 갖춘 찐팬(찐팬의 정의 필요, 예를 들면 시청횟수, 후원횟수, 채팅참여횟수 등)으로 고객을 전환시키고자 한다.

## 서비스 소개
- 셀럽의 입장에서는 각 팬들을 관리하는 데에 드는 시간과 비용을 단톡방으로 절약, 팬들의 입장에서는 셀럽과 1:1 대화를 하는 것처럼 소통하는 것으로 만족도 증가.
- 특히 팬심은 지불의사 금액이 높거나 지불의사 시간(광고를 끝까지 시청하는 등)이 높은 팬을 충성도가 높은 팬슈머라고 정의하고 이들을 위한 유료 콘텐츠, 굿즈 등의 IP매출 플랫폼을 확보하고 높은 단가의 광고 마케팅 등을 통한 수익 창출을 가능하게 한다.

## 팬 제공 정보
- 나이, 성별, 관심사, 연락처, 거주지역 등

---

# 목표
- 자연어 처리를 통해 채팅을 분석하여 어떤 셀럽이 팬들과 우호적인 관계를 맺는지 조사하자.

## 도출할 인사이트
- 타 커뮤니티 대비 팬심M의 차별성, 팬들이 셀럽에게 느끼는 감정 수치화


## 우리가 생각해본 데이터 분석의 목적

### 1. 셀럽의 어떠한 행동이 팬들의 우호적인 반응을 유도하는가
- 이러한 행동을 하는 셀럽은 팬들의 좋은 반응을 유도한다.
  - 셀럽의 행동유형(역조공, 사담, 팬심에서만의 콘텐츠 제공 등)을 나누고 비교,
  - 팬들의 유형별 케이스 조사를 통해 특정 행동이 각 팬들에게 얼마나 우호적인지 파악,
  - 셀럽의 우호적인 행동을 케이스 조사를 통해 롤모델을 지정하고 가이드라인을 제공할 수 있음

### 2. 팬심M이 셀럽에게 매력적인 플랫폼이 될 수 있는 방안은 무엇인가
- 이러한 고객들과 서비스가 있으니 셀럽은 팬심M을 사용하는 것이 좋다.
  - 팬 유형별 지불의사금액 및 지불의사시간 등으로 ROI(Return on Investment, 셀럽의 자원 투자로 얻는 팬들의 호응)가 높은 고객이 많다는 것을 어필,
  - 팬들의 선호행동(역조공, 사담 등)에 대한 우호도를 통해 가이드라인 제시(이런 유형에게는 이런 행동 하는 게 좋아요),
  - 팬들의 비호행동을 통한 가이드라인 제시(이런 유형에게는 이런 행동 하지 않는게 좋아요.)

---

# 과정

## 전처리
- 라벨링: 한국어 채팅 수준의 라벨링 자동화가 가능한가, KoBART사용해서 7가지 감정으로 나눌 수 있을 것 같음.
- 불용어 사전
- 어간추출 혹은 표제어 추출할 것인가
- 전처리 파이프라인

## 모델링
- 어떤 모델을 사용할지
- 모델링 후 API 개발할 것인가?

## 분석 및 시각화
- 1인 미디어의 팬 관리 산업(다이아TV 등의 대기업, 샌드박스 등의 MCN기업 등)의 구조 및 플랫폼 관리에 대한 이해 필요
- 셀럽의 유형과 팬들의 유형을 나누고 이들의 상성을 비교해볼 수 있음
- 선호행동, 비호행동 가이드라인 제시
- 타 플랫폼에 비해 팬심M만의 장점과 개선점 정리본 

---

# 프로젝트 결과
- 주어진 샘플 데이터 외 추가 데이터 전달 받지 못해 아쉽게 간단한 감정 분석 처리 진행

![image](https://user-images.githubusercontent.com/79494088/149820204-9904d98b-f5d1-4fcf-a6b9-e68bb52b6d8c.png)

![image](https://user-images.githubusercontent.com/79494088/149820230-75ea6b58-43f6-4385-a6f5-59d3bb80c9df.png)

![image](https://user-images.githubusercontent.com/79494088/149820258-6909951b-439a-43c5-92da-6ae7b6db7d8a.png)

![image](https://user-images.githubusercontent.com/79494088/149820280-4793c553-b913-4d8a-b96e-da5687433fe4.png)

![image](https://user-images.githubusercontent.com/79494088/149820294-15501b32-f6ff-4197-b03e-322ac05cad87.png)
