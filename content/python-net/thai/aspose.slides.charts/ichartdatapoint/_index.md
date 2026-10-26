---
title: IChartDataPoint class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint คลาส

แสดงจุดข้อมูลของซีรีส์.

The IChartDataPoint type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/x_value/) | คืนค่า x ของจุดข้อมูลแผนภูมิ.<br/>            อ่านอย่างเดียว [`IStringOrDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/y_value/) | คืนค่า y ของจุดข้อมูลแผนภูมิ.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/bubble_size/) | คืนค่าขนาดฟองของจุดข้อมูลแผนภูมิ.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/value/) | คืนค่าของจุดข้อมูลแผนภูมิ.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/size_value/) | คืนค่า ขนาด ของจุดข้อมูลแผนภูมิ.<br/>            ใช้กับแผนภูมิ Treemap และ Sunburst.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/color_value/) | คืนค่าสีของจุดข้อมูลแผนภูมิ.<br/>            ใช้กับแผนภูมิ Map.<br/>            อ่านอย่างเดียว [`IDoubleChartValue`](/slides/python-net/th/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | แสดงค่ามากล่ำของซีรีส์ในกรณีประเภทค่า Custom.<br/>            อ่านอย่างเดียว [`IErrorBarsCustomValues`](/slides/python-net/th/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/label/) | แสดงป้ายชื่อของจุดข้อมูลแผนภูมิ.<br/>            อ่านอย่างเดียว [`IDataLabel`](/slides/python-net/th/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน.<br/>            อ่าน/เขียน **bool**. |
| [`explosion`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/explosion/) | ระบุจำนวนที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของพาย.<br/>            อ่าน/เขียน **int**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/format/) | แสดงคุณสมบัติการจัดรูปแบบ.<br/>            อ่าน/เขียน [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/marker/) | ระบุเครื่องหมายข้อมูล.<br/>            อ่านอย่างเดียว [`IMarker`](/slides/python-net/th/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | คุณสมบัติของรายการคำอธิบายที่สอดคล้องในกรณีประเภทแผนภูมิจากรายการต่อไปนี้:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            อ่านอย่างเดียว [`ILegendEntryProperties`](/slides/python-net/th/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/set_as_total/) | ตั้งค่าจุดข้อมูลเป็นรวมทั้งหมด ใช้เฉพาะประเภทซีรีส์ Waterfall เท่านั้น. |
| [`invert_if_negative`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | ระบุว่าจุดข้อมูลจะสลับสีหากค่าติดลบ.<br/>            อ่าน/เขียน **bool**. |
| [`data_point_levels`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/data_point_levels/) | คืนภาชนะของระดับจุดข้อมูล ใช้กับซีรีส์ Treeamp และ Sunburst.<br/>            การจัดทำดัชนีระดับจุดข้อมูลเป็นศูนย์ฐาน. |
| [`index`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/index/) | ระบุว่าจุดข้อมูลนี้ใช้กับคอลเลกชันลูกของพาเรนท์ใด<br/>            อ่าน **int**. |
| [`actual_x`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/remove/#) | ลบ DataPoint จากซีรีส์แผนภูมิ. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | คืนค่าสีอัตโนมัติของจุดข้อมูลโดยอิงตามดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ.<br/>            สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)