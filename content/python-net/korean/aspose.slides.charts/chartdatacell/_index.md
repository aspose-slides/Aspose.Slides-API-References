---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartdatacell/
---
## ChartDataCell 클래스

차트 데이터에 대한 셀을 나타냅니다.

ChartDataCell 유형은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/row/) | 셀이 위치한 워크시트 행의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`column`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/column/) | 셀이 위치한 워크시트 열의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`value`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/value/) | 셀의 값을 가져오거나 설정합니다.<br/>            읽기/쓰기 **any**. |
| [`formula`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/formula/) | A1 스타일의 수식을 가져오거나 설정합니다. |
| [`r1c1_formula`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/r1c1_formula/) | R1C1 스타일의 수식을 가져오거나 설정합니다. |
| [`chart_data_worksheet`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | 워크시트를 가져옵니다.<br/>            읽기 전용 [`IChartDataWorksheet`](/slides/python-net/ko/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/is_hidden/) | 셀이 숨겨져 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`custom_number_format`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/custom_number_format/) | 숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다.<br/>            값이 비어 있으면 PresetNumberFormat 값이 사용됩니다.<br/>            읽기/쓰기 **str**. |
| [`preset_number_format`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/preset_number_format/) | 숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. 프리셋 번호는 [0..22] 또는 [37..49] 범위에 있어야 합니다.<br/>            읽기/쓰기 **int**. |

## 메서드

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/ko/aspose.slides.charts/chartdatacell/calculate/#bool) | 셀에 수식이 포함되어 있으면 해당 수식을 기반으로 값이 업데이트됩니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)