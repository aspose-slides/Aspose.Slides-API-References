---
title: ChartSeriesGroup class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup คลาส

Represents group of series.

The ChartSeriesGroup type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`type`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/type/) | คืนค่าชนิดของกลุ่มซีรีส์นี้.<br/>อ่านอย่างเดียว [`CombinableSeriesTypesGroup`](/slides/python-net/th/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | บ่งชี้ว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนที่สองหรือไม่.<br/>อ่านอย่างเดียว **bool**. |
| [`series`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/series/) | คืนค่าคอลเลกชันของซีรีส์.<br/>อ่านอย่างเดียว [`IChartSeriesReadonlyCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/up_down_bars/) | ให้การเข้าถึงแถบ up/down ของแผนภูมิ Line หรือ Stock.<br/>อ่านอย่างเดียว [`IUpDownBarsManager`](/slides/python-net/th/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/gap_width/) | กำหนดช่องว่างระหว่างคลัสเตอร์ของแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแถบหรือคอลัมน์.<br/>อ่าน/เขียน **int**. |
| [`gap_depth`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/gap_depth/) | คืนค่า หรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้างของมาร์กเกอร์ ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ.<br/>อ่าน/เขียน **int**. |
| [`first_slice_angle`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัท<br/>เป็นองศา (ตามเข็มนาฬิกาจากบน, ตั้งแต่ 0 ถึง 360 องศา).<br/>อ่าน/เขียน **int**. |
| [`doughnut_hole_size`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | กำหนดขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดของพื้นที่พล็อต).<br/>อ่าน/เขียน **int**. |
| [`overlap`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/overlap/) | กำหนดว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%).<br/>- -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์).<br/>- 0%: บาร์จัดวางเคียงกันโดยไม่มีการทับซ้อนหรือระยะห่าง.<br/>- 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันอย่างเต็มที่).<br/>คุณสมบัตินี้เป็นอ่าน/เขียน **int**. |
| [`second_pie_size`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/second_pie_size/) | กำหนดขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์).<br/>อ่าน/เขียน **int**. |
| [`bubble_size_representation`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | กำหนดว่าค่าขนาดของบับเบิลจะแสดงอย่างไรบนแผนภูมิบับเบิล.<br/>อ่าน/เขียน [`BubbleSizeRepresentationType`](/slides/python-net/th/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_position/) | กำหนดค่าที่จะใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie.<br/>ใช้ร่วมกับคุณสมบัติ PieSplitBy.<br/>อ่าน/เขียน **float**. |
| [`pie_split_by`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_by/) | กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie.<br/>อ่าน/เขียน [`PieSplitType`](/slides/python-net/th/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/is_color_varied/) | กำหนดว่าแต่ละมาร์กเกอร์ข้อมูลในซีรีส์จะมีสีที่แตกต่างกัน.<br/>อ่าน/เขียน **bool**. |
| [`has_series_lines`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/has_series_lines/) | เป็น true หากแผนภูมิมีเส้นซีรีส์ ใช้กับแผนภูมิ stacked bar และ OfPie.<br/>อ่าน/เขียน **bool**. |
| [`hi_low_lines_format`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | กำหนดรูปแบบ HiLowLines.<br/>HiLowLines ถูกนำไปใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | กำหนดปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น).<br/>อ่าน/เขียน **int**. |
| [`pie_split_custom_points`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง.<br/>มีจุดข้อมูลที่ควรวาดในพายหรือแถบที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie.<br/>อ่านอย่างเดียว [`PieSplitCustomPointCollection`](/slides/python-net/th/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/chart/) | คืนค่าแผนภูมิแม่.<br/>อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/presentation/) |  |

รับองค์ประกอบที่ตำแหน่งที่ระบุ

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup.  
2) กลุ่มของซีรีส์มีคุณสมบัติของซีรีส์บางอย่างที่เป็นเรื่องทั่วไปสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties").  
"Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน.  
แต่ละ "series group properties" สามารถมีการฉายภาพอ่านอย่างเดียวในคลาส ChartSeries.

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)