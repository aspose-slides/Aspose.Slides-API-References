---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: लेजेंड संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

लेजेंड संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | लेजेंड एंट्री के गुण प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] से संबंधित है, यदि चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] से संबंधित है। |
| [getCount()](#getCount--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


लेजेंड एंट्री के गुण प्राप्त करता है जो Chart.ChartData.Series[0].DataPoints[index] से संबंधित है, यदि चार्ट प्रकार इस सूची में से हो: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; या अन्य चार्ट प्रकारों के लिए Chart.ChartData.Series[index] से संबंधित है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल पढ़ने योग्य int।

**रिटर्न:**
int