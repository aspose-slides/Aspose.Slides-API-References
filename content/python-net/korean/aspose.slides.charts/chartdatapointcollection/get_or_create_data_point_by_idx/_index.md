---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            컬렉션에 이미 인덱스 `index`를 가진 데이터 포인트가 존재하면 해당 데이터 포인트를 반환합니다.
            If collection doesn't contains data point with index `index`==N
            (이 컬렉션의 데이터 포인트 수가 N 이하인 경우)
            then adds deficient data points and returns last (which has requested index).
            (그런 다음 부족한 데이터 포인트를 추가하고 마지막(요청한 인덱스를 가진) 데이터를 반환합니다.)
            For example, collection indexes are {0, 1, 2}, and requested index is 5.
            예를 들어, 컬렉션 인덱스가 {0, 1, 2}이고 요청된 인덱스가 5인 경우입니다.
            Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.
            그러면 메서드는 부족한 데이터 포인트를 추가합니다: {0, 1, 2, 3, 4, 5}. 그리고 인덱스 5인 데이터 포인트를 반환합니다.

### 반환값

요청된 인덱스를 가진 데이터 포인트를 반환합니다.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 인덱스. |



### 참조
* 클래스 [`ChartDataPointCollection`](/slides/python-net/ko/aspose.slides.charts/chartdatapointcollection)
* 클래스 [`IChartDataPoint`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)