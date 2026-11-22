---
title: refresh_data method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
從來源工作簿重新載入，刷新圖表資料。


```python
def refresh_data(self):
    ...
```


### 備註

如果圖表使用外部工作簿，則在呼叫時必須能存取該工作簿。

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當工作簿格式不受支援，或當 [`ChartData.data_source_type`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata/data_source_type) 為<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/zh-hant/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) 且外部工作簿無法存取或載入時，拋出此例外。 |



### 另請參閱
* 類別 [`ChartData`](/slides/python-net/zh-hant/aspose.slides.charts/chartdata)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)