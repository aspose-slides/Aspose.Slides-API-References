---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงถึงคอลเลกชันของกลุ่มซีรีส์ที่สามารถรวมกันได้.
type: docs
url: /th/com.aspose.slides/ichartseriesgroupcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

แสดงถึงคอลเลกชันของกลุ่มซีรีส์ที่สามารถรวมกันได้

--------------------

1) แต่ละกลุ่มของซีรีส์จะประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้ กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้จะถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup นอกจากนี้แต่ละกลุ่มของซีรีส์ยังประกอบด้วยซีรีส์ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว) ดังนั้นหลักการของการจัดกลุ่มซีรีส์คือการจัดตามประเภทของกลุ่มที่กล่าวถึงข้างต้นและตามประเภทการพล็อตหลัก/รอง 2) กลุ่มของซีรีส์จะมีคุณสมบัติบางอย่างที่เป็นค่าร่วมสำหรับแต่ละซีรีส์ในกลุ่ม (“คุณสมบัติของกลุ่มซีรีส์”) “คุณสมบัติของกลุ่มซีรีส์” ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน แต่ละ “คุณสมบัติของกลุ่มซีรีส์” สามารถมีการฉายเป็นแบบอ่านอย่างเดียวในคลาส ChartSeries

## Methods

| Method | Description |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Gets the series group by series. |
| [get_Item(int index)](#get-Item-int-) | Gets the series group by index. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

รับกลุ่มซีรีส์ตามซีรีส์

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

รับกลุ่มซีรีส์ตามดัชนี

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)