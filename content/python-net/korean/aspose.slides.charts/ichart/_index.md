---
title: IChart class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichart/
---
## IChart 클래스

슬라이드에 있는 그래픽 차트를 나타냅니다.

IChart 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`plot_visible_cells_only`](/slides/python-net/ko/aspose.slides.charts/ichart/plot_visible_cells_only/) | 표시된 셀만 플롯할지 여부를 결정합니다. False이면 표시된 셀과 숨겨진 셀 모두를 플롯합니다.<br/>            읽기/쓰기 **bool**. |
| [`display_blanks_as`](/slides/python-net/ko/aspose.slides.charts/ichart/display_blanks_as/) | 차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`DisplayBlanksAsType`](/slides/python-net/ko/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/ko/aspose.slides.charts/ichart/chart_data/) | 차트와 연결되거나 포함된 데이터에 대한 정보를 반환합니다.<br/>            읽기 전용 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/ko/aspose.slides.charts/ichart/has_title/) | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`chart_title`](/slides/python-net/ko/aspose.slides.charts/ichart/chart_title/) | 차트 제목을 반환하거나 설정합니다<br/>            읽기 전용 [`IChartTitle`](/slides/python-net/ko/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/ko/aspose.slides.charts/ichart/has_data_table/) | 차트에 데이터 표가 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`has_legend`](/slides/python-net/ko/aspose.slides.charts/ichart/has_legend/) | 차트에 범례가 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`legend`](/slides/python-net/ko/aspose.slides.charts/ichart/legend/) | 차트에 대한 범례를 반환하거나 설정합니다.<br/>            읽기 전용 [`ILegend`](/slides/python-net/ko/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/ko/aspose.slides.charts/ichart/chart_data_table/) | 차트의 데이터 표를 반환합니다.<br/>            읽기 전용 [`IDataTable`](/slides/python-net/ko/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/ko/aspose.slides.charts/ichart/style/) | 차트 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`StyleType`](/slides/python-net/ko/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/ko/aspose.slides.charts/ichart/type/) | 차트 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/ko/aspose.slides.charts/ichart/plot_area/) | 차트의 플롯 영역을 나타냅니다.<br/>            읽기 전용 [`IChartPlotArea`](/slides/python-net/ko/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/ko/aspose.slides.charts/ichart/rotation_3d/) | 차트의 3D 회전을 반환합니다.<br/>            읽기 전용 [`IRotation3D`](/slides/python-net/ko/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/ko/aspose.slides.charts/ichart/back_wall/) | 3D 차트의 뒤쪽 벽 형식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/ko/aspose.slides.charts/ichart/side_wall/) | 3D 차트의 측면 벽 형식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/ko/aspose.slides.charts/ichart/floor/) | 3D 차트의 바닥 형식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`user_shapes`](/slides/python-net/ko/aspose.slides.charts/ichart/user_shapes/) | 차트 위에 그려지는 모양을 지정합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/ko/aspose.slides.charts/ichart/axes/) | 차트 축에 대한 접근을 제공합니다.<br/>            읽기 전용 [`IAxesManager`](/slides/python-net/ko/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/ko/aspose.slides.charts/ichart/show_data_labels_over_maximum/) | 차트의 최대값 위에 데이터 레이블을 표시할지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`has_rounded_corners`](/slides/python-net/ko/aspose.slides.charts/ichart/has_rounded_corners/) | 차트 영역에 둥근 모서리를 적용할지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides.charts/ichart/shape_lock/) |  |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides.charts/ichart/graphical_object_lock/) |  |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides.charts/ichart/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/ko/aspose.slides.charts/ichart/placeholder/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides.charts/ichart/custom_data/) |  |
| [`raw_frame`](/slides/python-net/ko/aspose.slides.charts/ichart/raw_frame/) |  |
| [`frame`](/slides/python-net/ko/aspose.slides.charts/ichart/frame/) |  |
| [`line_format`](/slides/python-net/ko/aspose.slides.charts/ichart/line_format/) |  |
| [`three_d_format`](/slides/python-net/ko/aspose.slides.charts/ichart/three_d_format/) |  |
| [`effect_format`](/slides/python-net/ko/aspose.slides.charts/ichart/effect_format/) |  |
| [`fill_format`](/slides/python-net/ko/aspose.slides.charts/ichart/fill_format/) |  |
| [`hidden`](/slides/python-net/ko/aspose.slides.charts/ichart/hidden/) |  |
| [`z_order_position`](/slides/python-net/ko/aspose.slides.charts/ichart/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides.charts/ichart/connection_site_count/) |  |
| [`rotation`](/slides/python-net/ko/aspose.slides.charts/ichart/rotation/) |  |
| [`x`](/slides/python-net/ko/aspose.slides.charts/ichart/x/) |  |
| [`y`](/slides/python-net/ko/aspose.slides.charts/ichart/y/) |  |
| [`width`](/slides/python-net/ko/aspose.slides.charts/ichart/width/) |  |
| [`height`](/slides/python-net/ko/aspose.slides.charts/ichart/height/) |  |
| [`alternative_text`](/slides/python-net/ko/aspose.slides.charts/ichart/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides.charts/ichart/alternative_text_title/) |  |
| [`name`](/slides/python-net/ko/aspose.slides.charts/ichart/name/) |  |
| [`is_decorative`](/slides/python-net/ko/aspose.slides.charts/ichart/is_decorative/) |  |
| [`unique_id`](/slides/python-net/ko/aspose.slides.charts/ichart/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides.charts/ichart/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/ko/aspose.slides.charts/ichart/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides.charts/ichart/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/ko/aspose.slides.charts/ichart/parent_group/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/ichart/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/ichart/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides.charts/ichart/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides.charts/ichart/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides.charts/ichart/hyperlink_manager/) |  |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/ichart/text_format/) |  |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/ichart/chart/) |  |
| [`theme_manager`](/slides/python-net/ko/aspose.slides.charts/ichart/theme_manager/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides.charts/ichart/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides.charts/ichart/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides.charts/ichart/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides.charts/ichart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`validate_chart_layout(self)`](/slides/python-net/ko/aspose.slides.charts/ichart/validate_chart_layout/#) | 차트 요소의 실제 값을 계산합니다. 실제 값에는 IActualLayout 인터페이스를 구현하는 요소의 위치(IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)와 실제 축 값(IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)가 포함됩니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides.charts/ichart/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides.charts/ichart/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides.charts/ichart/get_base_placeholder/#) |  |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides.charts/ichart/create_theme_effective/#) |  |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)