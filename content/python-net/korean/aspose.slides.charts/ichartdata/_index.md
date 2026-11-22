---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/
---
## IChartData 클래스

차트 플로팅에 사용되는 데이터를 나타냅니다.

IChartData 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ko/aspose.slides.charts/ichartdata/chart_data_workbook/) | 차트 시리즈 또는 카테고리에 사용되는 셀을 생성하는 셀 팩토리를 가져옵니다.<br/>읽기 전용 [`IChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ko/aspose.slides.charts/ichartdata/series/) | 시리즈를 가져옵니다.<br/>읽기 전용 [`IChartSeriesCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ko/aspose.slides.charts/ichartdata/series_groups/) | 시리즈 그룹을 가져옵니다.<br/>읽기 전용 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories/) | 주 카테고리를 가져옵니다(또는 [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 false인 경우 주 및 보조 카테고리를 모두 가져옵니다).<br/>읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories/) | false이면 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 속성이 None을 반환하고 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터가 주 및 보조 시리즈 모두에 사용됩니다.<br/>true이면 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 속성의 데이터가 보조 시리즈에 사용되고 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터가 주 시리즈에 사용됩니다.<br/>읽기/쓰기 **bool**. |
| [`secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories/) | [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 true이면 보조 카테고리를 가져옵니다.<br/>읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ko/aspose.slides.charts/ichartdata/data_source_type/) | 차트의 데이터 소스를 나타냅니다 |
| [`external_workbook_path`](/slides/python-net/ko/aspose.slides.charts/ichartdata/external_workbook_path/) | 데이터 소스가 외부인 경우 외부 워크북 경로를 나타내며, 그렇지 않으면 None을 반환합니다 |
| [`embedded_workbook_type`](/slides/python-net/ko/aspose.slides.charts/ichartdata/embedded_workbook_type/) | 내장 워크북의 유형을 가져옵니다.<br/>[`IChartData.data_source_type`](/slides/python-net/ko/aspose.slides.charts/ichartdata/data_source_type)가 [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ko/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK)인 경우 [`WorkbookType.NOT_DEFINED`](/slides/python-net/ko/aspose.slides.charts/workbooktype/NOT_DEFINED)를 반환합니다.<br/>읽기 전용 [`WorkbookType`](/slides/python-net/ko/aspose.slides.charts/workbooktype). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/set_external_workbook/#str) | 외부 워크북을 차트의 데이터 소스로 설정합니다. 차트 데이터가 대상 워크북에서 업데이트됩니다. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | 외부 워크북을 차트의 데이터 소스로 설정합니다. |
| [`read_workbook_stream(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/read_workbook_stream/#) | 내부에 포함된 Excel 워크북을 메모리 스트림에 기록합니다. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | 사용자 지정 값으로 내부에 포함된 Excel 워크북을 초기화합니다. |
| [`set_range(self, formula)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/set_range/#str) | 차트 데이터 범위를 설정합니다. 새로운 데이터 범위에 따라 시리즈와 카테고리가 업데이트됩니다.<br/>데이터 범위의 시리즈 수가 차트 데이터의 시리즈 수보다 많으면 현재 컬렉션의 마지막 시리즈와 동일한 유형의 추가 시리즈가 컬렉션 끝에 추가됩니다. |
| [`get_range(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/get_range/#) | 차트 데이터 범위를 가져옵니다. |
| [`switch_row_column(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/switch_row_column/#) | 축을 따라 데이터를 교환합니다.<br/>X 축에 차트된 데이터가 Y 축으로 이동하고 그 반대도 마찬가지입니다. |
| [`refresh_data(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdata/refresh_data/#) | 소스 워크북에서 다시 로드하여 차트 데이터를 새로 고칩니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)