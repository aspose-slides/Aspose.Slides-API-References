---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
차트 데이터를 원본 워크북에서 다시 로드하여 새로 고칩니다.

```python
def refresh_data(self):
    ...
```

### 비고

차트가 외부 워크북을 사용하는 경우, 호출 시점에 워크북에 접근할 수 있어야 합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 지원되지 않는 워크북 형식이거나, [`ChartData.data_source_type`](/slides/python-net/ko/aspose.slides.charts/chartdata/data_source_type)가<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ko/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK)이며 외부 워크북에 접근하거나 로드할 수 없는 경우에 발생합니다. |

### 참고
* 클래스 [`ChartData`](/slides/python-net/ko/aspose.slides.charts/chartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)