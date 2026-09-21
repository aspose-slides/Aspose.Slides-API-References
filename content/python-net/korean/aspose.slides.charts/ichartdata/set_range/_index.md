---
title: set_range method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
차트 데이터 범위를 설정합니다. 새로운 데이터 범위를 기준으로 시리즈와 범주가 업데이트됩니다.
데이터 범위에 포함된 시리즈 수가 차트 데이터에 있는 시리즈 수보다 많으면 현재 컬렉션에서 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다.


```python
def set_range(self, formula):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| formula | **str** | 셀 데이터 범위 수식입니다. 예: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula가 None인 경우. |
| **RuntimeError(Proxy error(ArgumentException))** | formula의 형식이 올바르지 않은 경우. |



### 참고
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)