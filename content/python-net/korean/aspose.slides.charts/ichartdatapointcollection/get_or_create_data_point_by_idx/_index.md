---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
컬렉션에 이미 인덱스 `index`인 데이터 포인트가 포함되어 있으면 해당 데이터 포인트를 반환합니다.
컬렉션에 인덱스 `index`==N인 데이터 포인트가 없고(이 컬렉션의 데이터 포인트 수가 N 이하인 경우) 부족한 데이터 포인트를 추가하고 마지막 데이터 포인트(요청된 인덱스를 가진)를 반환합니다.
예를 들어, 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우, 메서드는 부족한 데이터 포인트들을 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

### 반환

요청된 인덱스의 데이터 포인트를 반환합니다.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 인덱스. |



### 참고
* 클래스 [`IChartDataPoint`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint)
* 클래스 [`IChartDataPointCollection`](/slides/python-net/ko/aspose.slides.charts/ichartdatapointcollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)