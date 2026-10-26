---
title: ChartDataPoint class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint คลาส

แทนข้อมูลจุดของซีรีส์

ประเภท ChartDataPoint เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            อ่านอย่างเดียว [`IStringOrDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/size_value/) | คืนค่าขนาดของจุดข้อมูลแผนภูมิ.<br/>            ใช้กับแผนภูมิ Treemap และ Sunburst.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/color_value/) | คืนค่าสีของจุดข้อมูลแผนภูมิ.<br/>            ใช้กับแผนภูมิ Map.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | แทนค่าบาร์ข้อผิดพลาดของซีรีส์ในกรณีของประเภทค่า Custom.<br/>            อ่านอย่างเดียว [`IErrorBarsCustomValues`](/slides/python-net/th/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            อ่านอย่างเดียว [`IDataLabel`](/slides/python-net/th/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | กำหนดว่าฟองอากาศมีเอฟเฟ็กต์ 3-D ที่ใช้กับพวกมัน.<br/>            อ่าน/เขียน **bool**. |
| [`explosion`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/explosion/) | กำหนดจำนวนที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของพาย.<br/>            อ่าน/เขียน **int**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/format/) | แทนคุณสมบัติการจัดรูปแบบ.<br/>            อ่าน/เขียน [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/marker/) | กำหนดตัวทำเครื่องหมายข้อมูล.<br/>            อ่านอย่างเดียว [`IMarker`](/slides/python-net/th/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/set_as_total/) | ตั้งค่าจุดข้อมูลเป็นยอดรวม ใช้สำหรับซีรีส์ Waterfall เท่านั้น. |
| [`related_legend_entry`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/related_legend_entry/) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการนี้:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            อ่านอย่างเดียว [`ILegendEntryProperties`](/slides/python-net/th/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/data_point_levels/) | คืนค่าตัวคอนเทนเนอร์ของระดับจุดข้อมูล ใช้สำหรับซีรีส์ Treeamp และ Sunburst.<br/>            การจัดดัชนีระดับจุดข้อมูลเริ่มที่ศูนย์. |
| [`index`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/invert_if_negative/) | กำหนดให้จุดข้อมูลเปลี่ยนสีกลับหากค่าติดลบ.<br/>            อ่าน/เขียน **bool**. |
| [`actual_x`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/actual_x/) | กำหนดตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ.<br/>            เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.<br/>            อ่าน **float**. |
| [`actual_y`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/actual_y/) | กำหนดตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ.<br/>            เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.<br/>            อ่าน **float**. |
| [`actual_width`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/actual_width/) | กำหนดความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.<br/>            อ่าน **float**. |
| [`actual_height`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/actual_height/) | กำหนดความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.<br/>            อ่าน **float**. |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/remove/#) | ลบ DataPoint จากซีรีส์ของแผนภูมิ. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/th/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | คืนค่าสีอัตโนมัติของจุดข้อมูลที่อิงตามดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ.<br/>            สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)