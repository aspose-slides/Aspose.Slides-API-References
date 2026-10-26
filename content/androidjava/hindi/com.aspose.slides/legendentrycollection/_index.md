---
title: LegendEntryCollection
second_title: Aspose.Slides के लिए Android के माध्यम से Java API संदर्भ
description: लेजेंड्स संग्रह का प्रतिनिधित्व करता है।
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

लेजेंड्स संग्रह का प्रतिनिधित्व करता है।  
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | लेजेंड एंट्री की प्रॉपर्टीज़ प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] से संबंधित है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] से संबंधित है। |
| [getCount()](#getCount--) | लेजेंड एंट्रीज़ की संख्या प्राप्त करता है। |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

लेजेंड एंट्री की प्रॉपर्टीज़ प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] से संबंधित है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] से संबंधित है।

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

लेजेंड एंट्रीज़ की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**रिटर्न:**  
int