---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides के लिए Java API संदर्भ
description: चार्ट डेटा वर्कबुक के कार्यपत्रकों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartdataworksheetcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

चार्ट डेटा वर्कबुक के कार्यपत्रकों का संग्रह दर्शाता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा कार्यपत्रक लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

इंडेक्स द्वारा कार्यपत्रक लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | संग्रह में कार्यपत्रक का इंडेक्स। |

**रिटर्न:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet का उदाहरण।