---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: लेजेंड्स संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

लेजेंड्स संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | लेजेंड एंट्री की गुण प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] के अनुरूप है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] के अनुरूप। |
| [getCount()](#getCount--) | संग्रह में वास्तव में शामिल तत्वों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

लेजेंड एंट्री की गुण प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] के अनुरूप है जब चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] के अनुरूप।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में वास्तव में शामिल तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int