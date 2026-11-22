---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
차트 데이터 범위를 설정합니다. 시리즈와 범주는 새로운 데이터 범위에 따라 업데이트됩니다.
If amount of series in data range greater than count of series in the chart data then additional series with the same type
as a last series in the current collection will be added to the end of the collection.
데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.


```python
def set_range(self, formula):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| formula | **str** | 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula는 None입니다. |
| **RuntimeError(Proxy error(ArgumentException))** | formula는 잘못된 형식입니다. |



### 참고
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)