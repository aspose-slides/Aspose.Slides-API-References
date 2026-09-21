---
title: IAxis class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/iaxis/
---
## คลาส IAxis

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/th/aspose.slides.charts/iaxis/axis_between_categories/) | บ่งบอกว่าแกนค่าตัดแกนประเภทระหว่างหมวดหมู่หรือไม่.<br/>            คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภทและไม่ใช้กับแผนภูมิ 3-D.<br/>            อ่าน/เขียน **bool**. |
| [`cross_at`](/slides/python-net/th/aspose.slides.charts/iaxis/cross_at/) | บ่งบอกจุดบนแกนที่แกนตั้งฉากตัดผ่าน.<br/>            อ่าน/เขียน **float**. |
| [`display_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/display_unit/) | ระบุค่าการสเกลของหน่วยแสดงผลสำหรับแกนค่า.<br/>            อ่าน/เขียน [`DisplayUnitType`](/slides/python-net/th/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_max_value/) | ระบุค่ามากสุดจริงบนแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`actual_min_value`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_min_value/) | ระบุค่าต่ำสุดจริงบนแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`actual_major_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_major_unit/) | ระบุหน่วยหลักจริงของแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`actual_minor_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_minor_unit/) | ระบุหน่วยย่อยจริงของแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`actual_major_unit_scale`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_major_unit_scale/) | ระบุสเกลหน่วยหลักจริงของแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`actual_minor_unit_scale`](/slides/python-net/th/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | ระบุสเกลหน่วยย่อยจริงของแกน เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้านี้เพื่อรับค่าจริง. |
| [`is_automatic_max_value`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_max_value/) | บ่งบอกว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`max_value`](/slides/python-net/th/aspose.slides.charts/iaxis/max_value/) | บ่งบอกค่ามากสุดบนแกนค่า.<br/>             อ่าน/เขียน **float**. |
| [`minor_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/minor_unit/) | บ่งบอกหน่วยย่อยสำหรับแกนวันที่หรือค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | บ่งบอกว่า หน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`major_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/major_unit/) | บ่งบอกหน่วยหลักสำหรับแกนวันที่หรือค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_automatic_major_unit`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_major_unit/) | บ่งบอกว่า หน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`is_automatic_min_value`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_min_value/) | บ่งบอกว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`min_value`](/slides/python-net/th/aspose.slides.charts/iaxis/min_value/) | บ่งบอกค่าต่ำสุดบนแกนค่า.<br/>             อ่าน/เขียน **float**. |
| [`is_logarithmic`](/slides/python-net/th/aspose.slides.charts/iaxis/is_logarithmic/) | บ่งบอกว่าแบบสเกลของแกนค่าคือลอการิทึมหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`log_base`](/slides/python-net/th/aspose.slides.charts/iaxis/log_base/) | บ่งบอกฐานลอการิทึม ค่าเริ่มต้นคือ 10.<br/>             อ่าน/เขียน **float**. |
| [`is_plot_order_reversed`](/slides/python-net/th/aspose.slides.charts/iaxis/is_plot_order_reversed/) | บ่งบอกว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/iaxis/is_visible/) | บ่งบอกว่าแกนมองเห็นได้หรือไม่.<br/>             อ่าน/เขียน **bool**. |
| [`major_tick_mark`](/slides/python-net/th/aspose.slides.charts/iaxis/major_tick_mark/) | บ่งบอกประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickMarkType`](/slides/python-net/th/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/th/aspose.slides.charts/iaxis/minor_tick_mark/) | บ่งบอกประเภทของเครื่องหมายติ๊กย่อยสำหรับแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickMarkType`](/slides/python-net/th/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/th/aspose.slides.charts/iaxis/tick_label_position/) | บ่งบอกตำแหน่งของป้ายกำกับเครื่องหมายติ๊กบนแกนที่ระบุ.<br/>             อ่าน/เขียน [`TickLabelPositionType`](/slides/python-net/th/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/th/aspose.slides.charts/iaxis/major_unit_scale/) | บ่งบอกสเกลหน่วยหลักสำหรับแกนวันที่.<br/>             อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/th/aspose.slides.charts/iaxis/minor_unit_scale/) | บ่งบอกสเกลหน่วยหลักสำหรับแกนวันที่.<br/>             อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/th/aspose.slides.charts/iaxis/base_unit_scale/) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่.<br/>            อ่าน/เขียน [`TimeUnitType`](/slides/python-net/th/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/th/aspose.slides.charts/iaxis/minor_grid_lines_format/) | บ่งบอกรูปแบบเส้นกริดย่อยบนแกนแผนภูมิ.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/th/aspose.slides.charts/iaxis/major_grid_lines_format/) | บ่งบอกรูปแบบเส้นกริดหลักบนแกนแผนภูมิ.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/th/aspose.slides.charts/iaxis/show_minor_grid_lines/) | บ่งบอกว่าเส้นกริดย่อยแสดงหรือไม่.<br/>             อ่านอย่างเดียว **bool**. |
| [`show_major_grid_lines`](/slides/python-net/th/aspose.slides.charts/iaxis/show_major_grid_lines/) | บ่งบอกว่าเส้นกริดหลักแสดงหรือไม่.<br/>             อ่านอย่างเดียว **bool**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/iaxis/format/) | บ่งบอกรูปแบบของแกน.<br/>             อ่านอย่างเดียว [`IAxisFormat`](/slides/python-net/th/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/th/aspose.slides.charts/iaxis/title/) | รับหัวข้อของแกน.<br/>             อ่านอย่างเดียว [`IChartTitle`](/slides/python-net/th/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/th/aspose.slides.charts/iaxis/cross_type/) | บ่งบอก CrossType บนแกนที่ระบุที่แกนอื่นตัดผ่าน.<br/>             อ่าน/เขียน [`CrossesType`](/slides/python-net/th/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/th/aspose.slides.charts/iaxis/position/) | บ่งบอกตำแหน่งของแกน.<br/>             อ่าน/เขียน [`AxisPositionType`](/slides/python-net/th/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/th/aspose.slides.charts/iaxis/has_title/) | กำหนดว่าแกนมีหัวข้อที่มองเห็นได้หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`number_format`](/slides/python-net/th/aspose.slides.charts/iaxis/number_format/) | บ่งบอกสตริงรูปแบบสำหรับป้ายแกน.<br/>            อ่าน/เขียน **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/th/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | บ่งบอกว่ารูปแบบเชื่อมกับข้อมูลต้นทางหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/th/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | บ่งบอกมุมการหมุนของป้ายเครื่องหมายติ๊ก<br/>            อ่าน/เขียน **float**. |
| [`tick_label_spacing`](/slides/python-net/th/aspose.slides.charts/iaxis/tick_label_spacing/) | ระบุจำนวนป้ายเครื่องหมายติ๊กที่ข้ามระหว่างป้ายที่วาด.<br/>            อ่าน/เขียน **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | ระบุค่าการเว้นระยะป้ายเครื่องหมายติ๊กอัตโนมัติ หากเป็น false ให้ใช้คุณสมบัติ TickLabelSpacing.<br/>            อ่าน/เขียน **bool**. |
| [`tick_marks_spacing`](/slides/python-net/th/aspose.slides.charts/iaxis/tick_marks_spacing/) | ระบุจำนวนเครื่องหมายติ๊กที่ต้องข้ามก่อนที่จะวาดเครื่องหมายถัดไป<br/>            ใช้กับแกนหมวดหมู่หรือซีรีส์.<br/>            อ่าน/เขียน **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | ระบุค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ หากเป็น false ให้ใช้คุณสมบัติ TickMarksSpacing.<br/>            อ่าน/เขียน **bool**. |
| [`label_offset`](/slides/python-net/th/aspose.slides.charts/iaxis/label_offset/) | ระบุระยะห่างของป้ายจากแกน ใช้กับแกนหมวดหมู่หรือวันที่ ค่าต้องอยู่ระหว่าง 0% ถึง 1000%.<br/>            อ่าน/เขียน **int**. |
| [`category_axis_type`](/slides/python-net/th/aspose.slides.charts/iaxis/category_axis_type/) | ระบุประเภทของแกนหมวดหมู่.<br/>            อ่าน/เขียน [`IAxis.category_axis_type`](/slides/python-net/th/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/th/aspose.slides.charts/iaxis/aggregation_type/) | บ่งบอกประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). ใช้กับหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`bin_width`](/slides/python-net/th/aspose.slides.charts/iaxis/bin_width/) | ระบุความกว้างของบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByBinWidth.<br/>            ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`number_of_bins`](/slides/python-net/th/aspose.slides.charts/iaxis/number_of_bins/) | ระบุจำนวนของบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByNumberOfBins.<br/>            ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น. |
| [`is_overflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/is_overflow_bin/) | ระบุว่ามีการใช้บินเกินหรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบินเกิน. |
| [`is_automatic_overflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | ระบุค่าบินเกินอัตโนมัติ หากเป็น false ให้ใช้คุณสมบัติ OverflowBin. |
| [`overflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/overflow_bin/) | ระบุค่าบินเกินที่กำหนดเอง ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ตั้งเป็น false และคุณสมบัติ IsOverflowBin มีค่า true. |
| [`is_underflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/is_underflow_bin/) | ระบุว่ามีการใช้บินขาดหรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบินขาด. |
| [`is_automatic_underflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | ระบุค่าบินขาดอัตโนมัติ หากเป็น false ให้ใช้คุณสมบัติ UnderflowBin. |
| [`underflow_bin`](/slides/python-net/th/aspose.slides.charts/iaxis/underflow_bin/) | ระบุค่าบินขาดที่กำหนดเอง ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ตั้งเป็น false และคุณสมบัติ IsUnderflowBin มีค่า true. |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/th/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/iaxis/presentation/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/th/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลแกน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)