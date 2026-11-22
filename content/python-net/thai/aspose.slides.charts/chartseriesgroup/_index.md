---
title: ChartSeriesGroup class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup คลาส

แสดงถึงกลุ่มของซีรีส์

ชนิด ChartSeriesGroup มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/type/) | คืนค่าประเภทของกลุ่มซีรีส์นี้<br/>            อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](/slides/python-net/th/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | ระบุว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่<br/>            อ่านอย่างเดียว **bool**. |
| [`series`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/series/) | คืนค่าคอลเลกชันของซีรีส์<br/>            อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/up_down_bars/) | ให้การเข้าถึงบาร์ขึ้น/ลงของกราฟเส้นหรือกราฟหุ้น<br/>            อ่านอย่างเดียว [`IUpDownBarsManager`](/slides/python-net/th/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/gap_width/) | กำหนดหรือรับระยะห่างระหว่างคลัสเตอร์ของบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์<br/>            ค่าต้องอยู่ระหว่าง 0 ถึง 500<br/>            อ่าน/เขียน **int**. |
| [`gap_depth`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/gap_depth/) | กำหนดหรือรับระยะห่างระหว่างซีรีส์ข้อมูลในกราฟ 3D เป็นเปอร์เซ็นต์ของความกว้างเครื่องหมาย<br/>            ค่าต้องอยู่ระหว่าง 0 ถึง 500<br/>            อ่าน/เขียน **int**. |
| [`first_slice_angle`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | กำหนดหรือรับมุมของชิ้นพายหรือโดนัทชาร์ตแรก<br/>            เป็นองศา (หมุนตามเข็มนาฬิกาจากตำแหน่งบน, ตั้งแต่ 0 ถึง 360 องศา)<br/>            อ่าน/เขียน **int**. |
| [`doughnut_hole_size`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | ระบุขนาดของรูในกราฟโดนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของพื้นที่แผนภูมิ)<br/>            อ่าน/เขียน **int**. |
| [`overlap`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/overlap/) | ระบุว่าบาร์และคอลัมน์จะทับซ้อนกันบนกราฟ 2 มิติเท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%)<br/>             - -100%: ช่องว่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์)<br/>             - 0%: บาร์วางติดกันโดยไม่มีการทับซ้อนหรือช่องว่าง<br/>             - 100%: ทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด)<br/>             คุณสมบัตินี้อ่าน/เขียน **int**. |
| [`second_pie_size`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/second_pie_size/) | ระบุขนาดของพายหรือบาร์ที่สองของกราฟพาย-ของ-พาย หรือบาร์-ของ-พายในรูปเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์)<br/>            อ่าน/เขียน **int**. |
| [`bubble_size_representation`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | ระบุวิธีที่ค่าขนาดของฟองอากาศแสดงบนกราฟฟองอากาศ<br/>            อ่าน/เขียน [`BubbleSizeRepresentationType`](/slides/python-net/th/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_position/) | ระบุค่าที่ใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของกราฟพาย-ของ-พายหรือบาร์-ของ-พาย<br/>            ใช้ร่วมกับคุณสมบัติ PieSplitBy<br/>            อ่าน/เขียน **float**. |
| [`pie_split_by`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_by/) | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองของกราฟพาย-ของ-พายหรือบาร์-ของ-พาย<br/>            อ่าน/เขียน [`PieSplitType`](/slides/python-net/th/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/is_color_varied/) | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน<br/>            อ่าน/เขียน **bool**. |
| [`has_series_lines`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/has_series_lines/) | จริงหากแผนภูมิมีเส้นซีรีส์ ใช้กับกราฟบาร์ซ้อนกันและ OfPie<br/>            อ่าน/เขียน **bool**. |
| [`hi_low_lines_format`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | ระบุรูปแบบ HiLowLines<br/>            HiLowLines ใช้ร่วมกับชนิดกราฟ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose |
| [`bubble_size_scale`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | ระบุแฟกเตอร์สเกลสำหรับกราฟฟองอากาศ (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น)<br/>            อ่าน/เขียน **int**. |
| [`pie_split_custom_points`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | ข้อมูลการแยกแบบกำหนดเองสำหรับกราฟพาย-ของ-พายหรือบาร์-ของ-พายที่มีการแยกแบบกำหนดเอง<br/>            มีจุดข้อมูลที่ควรวาดในพายหรือบาร์ที่สองของกราฟพาย-ของ-พายหรือบาร์-ของ-พาย<br/>            อ่านอย่างเดียว [`PieSplitCustomPointCollection`](/slides/python-net/th/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/chart/) | คืนค่าชาร์ตแม่<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/presentation/) |  |

รับองค์ประกอบที่ตำแหน่งที่ระบุ

## ดัชนี

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup  
2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม ("คุณสมบัติกลุ่มซีรีส์")  
   "คุณสมบัติกลุ่มซีรีส์" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน  
   แต่ละ "คุณสมบัติกลุ่มซีรีส์" สามารถมีการแสดงผลแบบอ่านอย่างเดียวในคลาส ChartSeries  

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)