---
title: SetExternalWorkbook()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد دفتر عمل خارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل المستهدف.
type: docs
weight: 183
url: /ar/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) طريقة

يحدد دفتر عمل خارجي كمصدر بيانات للمخطط. [Chart](../../chart/) سيتم تحديث البيانات من دفتر العمل المستهدف.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | المسار إلى دفتر العمل المستهدف |

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) طريقة

يحدد دفتر عمل خارجي كمصدر بيانات للمخطط.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | المسار إلى دفتر العمل المستهدف |
| updateChartData | **bool** | إذا كانت القيمة false فسيتم تحديث مسار دفتر العمل فقط. [Chart](../../chart/) لن يتم تحميل البيانات وتحديثها من دفتر العمل المستهدف. يمكن استخدام ذلك عندما لا يكون دفتر العمل المستهدف موجودًا أو غير متوفر. إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل المستهدف. |

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ChartData](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)