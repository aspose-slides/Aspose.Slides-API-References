---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: चार्ट श्रेणी स्तरों के मानों का प्रबंधित कंटेनर।
type: docs
url: /hi/com.aspose.slides/chartcategorylevelsmanager/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

चार्ट श्रेणी स्तरों के मानों का प्रबंधित कंटेनर।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataCell object for defined level. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | Sets grouping item for defined level. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | Delete grouping item for defined level. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```


परिभाषित स्तर के लिए IChartDataCell ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| level | int |  |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```


परिभाषित स्तर के लिए समूह आइटम सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```


परिभाषित स्तर के लिए समूह आइटम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| level | int |  |