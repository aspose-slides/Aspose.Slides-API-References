---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: แสดงถึงคอลเลกชันของกลุ่มของซีรีส์ที่สามารถรวมกันได้.
type: docs
url: /th/com.aspose.slides/ichartseriesgroupcollection/
---
**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

แทนชุดของกลุ่มของซีรีส์ที่สามารถรวมเข้าด้วยกันได้.

--------------------

1) แต่ละกลุ่มของซีรีส์ประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์ยังมีซีรีส์ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองแบบในกลุ่มเดียวกัน). ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตหลัก/รอง. 2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างที่เป็นของรวมสำหรับแต่ละซีรีส์ในกลุ่ม ("Series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "Series group properties" สามารถมีการฉายเป็นแบบอ่านอย่างเดียวในคลาส ChartSeries.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | ดึงกลุ่มซีรีส์ตามซีรีส์. |
| [get_Item(int index)](#get-Item-int-) | ดึงกลุ่มซีรีส์ตามดัชนี. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

ดึงกลุ่มซีรีส์ตามซีรีส์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**ผลลัพธ์:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

ดึงกลุ่มซีรีส์ตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)