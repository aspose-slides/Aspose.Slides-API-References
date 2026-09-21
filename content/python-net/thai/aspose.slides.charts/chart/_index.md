---
title: Chart class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chart/
---
## คลาส Chart

แทน chart กราฟิกบนสไลด์.

**การสืบทอด:**[`Chart`](/slides/python-net/th/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท Chart แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.charts/chart/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides.charts/chart/placeholder/) | ส่งคืน placeholder สำหรับ shape. ส่งคืน None หาก shape ไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides.charts/chart/custom_data/) | ส่งคืนข้อมูลที่กำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides.charts/chart/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของกรอบ shape ดิบ.<br/>            อ่านเขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides.charts/chart/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของกรอบ shape.<br/>            อ่านเขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides.charts/chart/line_format/) | ส่งคืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides.charts/chart/three_d_format/) | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติของเอฟเฟกต์ 3d สำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides.charts/chart/effect_format/) | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติของเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides.charts/chart/fill_format/) | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.charts/chart/hyperlink_click/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่านเขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.charts/chart/hyperlink_mouse_over/) | ส่งคืนหรือกำหนด hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์ไว้เหนือ.<br/>            อ่านเขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.charts/chart/hyperlink_manager/) | ส่งคืนผู้จัดการ hyperlink.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides.charts/chart/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่านเขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides.charts/chart/z_order_position/) | ส่งคืนตำแหน่งของ shape ในลำดับ z-order.<br/>            Shapes[0] ส่งคืน shape ที่อยู่ด้านหลังสุดของ z-order,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่อยู่ด้านหน้าสุดของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.charts/chart/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides.charts/chart/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าเป็นบวกบ่งชี้การหมุนตามเข็มนาฬิกา; ค่าเป็นลบบ่งชี้การหมุนทวนเข็มนาฬิกา.<br/>            อ่านเขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides.charts/chart/x/) | รับหรือกำหนดค่าพิกัด x ของมุมบนซ้ายของ shape, หน่วยเป็น points.<br/>            อ่านเขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides.charts/chart/y/) | รับหรือกำหนดค่าพิกัด y ของมุมบนซ้ายของ shape, หน่วยเป็น points.<br/>            อ่านเขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides.charts/chart/width/) | รับหรือกำหนดความกว้างของ shape, หน่วยเป็น points.<br/>            อ่านเขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides.charts/chart/height/) | รับหรือกำหนดความสูงของ shape, หน่วยเป็น points.<br/>            อ่านเขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.charts/chart/black_white_mode/) | คุณสมบัติระบุว่า shape จะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร.<br/>            อ่านเขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides.charts/chart/unique_id/) | ส่งคืนตัวระบุภายในที่มีขอบเขตของงานนำเสนอเพื่อใช้โดย add-in หรือโค้ดอื่น.<br/>            เนื่องจากค่านี้สามารถเปลี่ยนค่าได้โดยผู้ใช้หรือโปรแกรม, ไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.charts/chart/office_interop_shape_id/) | ส่งคืนตัวระบุที่มีขอบเขตของสไลด์และเป็นเอกลักษณ์ซึ่งคงที่ตลอดอายุของ shape และ<br/>            ให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้อย่างเชื่อถือจากทุกส่วนของเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides.charts/chart/alternative_text/) | ส่งคืนหรือกำหนดข้อความสำรองที่เกี่ยวข้องกับ shape.<br/>            อ่านเขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.charts/chart/alternative_text_title/) | ส่งคืนหรือกำหนดหัวข้อของข้อความสำรองที่เกี่ยวข้องกับ shape.<br/>            อ่านเขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides.charts/chart/name/) | ส่งคืนหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าสตริงว่างหากต้องการ.<br/>            อ่านเขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides.charts/chart/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่านเขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.charts/chart/shape_lock/) | ส่งคืน locks ของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides.charts/chart/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides.charts/chart/parent_group/) | ส่งคืนอ็อบเจ็กต์ GroupShape พาเรนต์ถ้า shape ถูกจัดกลุ่ม. มิฉะนั้นส่งคืน None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides.charts/chart/slide/) | ส่งคืนสไลด์พาเรนต์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/chart/presentation/) | ส่งคืนงานนำเสนอพาเรนต์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides.charts/chart/graphical_object_lock/) | ส่งคืน locks ของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/th/aspose.slides.charts/chart/plot_visible_cells_only/) | กำหนดว่าจะพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่. ค่าผิดหมายถึงพล็อตทั้งเซลล์ที่มองเห็นและที่ซ่อน.<br/>            อ่านเขียน **bool**. |
| [`display_blanks_as`](/slides/python-net/th/aspose.slides.charts/chart/display_blanks_as/) | ส่งคืนหรือกำหนดวิธีพล็อตเซลล์ว่างใน chart.<br/>            อ่านเขียน [`DisplayBlanksAsType`](/slides/python-net/th/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/th/aspose.slides.charts/chart/chart_data/) | ส่งคืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่สัมพันธ์กับ chart.<br/>            อ่านอย่างเดียว [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/th/aspose.slides.charts/chart/has_title/) | กำหนดว่า chart มีหัวข้อที่มองเห็นหรือไม่.<br/>            อ่านเขียน **bool**. |
| [`chart_title`](/slides/python-net/th/aspose.slides.charts/chart/chart_title/) | ส่งคืนหรือกำหนดหัวข้อของ chart.<br/>            อ่านอย่างเดียว [`IChartTitle`](/slides/python-net/th/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/th/aspose.slides.charts/chart/has_data_table/) | กำหนดว่า chart มีตารางข้อมูลหรือไม่.<br/>            อ่านเขียน **bool**. |
| [`has_legend`](/slides/python-net/th/aspose.slides.charts/chart/has_legend/) | กำหนดว่า chart มี legend หรือไม่.<br/>            อ่านเขียน **bool**. |
| [`legend`](/slides/python-net/th/aspose.slides.charts/chart/legend/) | ส่งคืนหรือกำหนด legend สำหรับ chart.<br/>            อ่านอย่างเดียว [`ILegend`](/slides/python-net/th/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/th/aspose.slides.charts/chart/chart_data_table/) | ส่งคืนตารางข้อมูลของ chart.<br/>            อ่านอย่างเดียว [`IDataTable`](/slides/python-net/th/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/th/aspose.slides.charts/chart/style/) | ส่งคืนหรือกำหนดสไตล์ของ chart.<br/>            อ่านเขียน [`StyleType`](/slides/python-net/th/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/th/aspose.slides.charts/chart/type/) | ส่งคืนหรือกำหนดประเภทของ chart.<br/>            อ่านเขียน [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/th/aspose.slides.charts/chart/plot_area/) | แทนพื้นที่พล็อตของ chart.<br/>            อ่านอย่างเดียว [`IChartPlotArea`](/slides/python-net/th/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/th/aspose.slides.charts/chart/rotation_3d/) | ส่งคืนการหมุน 3D ของ chart.<br/>            อ่านอย่างเดียว [`IRotation3D`](/slides/python-net/th/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/th/aspose.slides.charts/chart/back_wall/) | ส่งคืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงหลังของ chart 3D.<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/th/aspose.slides.charts/chart/side_wall/) | ส่งคืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงข้างของ chart 3D.<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/th/aspose.slides.charts/chart/floor/) | ส่งคืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของ chart 3D.<br/>            อ่านอย่างเดียว [`IChartWall`](/slides/python-net/th/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/chart/text_format/) | ส่งคืนรูปแบบข้อความของ chart.<br/>            คุณสมบัตินี้ไม่ใช้ได้กับประเภทต่อไปนี้: [`ChartType.TREEMAP`](/slides/python-net/th/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/th/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/th/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/th/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/th/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/th/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            อ่านอย่างเดียว [`IChartTextFormat`](/slides/python-net/th/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/th/aspose.slides.charts/chart/theme_manager/) | ส่งคืนผู้จัดการธีม.<br/>            อ่านอย่างเดียว [`IOverrideThemeManager`](/slides/python-net/th/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/th/aspose.slides.charts/chart/user_shapes/) | ระบุ shape ที่วาดบนเหนือ chart.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/th/aspose.slides.charts/chart/axes/) | ให้การเข้าถึงแกนของ chart.<br/>            อ่านอย่างเดียว [`IAxesManager`](/slides/python-net/th/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/th/aspose.slides.charts/chart/show_data_labels_over_maximum/) | กำหนดว่าตัวเลเบลข้อมูลที่เกินค่าสูงสุดของ chart จะถูกแสดงหรือไม่.<br/>            อ่านเขียน **bool**. |
| [`has_rounded_corners`](/slides/python-net/th/aspose.slides.charts/chart/has_rounded_corners/) | กำหนดว่าพื้นที่ของ chart จะมีมุมโค้งหรือไม่.<br/>            อ่านเขียน **bool**. |
| [`chart`](/slides/python-net/th/aspose.slides.charts/chart/chart/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.charts/chart/get_image/#) | ส่งคืนรูปย่อของ shape.<br/>            ShapeThumbnailBounds.Shape ถูกใช้เป็นประเภทค่าขอบเขตรูปย่อของ shape โดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | ส่งคืนรูปย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.charts/chart/remove_placeholder/#) | กำหนดว่าตัว shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.charts/chart/get_base_placeholder/#) | ส่งคืน shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            ส่งคืน None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides.charts/chart/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`validate_chart_layout(self)`](/slides/python-net/th/aspose.slides.charts/chart/validate_chart_layout/#) | คำนวณค่าจริงขององค์ประกอบ chart. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำตามอินเทอร์เฟซ IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides.charts/chart/create_theme_effective/#) | ส่งคืนธีมที่มีผลต่อ chart นี้. |

### ดูเพิ่มเติม
* คลาส [`Chart`](/slides/python-net/th/aspose.slides.charts/chart)
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)