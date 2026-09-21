---
title: Axis class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/axis/
---
## คลาส Axis

ห่อหุ้มอ็อบเจ็กต์ที่แสดงแกนของแผนภูมิ

The Axis type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/th/aspose.slides.charts/axis/chart/) | ส่งคืนแผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/th/aspose.slides.charts/axis/axis_between_categories/) | ระบุว่ามีการข้ามแกนค่ากับแกนประเภทระหว่างประเภทหรือไม่.<br/>             คุณสมบัตินี้ใช้ได้เฉพาะแกนประเภทเท่านั้น และไม่ใช้กับแผนภูมิ 3-D.<br/>             อ่าน/เขียน **bool**. |
| [`category_axis_type`](/slides/python-net/th/aspose.slides.charts/axis/category_axis_type/) | ระบุประเภทของแกนประเภท.<br/>            อ่าน/เขียน [`CategoryAxisType`](/slides/python-net/th/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/th/aspose.slides.charts/axis/cross_at/) | แสดงตำแหน่งบนแกนที่แกนตั้งฉากข้ามผ่าน.<br/>             อ่าน/เขียน **float**. |
| [`display_unit`](/slides/python-net/th/aspose.slides.charts/axis/display_unit/) | ระบุค่าการสเกลของหน่วยแสดงผลสำหรับแกนค่า.<br/>             อ่าน/เขียน [`DisplayUnitType`](/slides/python-net/th/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/th/aspose.slides.charts/axis/actual_max_value/) | ระบุค่ามากที่สุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`actual_min_value`](/slides/python-net/th/aspose.slides.charts/axis/actual_min_value/) | ระบุค่าที่น้อยที่สุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`actual_major_unit`](/slides/python-net/th/aspose.slides.charts/axis/actual_major_unit/) | ระบุหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`actual_minor_unit`](/slides/python-net/th/aspose.slides.charts/axis/actual_minor_unit/) | ระบุหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`actual_major_unit_scale`](/slides/python-net/th/aspose.slides.charts/axis/actual_major_unit_scale/) | ระบุสเกลหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`actual_minor_unit_scale`](/slides/python-net/th/aspose.slides.charts/axis/actual_minor_unit_scale/) | ระบุสเกลหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง. |
| [`is_automatic_max_value`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_max_value/) | ระบุว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`max_value`](/slides/python-net/th/aspose.slides.charts/axis/max_value/) | แสดงค่ามากสุดบนแกนค่า.<br/>             อ่าน/เขียน **float**. |
| [`minor_unit`](/slides/python-net/th/aspose.slides.charts/axis/minor_unit/) | แสดงหน่วยย่อยสำหรับแกนวันที่หรือค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_minor_unit/) | ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`major_unit`](/slides/python-net/th/aspose.slides.charts/axis/major_unit/) | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_automatic_major_unit`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_major_unit/) | ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`is_automatic_min_value`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_min_value/) | ระบุว่าค่าน้อยสุดถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`min_value`](/slides/python-net/th/aspose.slides.charts/axis/min_value/) | แสดงค่าต่ำสุดบนแกนค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_logarithmic`](/slides/python-net/th/aspose.slides.charts/axis/is_logarithmic/) | แสดงว่าแบบสเกลของแกนค่าคือเชิงลอการิทึมหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`log_base`](/slides/python-net/th/aspose.slides.charts/axis/log_base/) | แสดงฐานเชิงลอการิทึม. ค่าปริยายคือ 10.<br/>             อ่าน/เขียน **float**. |
| [`is_plot_order_reversed`](/slides/python-net/th/aspose.slides.charts/axis/is_plot_order_reversed/) | แสดงว่าซอฟต์แวร์ MS PowerPoint วาดจุดข้อมูลจากท้ายไปหน้าแรกหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/axis/is_visible/) | แสดงว่าแกนมองเห็นได้หรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`major_tick_mark`](/slides/python-net/th/aspose.slides.charts/axis/major_tick_mark/) | แสดงประเภทของเครื่องหมายหลักสำหรับแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickMarkType`](/slides/python-net/th/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/th/aspose.slides.charts/axis/minor_tick_mark/) | แสดงประเภทของเครื่องหมายย่อยสำหรับแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickMarkType`](/slides/python-net/th/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/th/aspose.slides.charts/axis/tick_label_position/) | แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickLabelPositionType`](/slides/python-net/th/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/th/aspose.slides.charts/axis/major_unit_scale/) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่.<br/>             อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/th/aspose.slides.charts/axis/minor_unit_scale/) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่.<br/>             อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/th/aspose.slides.charts/axis/base_unit_scale/) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่.<br/>            อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/th/aspose.slides.charts/axis/minor_grid_lines_format/) | แสดงรูปแบบของเส้นกริดย่อยบนแกนแผนภูมิ.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/th/aspose.slides.charts/axis/major_grid_lines_format/) | แสดงรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/th/aspose.slides.charts/axis/show_minor_grid_lines/) | เพื่อซ่อนเส้นกริดย่อย ให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill.<br/>            อ่านอย่างเดียว **bool**. |
| [`show_major_grid_lines`](/slides/python-net/th/aspose.slides.charts/axis/show_major_grid_lines/) | เพื่อซ่อนเส้นกริดหลัก ให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill.<br/>            อ่านอย่างเดียว **bool**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/axis/format/) | แสดงรูปแบบของแกน.<br/>             อ่านอย่างเดียว [`IAxisFormat`](/slides/python-net/th/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/axis/text_format/) | แสดงรูปแบบของข้อความ.<br/>             อ่านอย่างเดียว [`IChartTextFormat`](/slides/python-net/th/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/th/aspose.slides.charts/axis/title/) | รับหัวข้อของแกน.<br/>             อ่านอย่างเดียว [`IChartTitle`](/slides/python-net/th/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/th/aspose.slides.charts/axis/cross_type/) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้ามผ่าน.<br/>             อ่าน/เขียน [`CrossesType`](/slides/python-net/th/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/th/aspose.slides.charts/axis/position/) | แสดงตำแหน่งของแกน.<br/>             อ่าน/เขียน [`AxisPositionType`](/slides/python-net/th/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/th/aspose.slides.charts/axis/has_title/) | กำหนดว่าแกนมีหัวข้อที่มองเห็นได้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`number_format`](/slides/python-net/th/aspose.slides.charts/axis/number_format/) | แสดงสตริงฟอร์แมตสำหรับป้ายแกน.<br/>            อ่าน/เขียน **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/th/aspose.slides.charts/axis/is_number_format_linked_to_source/) | ระบุว่าฟอร์แมตเชื่อมโยงกับข้อมูลต้นทางหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/th/aspose.slides.charts/axis/tick_label_rotation_angle/) | แสดงมุมการหมุนของป้ายเครื่องหมาย.<br/>            อ่าน/เขียน **float**. |
| [`tick_label_spacing`](/slides/python-net/th/aspose.slides.charts/axis/tick_label_spacing/) | ระบุจำนวนป้ายเครื่องหมายที่ข้ามระหว่างป้ายที่วาด. ใช้กับแกนประเภทหรือซีรีส์.<br/>            อ่าน/เขียน **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | ระบุค่าการเว้นระยะป้ายเครื่องหมายอัตโนมัติ. ถ้า false: ใช้คุณสมบัติ TickLabelSpacing.<br/>            อ่าน/เขียน **bool**. |
| [`tick_marks_spacing`](/slides/python-net/th/aspose.slides.charts/axis/tick_marks_spacing/) | ระบุจำนวนเครื่องหมายที่ต้องข้ามก่อนที่เครื่องหมายต่อไปจะถูก<br/>            วาด. ใช้กับแกนประเภทหรือซีรีส์.<br/>            อ่าน/เขียน **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | ระบุค่าการเว้นระยะเครื่องหมายอัตโนมัติ. ถ้า false: ใช้คุณสมบัติ TickMarksSpacing.<br/>            อ่าน/เขียน **bool**. |
| [`label_offset`](/slides/python-net/th/aspose.slides.charts/axis/label_offset/) | ระบุระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%.<br/>            อ่าน/เขียน **int**. |
| [`aggregation_type`](/slides/python-net/th/aspose.slides.charts/axis/aggregation_type/) | แสดงประเภทการรวมของแกนประเภท (การจัดกลุ่ม). ใช้กับประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`bin_width`](/slides/python-net/th/aspose.slides.charts/axis/bin_width/) | ระบุความกว้างของบินเมื่อค่าคุณสมบัติ AggregationType ตั้งเป็น AxisAggregationType.ByBinWidth.<br/>            ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`number_of_bins`](/slides/python-net/th/aspose.slides.charts/axis/number_of_bins/) | ระบุจำนวนของบินเมื่อค่าคุณสมบัติ AggregationType ตั้งเป็น AxisAggregationType.ByNumberOfBins.<br/>            ใช้กับแกนประเภท. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`is_overflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/is_overflow_bin/) | ระบุว่ามีการใช้ bin เกินขนาดหรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าของ bin เกินขนาด. |
| [`is_automatic_overflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_overflow_bin/) | ระบุค่าของ bin เกินขนาดอัตโนมัติ. ถ้า false: ใช้คุณสมบัติ OverflowBin. |
| [`overflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/overflow_bin/) | ระบุค่าที่กำหนดเองของ bin เกินขนาด. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และคุณสมบัติ IsOverflowBin เท่ากับ true. |
| [`is_underflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/is_underflow_bin/) | ระบุว่ามีการใช้ bin ขาดหายหรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าของ bin ขาดหาย. |
| [`is_automatic_underflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/is_automatic_underflow_bin/) | ระบุค่าของ bin ขาดหายอัตโนมัติ. ถ้า false: ใช้คุณสมบัติ UnderflowBin. |
| [`underflow_bin`](/slides/python-net/th/aspose.slides.charts/axis/underflow_bin/) | ระบุค่าที่กำหนดเองของ bin ขาดหาย. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และคุณสมบัติ IsUnderflowBin เท่ากับ true. |
| [`slide`](/slides/python-net/th/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/axis/presentation/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/th/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลของแกน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)