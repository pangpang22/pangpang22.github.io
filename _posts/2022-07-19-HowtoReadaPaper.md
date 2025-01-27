---
layout: post
title: "｢논문 독법｣(2007)"
description: "｢How to read a paper｣(2007) 번역."
date: 2022-07-19
tags: [논문, 번역, 컴퓨터과학]
comments: true
share: true
published: true
---
*이 포스팅은 현재 케임브리지 대학교 소속 S. Keshav가 워털루 대학교 재직 시절 작성한 ｢[How to read a paper](https://dl.acm.org/doi/10.1145/1273445.1273458)｣(2007)를 번역한 것이다.*

---

## 요약

연구자는 많은 시간을 연구 논문 독해에 할애한다. 하지만 연구 논문 독해 기술은 거의 교육되지 않는다. 막대한 노력 낭비가 이어진다. 본고는 연구 논문 독해를 위한 실용적이며 효율적인 <mark>삼단계 방법</mark>(three-pass method)을 약술한다. 또 어떻게 삼단계 방법을 문헌 조사에 사용하는지 설명한다.

## 1. 서론

학회나 수업을 위한 검토, 분야의 동향에 대한 파악, 새 분야에 관한 문헌 조사 등. 연구자는 다양한 이유로 논문을 읽어야 한다. 보통 연구자는 매년 수백 시간을 논문 독해에 쏟는다.

논문 독해에는 효율이 필요하다. 연구자는 이런 효율을 익혀야 한다. 하지만 아무도 이런 기술을 가르치지 않는다. 따라서 대학원에 막 입학한 학생은 시행착오를 거쳐 스스로 배워야 한다. 신입생은 많은 힘을 낭비하고 흔히 좌절감에 사로잡힌다.

다년간 나는 논문 독법 효율에 단순한 접근을 취했다. 본고는 이른바 '삼단계' 접근을 설명하고 어떻게 삼단계 접근을 문헌 조사에서 사용하는지 보인다.

## 2. 삼단계 접근법

핵심은 이렇다. 논문을 처음부터 끝까지 쟁기질하지 말라. 세 단계로 나눠라. 각 단계에서는 특정 목표를 성취한다. 그리고 이전 단계를 토대로 나아간다. <mark>첫 번째</mark> 단계는 논문에 관한 일반 발상을 제공한다. 각 단계에서는 특정 목표를 성취하며 이전 단계를 토대로 한다. <mark>첫 번째</mark> 단계는 논문에 관한 일반적인 아이디어를 취한다. <mark>두 번째</mark> 단계는 논문의 내용을 쥘 수 있도록 하되, 그 디테일은 내버려 두도록 한다. <mark>세 번째</mark> 단계는 논문을 깊이 이해하도록 한다.

### 2.1 1단계

1단계는 일별(一瞥)의 단계다. 논문의 조감도를 취하기 위한 것이다. 또 이어지는 단계가 꼭 필요한지 결정할 수 있는 단계다. 1단계는 5분에서 10분가량 걸릴 것이다. 다음처럼 구성된다.

1. 제목, 요약, 서론을 주의 깊게 읽는다.
2. 절과 소절의 제목을 읽되 나머지는 전부 무시한다.
3. 결론을 읽는다.
4. 참고 문헌을 일별하며 이미 읽은 것이 있는지 스스로 힐책한다.

1단계가 끝날 무렵 이른바 <mark>다섯 C</mark>를 답할 수 있어야 한다.

1. Category: 이 논문의 유형은 무엇인가? 측량 논문인가? 현존 체계의 분석인가? 연구 프로토타입의 기술인가?
2. Context: 어떤 다른 논문이 연관되어 있는가? 어떤 이론적 기초가 이 문제를 분석하는 데 사용되었는가?
3. Correctness: 가정이 타당해 보이는가?
4. Contributions: 논문의 주요 공헌이 무엇인가?
5. Clarity: 논문이 잘 작성되었는가?

이들 정보를 이용해 후속 독해를 결정할 수 있다. 논문이 더는 흥미롭지 않을 수 있다. 혹은 분야를 충분히 이해하지 않기에 논문을 더는 이해할 수 없을 수 있다. 혹은 저자가 타당하지 않은 가정을 내릴 수도 있다. 1단계는 당신의 연구 분야가 아니지만 언젠가 유관할지도 모르는 분야에 속하는 논문 독해에 적합하다.

그런데 논문을 쓸 적에는 대다수 검토자(와 독자)가 오직 한 단계만의 독해를 취하리라고 예상할 수 있다. 그러니 절과 소절 제목을 명징하게 지어라. 간결하고 종합적인 요약을 작성하도록 노력하라. 검토자가 한 번의 단계만으로 요지를 파악할 수 없다면 논문은 거절 받기 십상이다. 독자가 논문 핵심을 5분이 지나서도 이해할 수 없다면 아마 절대 읽히지 않으리다.

### 2.2 2단계

2단계는 논문을 더 주의 깊게 읽되 증명과 같은 디테일을 무시하는 단계다. 읽어가며 핵심 사항을 적어 내리고 (jot down) 여분에 논평을 작성하기 용이한 단계다.

1. 다이어그램과 그림을 자세히 보라. 그래프에 특별한 주의를 기울여라. 좌표축이 제대로 레이블 되었는가? 결과에 오류가 있는가? 결론에 통계적인 오류는 없는가? 이와 같은 일반적인 실수는 실로 훌륭한 연구와 성급하고 조잡한 연구를 구분할 것이다.
2. 유관하지만 읽은 적 없는 참고 문헌을 기억하도록 표기한다. (이는 논문의 배경에 관해 배울 수 있는 좋은 방법이다.)

2단계는 한 시간 정도 걸릴 것이다. 이 단계 이후에는 논문의 내용의 감이 잡힐 것이다. 다른 사람에게 보조 증거와 함께 논문의 주된 요점을 요약할 수 있어야 한다. 이 수준의 디테일은 당신이 관심을 갖지만 연구 분야는 아닌 논문에 대해 적합하다.

어떤 때는 2단계에도 논문을 이해할 수 없을지도 모른다. 주제가 새롭고 용어와 약자가 낯선 탓일 수도 있다. 혹은 당신이 이해하지 못하는 증명이나 실험적 기법을 저자가 사용하여 논문 한 뭉치가 불가해할 수도 있다. 논문이 근거 없는 주장과 수많은 선행참조로 서투르게 작성되었을 수도 있다. 혹은 밤이 늦어 그냥 피곤한 것일 수도 있다. 이제 당신은 고르면 된다. (가) 논문을 치우기, 당신의 성공적인 진로에 이 내용을 이해할 필요가 없기를 바라며. (나) 다음에 논문으로 돌아오기, 가능하면 배경 내용을 읽고 나서. (다) 인내심을 갖기, 그리고 3단계로 나아가기.

### 2.3 3단계

논문을 완전하게 이해하기 위해서는, 특히 당신이 검토자라면, 3단계를 요구한다. 3단계를 향한 열쇠는 논문을 <mark>가상적으로 재구현</mark>하려는 시도다. 즉, 저자와 같은 가정을 취해 연구를 재창조하는 것이다. 이런 재창조를 실제 논문과 비교하여 논문의 혁신만이 아니라 숨겨진 실패와 가정까지 쉽게 식별할 수 있다.

이 단계는 디테일에 대한 많은 관심을 요구한다. 모든 명제에서 모든 가정을 식별하고 이의를 제기해야 한다. 이와 더불어 당신이라면 어떻게 특정 아이디어를 제시할지 고찰해야 한다. 이와 같은 실제와 가상적인 아이디어 간의 비교는 논문상의 증명과 표현 기법에 대한 날카로운 통찰로 이어지고 당신은 분명 당신의 레퍼토리에 이를 추가할 수 있을 것이다. 이 과정에서 향후 연구를 위한 아이디어를 적어 내리기도 해야 한다.

초심자에게 이 단계는 네다섯 시간 정도 걸릴 것이다. 그리고 경험이 있는 독자에게는 한 시간 정도 걸릴 것이다. 단계가 끝날 무렵에는 논문의 전체 구조를 기억에서 재구성할 수 있어야 한다. 그 장점과 약점 또한 식별할 수 있어야 한다. 특히 암시적인 가정과 연관 연구에서 빠진 참고 문헌과 실험적이거나 분석적인 기법에 관해 가능한 사안을 정확히 짚을 수 있어야 한다.

## 3. 문헌 조사

논문 독해 기술은 문헌 조사에서 시험대에 오른다. 문헌 조사는 당신으로 하여금 수십 편의 논문을 읽도록 하며, 이들 논문은 어쩌면 익숙하지 않은 분야의 논문일지도 모른다. 어떤 논문을 읽어야 할 것인가? 여기 삼단계 접근법이 도움이 되도록 사용할 수 있는 방법이 있다.

우선 구글 스칼라([Google Scholar](https://scholar.google.com/))나 사이트 시어([CiteSeer](http://citeseerx.ist.psu.edu/index;jsessionid=802EAC06AD1A65A897EFE0745DFCABDC))와 같은 학술 검색 엔진과 선별한 키워드를 사용해 그 분야의 <mark>최근</mark> 논문을 셋에서 다섯 편 정도를 찾는다. 논문마다 하나씩 단계를 거쳐 연구에 대한 감을 잡고, 그런 다음 이들 논문의 관련 연구 절을 읽는다. 당신은 최근 연구의 섬네일 요약을 찾을 것이고, 어쩌면 운이 좋다면 최근 조사(survey) 논문을 가리키는 포인터를 발견할 수도 있다. 그러한 조사 논문을 찾을 수 있다면, 끝난 것이다. 조사 논문을 읽고, 당신의 행운에 자축하라.

그렇지 않다면 두 번째 단계로 진입해 참고문헌에서 공유된 인용 문헌과 반복된 저자명을 찾아라. 이들은 그 분야에서 핵심 논문 및 연구자들이다. 핵심 논문을 다운로드하고 잠시 보관하라. 그런 다음 핵심 연구자들의 웹사이트로 들어가 이들이 최근 어디서 논문을 공개했는지 확인하라. 이는 그 분야의 상위 학회를 식별하는 데 도움을 줄 것이다. 왜냐하면 최고의 연구자들은 보통 최상의 학회에 논문을 발표하기 때문이다.

세 번째 단계는 이들 최상 학회들의 웹사이트로 들어가 그 회보를 살펴보는 것이다. 빠른 스캔으로도 일반적으로 최신 고품질 관련 연구를 식별된다. 이들 논문은 앞서 보관한 것과 더불어 당신의 조사의 첫 번째 판본을 구성한다. 이들 논문으로 두 단계를 거친다. 이들 모두 앞서 발견하지 못한 핵심 논문을 참고한다면 확보하고 읽어라. 필요한 만큼 반복하라.

## 4. 경험

학회 회보 독해, 논평 작성, 배경 연구, 논의 전의 짧은 논문 검토 등. 나는 이 접근을 지난 15년간 취했다. 이렇게 훈련된 접근법은 내가 조감도를 취하기 전에 디테일에 잠식하지 않도록 예방해주었다. 내게 논문 뭉치를 검토에 요구되는 시간을 추정할 수 있도록 허락했다. 다른 무엇보다 나는 내 필요와 내게 주어진 시간에 따라 논문 감정의 깊이를 조정할 수 있다.

## 5. 관련 작업

논평을 작성하기 위해 논문을 읽고 있다면 [Timothy Roscoe](https://inf.ethz.ch/people/person-detail.roscoe.html)의 "시스템 학회를 위한 논평 작성"<sup>[1](#footnote_1)</sup>에 관한 논문도 읽어야 한다. 기술 논문을 작성할 예정이라면 [Henning Schulzrinne](https://www.cs.columbia.edu/~hgs/)의 종합적인 웹사이트<sup>[2](#footnote_2)</sup>와 [George Whitesides](https://gmwgroup.harvard.edu/)가 그 절차에 관해 남긴 탁월한 개요<sup>[3](#footnote_3)</sup>를 모두 참고해야 한다.

## 6. 요청 사항

나는 이것을 살아있는 문서로 만들고 싶다. 의견을 수용하면서 업데이트하고 싶다. 발전을 위한 아무 의견이나 제안을 위해 잠시만 시간을 내서 이메일을 달라. 또 CCR의 온라인 에디션인 CCRo<sup>[4](#footnote_4)</sup>에 코멘트를 남길 수도 있다.

## 7. 감사의 말

이 문서는 내 학생 Hossein Falaki, Earl Oliver, Sumair Ur Rahman에 의해 초안이 작성되었다. 감사를 전한다. 나는 또한 Christophe Diot의 통찰력 있는 의견과 Nicole Keshav의 예리한 퇴고로 도움을 받았다.

이 연구는 캐나다 국립 과학 기술 위원회, 캐나다 연구 위원장 프로그램, 노텔 네트웍스, 마이크로소프트, 인텔 코퍼레이션, 스프린트 코퍼레이션의 연구비로 지원되었다.

## 8. 참고 문헌

<a name="footnote_1">1</a>: T. Roscoe, "Writing Reviews for Systems Conferences,"
[https://people.inf.ethz.ch/troscoe/pubs/review-writing.pdf](https://people.inf.ethz.ch/troscoe/pubs/review-writing.pdf)

<a name="footnote_2">2</a>: H. Schulzrinne, "Writing Technical Articles,"
[https://www.cs.columbia.edu/~hgs/etc/writing-style.html](https://www.cs.columbia.edu/~hgs/etc/writing-style.html)

<a name="footnote_3">3</a>: G.M. Whitesides, "Whitesides' Group: Writing a Paper,"
[https://gmwgroup.harvard.edu/publications/whitesides-group-writing-paper](https://gmwgroup.harvard.edu/publications/whitesides-group-writing-paper)

<a name="footnote_4">4</a>: ACM SIGCOMM Computer Communication Review Online, [http://www.sigcomm.org/ccr/drupal/](http://www.sigcomm.org/ccr/drupal/)
