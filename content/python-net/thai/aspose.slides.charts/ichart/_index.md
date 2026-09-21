---
title: IChart class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichart/
---
## IChart คลาส

เป็นตัวแทนของแผนภูมิกราฟิกบนสไลด์

IChart type แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`plot_visible_cells_only`](/slides/python-net/th/aspose.slides.charts/ichart/plot_visible_cells_only/) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นได้หรือไม่ ค่าจำเป็นต้องเป็น False เพื่อแสดงทั้งเซลล์ที่มองเห็นและที่ซ่อนอยู่<br/>            อ่าน/เขียน **bool**. |
| [`display_blanks_as`](/slides/python-net/th/aspose.slides.charts/ichart/display_blanks_as/) | คืนค่า หรือกำหนดวิธีการแสดงเซลล์เปล่าในแผนภูมิ<br/>            อ่าน/เขียน [`DisplayBlanksAsType`](/slides/python-net/th/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/th/aspose.slides.charts/ichart/chart_data/) | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังไว้ที่เกี่ยวข้องกับแผนภูมิ<br/>            อ่านอย่างเดียว [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/th/aspose.slides.charts/ichart/has_title/) | กำหนดว่าแผนภูมิมีหัวข้อที่มองเห็นได้หรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`chart_title`](/slides/python-net/th/aspose.slides.charts/ichart/chart_title/) | คืนค่า หรือกำหนดหัวข้อของแผนภูมิ<br/>            อ่านอย่างเดียว [`IChartTitle`](/slides/python-net/th/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/th/aspose.slides.charts/ichart/has_data_table/) | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`has_legend`](/slides/python-net/th/aspose.slides.charts/ichart/has_legend/) | กำหนดว่าแผนภูมิมี legend หรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`legend`](/slides/python-net/th/aspose.slides.charts/ichart/legend/) | คืนค่า หรือกำหนด legend สำหรับแผนภูมิ<br/>            อ่านอย่างเดียว [`ILegend`](/slides/python-net/th/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/th/aspose.slides.charts/ichart/chart_data_table/) | คืนตารางข้อมูลของแผนภูมิ<br/>            อ่านอย่างเดียว [`IDataTable`](/slides/python-net/th/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/th/aspose.slides.charts/ichart/style/) | คืนค่า หรือกำหนดสไตล์ของแผนภูมิ<br/>            อ่าน/เขียน [`StyleType`](/slides/python-net/th/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/th/aspose.slides.charts/ichart/type/) | คืนค่า หรือกำหนดประเภทของแผนภูมิ<br/>            อ่าน/เขียน [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/th/aspose.slides.charts/ichart/plot_area/) | เป็นตัวแทนของพื้นที่พล็อตของแผนภูมิ<br/>            อ่านอย่างเดียว [`IChartPlotArea`](/slides/python-net/th/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/th/aspose.slides.charts/ichart/rotation_3d/) | คืนการหมุน 3D ของแผนภูมิ<br/>            อ่านอย่างเดียว [`IRotation3D`](/slides/python-net/th/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/th/aspose.slides.charts/ichart/back_wall/) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3D<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/th/aspose.slides.charts/ichart/side_wall/) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3D<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/th/aspose.slides.charts/ichart/floor/) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3D<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`user_shapes`](/slides/python-net/th/aspose.slides.charts/ichart/user_shapes/) | ระบุรูปทรงที่วาดบนแผนภูมิ<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/th/aspose.slides.charts/ichart/axes/) | ให้การเข้าถึงแกนของแผนภูมิ<br/>            อ่านอย่างเดียว [`IAxesManager`](/slides/python-net/th/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/th/aspose.slides.charts/ichart/show_data_labels_over_maximum/) | ระบุว่าจะต้องแสดงป้ายกำกับข้อมูลเหนือค่าสูงสุดของแผนภูมิหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`has_rounded_corners`](/slides/python-net/th/aspose.slides.charts/ichart/has_rounded_corners/) | ระบุว่าพื้นที่แผนภูมิควรมีมุมโค้ง<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.charts/ichart/shape_lock/) |  |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides.charts/ichart/graphical_object_lock/) |  |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.charts/ichart/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides.charts/ichart/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides.charts/ichart/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides.charts/ichart/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides.charts/ichart/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides.charts/ichart/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides.charts/ichart/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides.charts/ichart/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides.charts/ichart/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides.charts/ichart/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides.charts/ichart/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.charts/ichart/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides.charts/ichart/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides.charts/ichart/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides.charts/ichart/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides.charts/ichart/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides.charts/ichart/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides.charts/ichart/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.charts/ichart/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides.charts/ichart/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides.charts/ichart/is_decorative/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides.charts/ichart/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.charts/ichart/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides.charts/ichart/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.charts/ichart/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides.charts/ichart/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/ichart/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/ichart/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.charts/ichart/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.charts/ichart/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.charts/ichart/hyperlink_manager/) |  |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/ichart/text_format/) |  |
| [`chart`](/slides/python-net/th/aspose.slides.charts/ichart/chart/) |  |
| [`theme_manager`](/slides/python-net/th/aspose.slides.charts/ichart/theme_manager/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.charts/ichart/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.charts/ichart/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.charts/ichart/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.charts/ichart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`validate_chart_layout(self)`](/slides/python-net/th/aspose.slides.charts/ichart/validate_chart_layout/#) | คำนวณค่าจริงขององค์ประกอบแผนภูมิ ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำตามอินเทอร์เฟซ IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.charts/ichart/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.charts/ichart/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.charts/ichart/get_base_placeholder/#) |  |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides.charts/ichart/create_theme_effective/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)