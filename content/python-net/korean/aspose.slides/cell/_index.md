---
title: Cell class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/cell/
---
## Cell 클래스

테이블의 셀을 나타냅니다.

Cell 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/ko/aspose.slides/cell/offset_x/) | 테이블 왼쪽 측면에서 셀 왼쪽 측면까지의 거리를 반환합니다.<br/>            읽기 전용 **float**. |
| [`offset_y`](/slides/python-net/ko/aspose.slides/cell/offset_y/) | 테이블 상단에서 셀 상단까지의 거리를 반환합니다.<br/>            읽기 전용 **float**. |
| [`first_row_index`](/slides/python-net/ko/aspose.slides/cell/first_row_index/) | 셀에 의해 커버되는 첫 번째 행의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`first_column_index`](/slides/python-net/ko/aspose.slides/cell/first_column_index/) | 셀에 의해 커버되는 첫 번째 열의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`width`](/slides/python-net/ko/aspose.slides/cell/width/) | 셀의 너비를 반환합니다.<br/>            읽기 전용 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/cell/height/) | 셀의 높이를 반환합니다.<br/>            읽기 전용 **float**. |
| [`minimal_height`](/slides/python-net/ko/aspose.slides/cell/minimal_height/) | 셀의 최소 높이를 반환합니다.<br/>            이는 셀에 의해 커버되는 모든 행의 최소 높이의 합계입니다.<br/>            읽기 전용 **float**. |
| [`margin_left`](/slides/python-net/ko/aspose.slides/cell/margin_left/) | TextFrame의 왼쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_right`](/slides/python-net/ko/aspose.slides/cell/margin_right/) | TextFrame의 오른쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_top`](/slides/python-net/ko/aspose.slides/cell/margin_top/) | TextFrame의 상단 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_bottom`](/slides/python-net/ko/aspose.slides/cell/margin_bottom/) | TextFrame의 하단 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`text_vertical_type`](/slides/python-net/ko/aspose.slides/cell/text_vertical_type/) | 수직 텍스트 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextVerticalType`](/slides/python-net/ko/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ko/aspose.slides/cell/text_anchor_type/) | 텍스트 앵커 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAnchorType`](/slides/python-net/ko/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ko/aspose.slides/cell/anchor_center/) | 텍스트 상자가 셀 내부에 가운데 정렬되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`first_row`](/slides/python-net/ko/aspose.slides/cell/first_row/) | 셀의 첫 번째 행을 가져옵니다.<br/>            읽기 전용 [`IRow`](/slides/python-net/ko/aspose.slides/irow). |
| [`first_column`](/slides/python-net/ko/aspose.slides/cell/first_column/) | 셀의 첫 번째 열을 가져옵니다.<br/>            읽기 전용 [`IColumn`](/slides/python-net/ko/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/ko/aspose.slides/cell/col_span/) | 현재 셀이 차지할 상위 테이블의 표 그리드에서 그리드 열 수를 반환합니다.<br/>            이 속성은 셀이 테이블의 다른 셀들의 수직 경계에 걸쳐 병합된 것처럼 보이게 합니다.<br/>            읽기 전용 **int**. |
| [`row_span`](/slides/python-net/ko/aspose.slides/cell/row_span/) | 병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 결합하여 수평 병합의 시작 셀을 지정하는 데 사용됩니다.<br/>            읽기 전용 **int**. |
| [`text_frame`](/slides/python-net/ko/aspose.slides/cell/text_frame/) | 셀의 텍스트 프레임을 반환합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ko/aspose.slides/cell/table/) | 셀의 상위 Table 객체를 반환합니다.<br/>            읽기 전용 [`ITable`](/slides/python-net/ko/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ko/aspose.slides/cell/is_merged_cell/) | 셀이 조정된 셀과 병합했을 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`cell_format`](/slides/python-net/ko/aspose.slides/cell/cell_format/) | 이 셀에 대한 서식 속성을 포함하는 CellFormat 객체를 반환합니다.<br/>            읽기 전용 [`ICellFormat`](/slides/python-net/ko/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ko/aspose.slides/cell/slide/) | 셀의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides/cell/presentation/) | 셀의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |

## 메서드

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ko/aspose.slides/cell/split_by_col_span/#int) | 열 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [`split_by_row_span(self, index)`](/slides/python-net/ko/aspose.slides/cell/split_by_row_span/#int) | 행 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [`split_by_height(self, height)`](/slides/python-net/ko/aspose.slides/cell/split_by_height/#float) | 셀을 높이 기준으로 분할합니다. |
| [`split_by_width(self, width)`](/slides/python-net/ko/aspose.slides/cell/split_by_width/#float) | 셀을 너비 기준으로 분할합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)