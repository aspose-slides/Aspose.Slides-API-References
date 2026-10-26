---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: चार्ट श्रेणी स्तरों के मानों का प्रबंधित कंटेनर।
type: docs
url: /hi/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

चार्ट श्रेणी स्तरों के मानों का प्रबंधित कंटेनर।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | परिभाषित स्तर के लिए IChartDataCell ऑब्जेक्ट लौटाता है। |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | परिभाषित स्तर के लिए समूह आइटम सेट करता है। |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | परिभाषित स्तर के लिए समूह आइटम हटाता है। |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
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
public abstract void setGroupingItem(int level, Object value)
```


परिभाषित स्तर के लिए समूह आइटम सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| level | int | श्रेणी स्तर int |
| value | java.lang.Object | समूह आइटम ऑब्जेक्ट |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```


परिभाषित स्तर के लिए समूह आइटम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| level | int | श्रेणी स्तर int |