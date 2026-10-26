---
title: AddChart()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างแผนภูมิใหม่ เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปทรง
type: docs
weight: 66
url: /th/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) เมธอด

สร้างแผนภูมิใหม่ เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปทรง

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่ต้องการเพิ่ม |
| x | **float** | พิกัด x ของแผนภูมิใหม่ หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของแผนภูมิ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของแผนภูมิ หน่วยเป็นพอยต์ |

### ค่าที่ส่งคืน

วัตถุ [Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีสร้างแผนภูมิใน PowerPoint [Presentation](../../presentation/). 
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนไฟล์ PPTX
auto pres = System::MakeObject<Presentation>();
// เข้าถึงสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// เพิ่มแผนภูมิพร้อมข้อมูลเริ่มต้น
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// ตั้งค่าชื่อแผนภูมิ
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// ตั้งค่าให้ซีรีส์แรกแสดงค่า
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// ตั้งค่าดัชนีสำหรับแผ่นข้อมูลแผนภูมิ
int32_t defaultWorksheetIndex = 0;
// เรียกแผ่นงานข้อมูลแผนภูมิ
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// ลบซีรีส์และหมวดหมู่ที่สร้างโดยอัตโนมัติเริ่มต้น
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// เพิ่มซีรีส์ใหม่
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// เพิ่มหมวดหมู่ใหม่
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// ดึงซีรีส์แผนภูมิเพื่อใช้ครั้งแรก
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// เติมข้อมูลให้ซีรีส์
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// ตั้งค่าสีเติมสำหรับซีรีส์
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// ดึงซีรีส์แผนภูมิที่สอง
series = chart->get_ChartData()->get_Series()->idx_get(1);
// เติมข้อมูลให้ซีรีส์
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// ตั้งค่าสีเติมสำหรับซีรีส์
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// ตั้งค่าป้ายกำกับแรกให้แสดงชื่อหมวดหมู่
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// ตั้งค่าซีรีส์ให้แสดงค่าที่ป้ายกำกับที่สาม
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// บันทึกไฟล์ PPTX ลงดิสก์
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) เมธอด

สร้างแผนภูมิใหม่ เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปทรง

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | ประเภทของแผนภูมิที่ต้องการเพิ่ม |
| x | **float** | พิกัด x ของแผนภูมิใหม่ หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่ หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของแผนภูมิ หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของแผนภูมิ หน่วยเป็นพอยต์ |
| initWithSample | **bool** | true เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลชุดตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิโดยไม่มีชุดข้อมูลและตั้งค่าเพียงขั้นต่ำ ซึ่งทำให้การสร้างเร็วขึ้น |

### ค่าที่ส่งคืน

วัตถุ [Charts::IChart](../../../aspose.slides.charts/ichart/) ที่สร้างใหม่

## ดูเพิ่มเติม

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChart](../../../aspose.slides.charts/ichart/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)