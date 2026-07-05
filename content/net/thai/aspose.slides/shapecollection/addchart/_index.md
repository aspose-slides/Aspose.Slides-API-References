---
title: AddChart
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: สร้าง chart ใหม่ กำหนดค่าเริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชัน shape
type: docs
weight: 100
url: /th/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

สร้างแผนภูมิใหม่, กำหนดค่าเริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และเพิ่มเข้าที่ส่วนท้ายของคอลเลกชันรูปทรง

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | ChartType | ชนิดของแผนภูมิที่ต้องการเพิ่ม |
| x | Single | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | Single | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | Single | ความกว้างของแผนภูมิ, หน่วยเป็นจุด |
| height | Single | ความสูงของแผนภูมิ, หน่วยเป็นจุด |

### Return Value

ออบเจ็กต์ที่สร้างใหม่ [`IChart`](../../../aspose.slides.charts/ichart).

### Examples

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง Chart ใน PowerPoint Presentation.

```csharp
[C#]
// สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของไฟล์ PPTX
using(Presentation pres = new Presentation()) {
  // เข้าถึงสไลด์แรก
  ISlide sld = pres.Slides[0];
  // เพิ่มแผนภูมิพร้อมข้อมูลค่าเริ่มต้น
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // ตั้งค่าชื่อเรื่องของแผนภูมิ
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // ตั้งค่าให้ซีรีส์แรกแสดงค่าตัวเลข
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // ตั้งค่า index สำหรับแผ่นข้อมูลของแผนภูมิ
  int defaultWorksheetIndex = 0;
  // ดึงแผ่นงานข้อมูลของแผนภูมิ
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // ลบซีรีส์และหมวดหมู่ที่สร้างขึ้นโดยค่าเริ่มต้น
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // เพิ่มซีรีส์ใหม่
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // เพิ่มหมวดหมู่ใหม่
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // รับซีรีส์แผนภูมิเชิงแรก
  IChartSeries series = chart.ChartData.Series[0];
  // เติมข้อมูลซีรีส์
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // ตั้งค่าสีเติมสำหรับซีรีส์
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // รับซีรีส์แผนภูมิที่สอง
  series = chart.ChartData.Series[1];
  // เติมข้อมูลซีรีส์
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // ตั้งค่าสีเติมสำหรับซีรีส์
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // ตั้งค่าป้ายกำกับแรกให้แสดงชื่อหมวดหมู่
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // ตั้งค่าซีรีส์ให้แสดงค่าตัวเลขสำหรับป้ายกำกับที่สาม
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // บันทึกไฟล์ PPTX ลงดิสก์
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* คลาส [ShapeCollection](../../shapecollection)
* เนมสเปซ [Aspose.Slides](../../shapecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

สร้างแผนภูมิใหม่, กำหนดค่าเริ่มต้นด้วยข้อมูลและการตั้งค่าตัวอย่าง, และเพิ่มเข้าที่ส่วนท้ายของคอลเลกชันรูปทรง

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | ChartType | ชนิดของแผนภูมิที่ต้องการเพิ่ม |
| x | Single | พิกัด x ของแผนภูมิใหม่, หน่วยเป็นจุด |
| y | Single | พิกัด y ของแผนภูมิใหม่, หน่วยเป็นจุด |
| width | Single | ความกว้างของแผนภูมิ, หน่วยเป็นจุด |
| height | Single | ความสูงของแผนภูมิ, หน่วยเป็นจุด |
| initWithSample | Boolean | True เพื่อกำหนดค่าเริ่มต้นของแผนภูมิใหม่ด้วยข้อมูลและการตั้งค่าตัวอย่าง; false เพื่อสร้างแผนภูมิที่ไม่มีชุดข้อมูลและมีการตั้งค่าน้อยที่สุด ซึ่งทำให้การสร้างเร็วขึ้น |

### Return Value

ออบเจ็กต์ที่สร้างใหม่ [`IChart`](../../../aspose.slides.charts/ichart).

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* คลาส [ShapeCollection](../../shapecollection)
* เนมสเปซ [Aspose.Slides](../../shapecollection)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->