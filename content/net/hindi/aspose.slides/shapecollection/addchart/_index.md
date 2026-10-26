---
title: AddChart
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है और इसे शेप संग्रह के अंत में जोड़ता है।
type: docs
weight: 100
url: /hi/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे शेप संग्रह के अंत में जोड़ता है।

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | ChartType | जोड़ने के लिए चार्ट का प्रकार। |
| x | Single | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | Single | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | Single | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | Single | चार्ट की ऊँचाई, पॉइंट्स में। |

### रिटर्न मान

नया निर्मित [`IChart`](../../../aspose.slides.charts/ichart)।

### उदाहरण

नीचे दिया गया उदाहरण PowerPoint प्रस्तुति में चार्ट बनाने का तरीका दिखाता है।

```csharp
[C#]
// PPTX फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास को इंस्टैंसिएट करता है
using(Presentation pres = new Presentation()) {
  // पहले स्लाइड तक पहुँचता है
  ISlide sld = pres.Slides[0];
  // डिफ़ॉल्ट डेटा के साथ एक चार्ट जोड़ता है
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // चार्ट शीर्षक सेट करता है
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // पहली श्रृंखला को मान दिखाने के लिए सेट करता है
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // चार्ट डेटा शीट के लिए इंडेक्स सेट करता है
  int defaultWorksheetIndex = 0;
  // चार्ट डेटा वर्कशीट प्राप्त करता है
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // डिफ़ॉल्ट उत्पन्न श्रृंखला और श्रेणियों को हटाता है
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // नई श्रृंखला जोड़ता है
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // नई श्रेणियाँ जोड़ता है
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // पहली चार्ट श्रृंखला लेता है
  IChartSeries series = chart.ChartData.Series[0];
  // श्रृंखला डेटा को भरता है
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // श्रृंखला के लिए भरने का रंग सेट करता है
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // दूसरी चार्ट श्रृंखला लेता है
  series = chart.ChartData.Series[1];
  // श्रृंखला डेटा को भरता है
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // श्रृंखला के लिए भरने का रंग सेट करता है
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // पहले लेबल को श्रेणी का नाम दिखाने के लिए सेट करता है
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // श्रृंखला को तीसरे लेबल के लिए मान दिखाने के लिए सेट करता है
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // PPTX फ़ाइल को डिस्क पर सेव करता है
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* इंटरफ़ेस [IChart](../../../aspose.slides.charts/ichart)
* एनम [ChartType](../../../aspose.slides.charts/charttype)
* क्लास [ShapeCollection](../../shapecollection)
* नामस्थान [Aspose.Slides](../../shapecollection)
* असेंबली [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

एक नया चार्ट बनाता है, इसे नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करता है, और इसे शेप संग्रह के अंत में जोड़ता है।

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | ChartType | जोड़ने के लिए चार्ट का प्रकार। |
| x | Single | नए चार्ट का x-निर्देशांक, पॉइंट्स में। |
| y | Single | नए चार्ट का y-निर्देशांक, पॉइंट्स में। |
| width | Single | चार्ट की चौड़ाई, पॉइंट्स में। |
| height | Single | चार्ट की ऊँचाई, पॉइंट्स में। |
| initWithSample | Boolean | नए चार्ट को नमूना श्रृंखला डेटा और सेटिंग्स के साथ प्रारंभ करने के लिए True; यदि False हो तो चार्ट को बिना श्रृंखला और केवल न्यूनतम सेटिंग्स के साथ बनाया जाएगा, जिससे निर्माण तेज़ होता है। |

### रिटर्न मान

नया निर्मित [`IChart`](../../../aspose.slides.charts/ichart)।

### संबंधित देखें

* इंटरफ़ेस [IChart](../../../aspose.slides.charts/ichart)
* एनम [ChartType](../../../aspose.slides.charts/charttype)
* क्लास [ShapeCollection](../../shapecollection)
* नामस्थान [Aspose.Slides](../../shapecollection)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->