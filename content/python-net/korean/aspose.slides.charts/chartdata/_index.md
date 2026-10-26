---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/
---
## ChartData 클래스

차트 플로팅에 사용되는 데이터를 나타냅니다.

ChartData 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ko/aspose.slides.charts/chartdata/chart_data_workbook/) | 차트 시리즈 또는 범주에 사용되는 셀을 만들기 위한 셀 팩토리를 가져옵니다.<br/>            읽기 전용 [`IChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ko/aspose.slides.charts/chartdata/series/) | 시리즈를 가져옵니다.<br/>            읽기 전용 [`IChartSeriesCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ko/aspose.slides.charts/chartdata/series_groups/) | 시리즈 그룹을 가져옵니다.<br/>            읽기 전용 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories/) | 기본 범주를 가져옵니다 (또는 [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) 속성이 false인 경우 기본 및 보조 범주 모두).<br/>            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories/) | false이면 [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) 속성이 None을 반환하고 [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다.<br/>            true이면 [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) 속성의 데이터가 보조 시리즈에 사용되고 [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) 속성의 데이터가 기본 시리즈에 사용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories/) | [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) 속성이 true인 경우 보조 범주를 가져옵니다.<br/>            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ko/aspose.slides.charts/chartdata/data_source_type/) | 외부 데이터 소스인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 None을 나타냅니다 |
| [`external_workbook_path`](/slides/python-net/ko/aspose.slides.charts/chartdata/external_workbook_path/) | 차트의 데이터 소스를 나타냅니다 |
| [`embedded_workbook_type`](/slides/python-net/ko/aspose.slides.charts/chartdata/embedded_workbook_type/) | 내장 워크북의 유형을 가져옵니다.<br/>            [`ChartData.data_source_type`](/slides/python-net/ko/aspose.slides.charts/chartdata/data_source_type)가 [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ko/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK)인 경우 [`WorkbookType.NOT_DEFINED`](/slides/python-net/ko/aspose.slides.charts/workbooktype/NOT_DEFINED)를 반환합니다.<br/>            읽기 전용 [`WorkbookType`](/slides/python-net/ko/aspose.slides.charts/workbooktype). |

## 메서드

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ko/aspose.slides.charts/chartdata/set_external_workbook/#str) | 외부 워크북을 차트의 데이터 소스로 설정합니다. 차트 데이터는 대상 워크북에서 업데이트됩니다. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ko/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | 외부 워크북을 차트의 데이터 소스로 설정합니다. |
| [`read_workbook_stream(self)`](/slides/python-net/ko/aspose.slides.charts/chartdata/read_workbook_stream/#) | 내부에 포함된 Excel 워크북을 스트림으로 씁니다. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ko/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | 사용자 지정 값으로 내부에 포함된 Excel 워크북을 초기화합니다. |
| [`get_range(self)`](/slides/python-net/ko/aspose.slides.charts/chartdata/get_range/#) | 차트 데이터 범위를 가져옵니다. |
| [`set_range(self, formula)`](/slides/python-net/ko/aspose.slides.charts/chartdata/set_range/#str) | 차트 데이터 범위를 설정합니다. 새로운 데이터 범위에 따라 시리즈와 범주가 업데이트됩니다.<br/>            데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다. |
| [`switch_row_column(self)`](/slides/python-net/ko/aspose.slides.charts/chartdata/switch_row_column/#) | 축을 따라 데이터를 교환합니다.<br/>            X축에 차트된 데이터가 Y축으로 이동하고 그 반대도 마찬가지입니다. |


### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)