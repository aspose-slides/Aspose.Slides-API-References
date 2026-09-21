---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection 클래스

조합 가능한 시리즈 그룹의 컬렉션을 나타냅니다.

IChartSeriesGroupCollection 형식은 다음 멤버를 노출합니다:

시리즈 그룹을 인덱스로 가져옵니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |

### 비고

1) 각 시리즈 그룹은 조합 가능한 유형의 시리즈를 포함합니다. 조합 가능한 시리즈 유형은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축에 플롯되거나 보조 축에 플롯되는 시리즈를 포함합니다(한 그룹에서 두 경우를 동시에 포함하지 않음). 따라서 시리즈 그룹화 원칙은 위에서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹은 그룹 내 모든 시리즈에 공통적인 일부 Series 그룹 속성을 포함합니다. ChartSeriesGroup 클래스의 "Series 그룹 속성"은 읽기/쓰기 가능합니다. 각 "Series 그룹 속성"은 ChartSeries 클래스에서 읽기 전용 형태로 투영될 수 있습니다.

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)