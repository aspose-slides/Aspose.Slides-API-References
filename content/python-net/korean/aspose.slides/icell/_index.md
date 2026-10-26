---
title: ICell class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icell/
---
## ICell 클래스

테이블에서 셀을 나타냅니다.

ICell 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/ko/aspose.slides/icell/offset_x/) | 테이블의 왼쪽 측면에서 셀의 왼쪽 측면까지의 거리를 반환합니다.<br/>            읽기 전용 **float**. |
| [`offset_y`](/slides/python-net/ko/aspose.slides/icell/offset_y/) | 테이블의 위쪽 측면에서 셀의 위쪽 측면까지의 거리를 반환합니다.<br/>            읽기 전용 **float**. |
| [`first_row_index`](/slides/python-net/ko/aspose.slides/icell/first_row_index/) | 셀에 의해 커버되는 첫 번째 행의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`first_column_index`](/slides/python-net/ko/aspose.slides/icell/first_column_index/) | 셀에 의해 커버되는 첫 번째 열의 인덱스를 반환합니다.<br/>            읽기 전용 **int**. |
| [`width`](/slides/python-net/ko/aspose.slides/icell/width/) | 셀의 너비를 반환합니다.<br/>            읽기 전용 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/icell/height/) | 셀의 높이를 반환합니다.<br/>            읽기 전용 **float**. |
| [`minimal_height`](/slides/python-net/ko/aspose.slides/icell/minimal_height/) | 셀의 최소 높이를 반환합니다.<br/>            이는 셀이 커버하는 모든 행의 최소 높이의 합계입니다.<br/>            읽기 전용 **float**. |
| [`margin_left`](/slides/python-net/ko/aspose.slides/icell/margin_left/) | TextFrame에서 왼쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_right`](/slides/python-net/ko/aspose.slides/icell/margin_right/) | TextFrame에서 오른쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_top`](/slides/python-net/ko/aspose.slides/icell/margin_top/) | TextFrame에서 위쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_bottom`](/slides/python-net/ko/aspose.slides/icell/margin_bottom/) | TextFrame에서 아래쪽 여백을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`text_vertical_type`](/slides/python-net/ko/aspose.slides/icell/text_vertical_type/) | 수직 텍스트의 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextVerticalType`](/slides/python-net/ko/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ko/aspose.slides/icell/text_anchor_type/) | 텍스트 앵커 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAnchorType`](/slides/python-net/ko/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ko/aspose.slides/icell/anchor_center/) | 텍스트 상자가 셀 안에서 가운데 정렬되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`first_column`](/slides/python-net/ko/aspose.slides/icell/first_column/) | 셀의 첫 번째 열을 가져옵니다.<br/>            읽기 전용 [`IColumn`](/slides/python-net/ko/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/ko/aspose.slides/icell/first_row/) | 셀의 첫 번째 행을 가져옵니다.<br/>            읽기 전용 [`IRow`](/slides/python-net/ko/aspose.slides/irow). |
| [`col_span`](/slides/python-net/ko/aspose.slides/icell/col_span/) | 현재 셀이 차지해야 하는 상위 테이블의 테이블 그리드에서 그리드 열 수를 반환합니다.<br/>            이 속성을 사용하면 셀이 테이블의 다른 셀의 수직 경계를 넘쳐서 병합된 것처럼 보이게 할 수 있습니다.<br/>            읽기 전용 **int**. |
| [`row_span`](/slides/python-net/ko/aspose.slides/icell/row_span/) | 병합된 셀이 차지하는 행 수를 반환합니다. 이는 다른 셀의 vMerge 속성과 함께 사용되어 가로 병합의 시작 셀을 지정합니다.<br/>            읽기 전용 **int**. |
| [`text_frame`](/slides/python-net/ko/aspose.slides/icell/text_frame/) | 셀의 텍스트 프레임을 반환합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ko/aspose.slides/icell/table/) | 셀에 대한 상위 Table 객체를 반환합니다.<br/>            읽기 전용 [`ITable`](/slides/python-net/ko/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ko/aspose.slides/icell/is_merged_cell/) | 셀의 병합 여부를 반환합니다. 병합된 셀이 있으면 true, 그렇지 않으면 false를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`cell_format`](/slides/python-net/ko/aspose.slides/icell/cell_format/) | 이 셀에 대한 서식 속성을 포함하는 CellFormat 객체를 반환합니다.<br/>            읽기 전용 [`ICellFormat`](/slides/python-net/ko/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ko/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/icell/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ko/aspose.slides/icell/split_by_col_span/#int) | 열 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [`split_by_row_span(self, index)`](/slides/python-net/ko/aspose.slides/icell/split_by_row_span/#int) | 행 인덱스를 기준으로 셀을 두 개의 셀로 분할합니다. |
| [`split_by_height(self, height)`](/slides/python-net/ko/aspose.slides/icell/split_by_height/#float) | 높이 기준으로 셀을 분할합니다. |
| [`split_by_width(self, width)`](/slides/python-net/ko/aspose.slides/icell/split_by_width/#float) | 너비 기준으로 셀을 분할합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)