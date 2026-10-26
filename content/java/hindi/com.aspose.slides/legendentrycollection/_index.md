---
title: LegendEntryCollection
second_title: Aspose.Slides for Java API संदर्भ
description: लेजेंड संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/legendentrycollection/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

लेजेंड संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Chart.ChartData.Series[0].DataPoints[index] के अनुरूप लेजेंड प्रविष्टि की गुणधर्म प्राप्त करता है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] के अनुरूप। |
| [getCount()](#getCount--) | लेजेंड प्रविष्टियों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Chart.ChartData.Series[0].DataPoints[index] के अनुरूप लेजेंड प्रविष्टि की गुणधर्म प्राप्त करता है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] के अनुरूप।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


लेजेंड प्रविष्टियों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int.

**रिटर्न:**
int