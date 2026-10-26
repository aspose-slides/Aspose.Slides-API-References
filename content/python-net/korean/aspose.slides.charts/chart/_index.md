---
title: Chart class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chart/
---
## Chart 클래스

슬라이드에 그래픽 차트를 나타냅니다.

**Inheritance:**[`Chart`](/slides/python-net/ko/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ko/aspose.slides/shape)

The Chart type exposes the following members:

## 속성

| Property | 설명 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ko/aspose.slides.charts/chart/is_text_holder/) | shape가 TextHolder_PPT인지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`placeholder`](/slides/python-net/ko/aspose.slides.charts/chart/placeholder/) | shape의 플레이스홀더를 반환합니다. shape에 플레이스홀더가 없으면 None을 반환합니다.<br/>            읽기 전용 [`IPlaceholder`](/slides/python-net/ko/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ko/aspose.slides.charts/chart/custom_data/) | shape의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ko/aspose.slides.charts/chart/raw_frame/) | 원시 shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ko/aspose.slides.charts/chart/frame/) | shape 프레임의 속성을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ko/aspose.slides.charts/chart/line_format/) | shape의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다.<br/>            참고: 선 속성이 없는 특정 유형의 shape에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ko/aspose.slides.charts/chart/three_d_format/) | shape의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다.<br/>            참고: 3D 속성이 없는 특정 유형의 shape에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides.charts/chart/effect_format/) | shape에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다.<br/>            참고: 효과 속성이 없는 특정 유형의 shape에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides.charts/chart/fill_format/) | shape의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다.<br/>            참고: 채우기 속성이 없는 특정 유형의 shape에 대해서는 None을 반환할 수 있습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ko/aspose.slides.charts/chart/hyperlink_click/) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ko/aspose.slides.charts/chart/hyperlink_mouse_over/) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHyperlink`](/slides/python-net/ko/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ko/aspose.slides.charts/chart/hyperlink_manager/) | 하이퍼링크 관리자를 반환합니다.<br/>            읽기 전용 [`IHyperlinkManager`](/slides/python-net/ko/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ko/aspose.slides.charts/chart/hidden/) | shape가 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`z_order_position`](/slides/python-net/ko/aspose.slides.charts/chart/z_order_position/) | z-순서에서 shape의 위치를 반환합니다.<br/>            Shapes[0]은 z-순서 뒤쪽에 있는 shape를 반환하고,<br/>            Shapes[Shapes.Count - 1]은 앞쪽에 있는 shape를 반환합니다.<br/>            읽기 전용 **int**. |
| [`connection_site_count`](/slides/python-net/ko/aspose.slides.charts/chart/connection_site_count/) | shape의 연결 지점 수를 반환합니다.<br/>            읽기 전용 **int**. |
| [`rotation`](/slides/python-net/ko/aspose.slides.charts/chart/rotation/) | 지정된 shape가 z축을 중심으로 회전된 각도를 반환하거나 설정합니다.<br/>            양수 값은 시계 방향 회전을 의미하고, 음수 값은 반시계 방향 회전을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`x`](/slides/python-net/ko/aspose.slides.charts/chart/x/) | shape의 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides.charts/chart/y/) | shape의 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides.charts/chart/width/) | shape의 너비를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides.charts/chart/height/) | shape의 높이를 포인트 단위로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`black_white_mode`](/slides/python-net/ko/aspose.slides.charts/chart/black_white_mode/) | shape가 흑백 디스플레이 모드에서 렌더링되는 방식을 지정합니다.<br/>            읽기/쓰기 [`BlackWhiteMode`](/slides/python-net/ko/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ko/aspose.slides.charts/chart/unique_id/) | 애드인 또는 기타 코드에서 사용하도록 설계된 내부 프레젠테이션 범위 식별자를 반환합니다.<br/>            이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다.<br/>            읽기 전용 **int**.<br/>            참고 [`Shape.office_interop_shape_id`](/slides/python-net/ko/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ko/aspose.slides.charts/chart/office_interop_shape_id/) | shape의 수명 동안 변하지 않는 슬라이드 범위 고유 식별자를 반환하고,<br/>            PowerPoint 또는 interop 코드가 문서 어디서든 shape를 안정적으로 참조할 수 있게 합니다.<br/>            읽기 전용 **int**.<br/>            참고 [`Shape.unique_id`](/slides/python-net/ko/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ko/aspose.slides.charts/chart/alternative_text/) | shape와 연결된 대체 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_text_title`](/slides/python-net/ko/aspose.slides.charts/chart/alternative_text_title/) | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`name`](/slides/python-net/ko/aspose.slides.charts/chart/name/) | shape의 이름을 반환하거나 설정합니다.<br/>            None이 아니어야 합니다. 필요한 경우 빈 문자열을 사용하십시오.<br/>            읽기/쓰기 **str**. |
| [`is_decorative`](/slides/python-net/ko/aspose.slides.charts/chart/is_decorative/) | 'Mark as decorative' 옵션을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`shape_lock`](/slides/python-net/ko/aspose.slides.charts/chart/shape_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ko/aspose.slides.charts/chart/is_grouped/) | shape가 그룹화되어 있는지 여부를 결정합니다.<br/>            읽기 전용 **bool**. |
| [`parent_group`](/slides/python-net/ko/aspose.slides.charts/chart/parent_group/) | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 None을 반환합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/chart/slide/) | shape의 상위 슬라이드를 반환합니다.<br/>            읽기 전용 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/chart/presentation/) | 슬라이드의 상위 프레젠테이션을 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ko/aspose.slides.charts/chart/graphical_object_lock/) | shape의 잠금을 반환합니다.<br/>            읽기 전용 [`IGraphicalObjectLock`](/slides/python-net/ko/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/ko/aspose.slides.charts/chart/plot_visible_cells_only/) | 보이는 셀만 플롯될지 여부를 결정합니다. False이면 보이는 셀과 숨겨진 셀 모두를 플롯합니다.<br/>            읽기/쓰기 **bool**. |
| [`display_blanks_as`](/slides/python-net/ko/aspose.slides.charts/chart/display_blanks_as/) | 차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`DisplayBlanksAsType`](/slides/python-net/ko/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/ko/aspose.slides.charts/chart/chart_data/) | 차트와 연결되거나 포함된 데이터에 대한 정보를 반환합니다.<br/>            읽기 전용 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/ko/aspose.slides.charts/chart/has_title/) | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`chart_title`](/slides/python-net/ko/aspose.slides.charts/chart/chart_title/) | 차트 제목을 반환하거나 설정합니다.<br/>            읽기 전용 [`IChartTitle`](/slides/python-net/ko/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/ko/aspose.slides.charts/chart/has_data_table/) | 차트에 데이터 표가 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`has_legend`](/slides/python-net/ko/aspose.slides.charts/chart/has_legend/) | 차트에 범례가 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`legend`](/slides/python-net/ko/aspose.slides.charts/chart/legend/) | 차트의 범례를 반환하거나 설정합니다.<br/>            읽기 전용 [`ILegend`](/slides/python-net/ko/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/ko/aspose.slides.charts/chart/chart_data_table/) | 차트의 데이터 표를 반환합니다.<br/>            읽기 전용 [`IDataTable`](/slides/python-net/ko/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/ko/aspose.slides.charts/chart/style/) | 차트 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`StyleType`](/slides/python-net/ko/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/ko/aspose.slides.charts/chart/type/) | 차트 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/ko/aspose.slides.charts/chart/plot_area/) | 차트의 플롯 영역을 나타냅니다.<br/>            읽기 전용 [`IChartPlotArea`](/slides/python-net/ko/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/ko/aspose.slides.charts/chart/rotation_3d/) | 차트의 3D 회전을 반환합니다.<br/>            읽기 전용 [`IRotation3D`](/slides/python-net/ko/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/ko/aspose.slides.charts/chart/back_wall/) | 3D 차트의 뒤쪽 벽 서식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/ko/aspose.slides.charts/chart/side_wall/) | 3D 차트의 측면 벽 서식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/ko/aspose.slides.charts/chart/floor/) | 3D 차트의 바닥 서식을 변경할 수 있는 객체를 반환합니다.<br/>            읽기 전용 [`IChartWall`](/slides/python-net/ko/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/chart/text_format/) | 차트 텍스트 서식을 반환합니다.<br/>            이 속성은 다음 유형에서는 적용되지 않습니다: [`ChartType.TREEMAP`](/slides/python-net/ko/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/ko/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/ko/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/ko/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/ko/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/ko/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/ko/aspose.slides.charts/chart/theme_manager/) | 테마 관리자를 반환합니다.<br/>            읽기 전용 [`IOverrideThemeManager`](/slides/python-net/ko/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/ko/aspose.slides.charts/chart/user_shapes/) | 차트 위에 그려지는 shape를 지정합니다.<br/>            읽기 전용 [`IGroupShape`](/slides/python-net/ko/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/ko/aspose.slides.charts/chart/axes/) | 차트 축에 대한 접근을 제공합니다.<br/>            읽기 전용 [`IAxesManager`](/slides/python-net/ko/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/ko/aspose.slides.charts/chart/show_data_labels_over_maximum/) | 차트 최대값 위에 데이터 레이블을 표시할지 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`has_rounded_corners`](/slides/python-net/ko/aspose.slides.charts/chart/has_rounded_corners/) | 차트 영역에 둥근 모서리를 적용할지 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/chart/chart/) |   |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides.charts/chart/get_image/#) | shape 썸네일을 반환합니다.<br/>            기본적으로 ShapeThumbnailBounds.Shape shape 썸네일 경계 유형이 사용됩니다. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | shape 썸네일을 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Shape의 내용을 SVG 파일로 저장합니다. |
| [`remove_placeholder(self)`](/slides/python-net/ko/aspose.slides.charts/chart/remove_placeholder/#) | 이 shape가 플레이스홀더가 아님을 정의합니다. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ko/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | 플레이스홀더가 없는 경우 새 플레이스홀더를 추가하고 지정된 플레이스홀더 속성을 설정합니다. |
| [`get_base_placeholder(self)`](/slides/python-net/ko/aspose.slides.charts/chart/get_base_placeholder/#) | 기본 플레이스홀더 shape를 반환합니다(현재 shape가 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape).<br/>            현재 shape가 상속받지 않은 경우 None을 반환합니다. |
| [`get_visual_bounds(self)`](/slides/python-net/ko/aspose.slides.charts/chart/get_visual_bounds/#) | 렌더링된 콘텐츠로 계산된 shape의 시각적 경계를 반환합니다. |
| [`validate_chart_layout(self)`](/slides/python-net/ko/aspose.slides.charts/chart/validate_chart_layout/#) | 차트 요소의 실제 값을 계산합니다. 실제 값에는 IActualLayout 인터페이스를 구현하는 요소들의 위치<br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            및 실제 축 값(IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit,<br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)가 포함됩니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides.charts/chart/create_theme_effective/#) | 이 차트에 대한 효과적인 테마를 반환합니다. |

### 참고
* 클래스 [`Chart`](/slides/python-net/ko/aspose.slides.charts/chart)
* 클래스 [`GraphicalObject`](/slides/python-net/ko/aspose.slides/graphicalobject)
* 클래스 [`Shape`](/slides/python-net/ko/aspose.slides/shape)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)