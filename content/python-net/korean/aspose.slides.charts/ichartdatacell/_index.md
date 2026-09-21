---
title: IChartDataCell class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell 클래스

차트 데이터용 셀을 나타냅니다.

IChartDataCell 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`row`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/row/) | 셀의 위치를 포함하는 워크시트 행의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`column`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/column/) | 셀의 위치를 포함하는 워크시트 열의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`value`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/value/) | 셀의 값을 가져오거나 설정합니다.<br/>            읽기/쓰기 **any**. |
| [`formula`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/formula/) | A1 스타일의 수식을 가져오거나 설정합니다. |
| [`r1c1_formula`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/r1c1_formula/) | R1C1 스타일의 수식을 가져오거나 설정합니다. |
| [`chart_data_worksheet`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | 워크시트를 가져옵니다.<br/>            읽기 전용 [`IChartDataWorksheet`](/slides/python-net/ko/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/is_hidden/) | 셀의 숨김 여부를 확인합니다.<br/>            읽기 전용 **bool**. |
| [`custom_number_format`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/custom_number_format/) | 숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다. <br/>            값이 비어 있으면 PresetNumberFormat 값을 사용합니다.<br/>            읽기/쓰기 **str**. |
| [`preset_number_format`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/preset_number_format/) | 숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. 사전 설정 번호는 [0..22] 또는 [37..49] 범위여야 합니다.<br/>            읽기/쓰기 **int**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell/calculate/#bool) | 셀에 수식이 포함된 경우 해당 수식을 기반으로 값이 업데이트됩니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)