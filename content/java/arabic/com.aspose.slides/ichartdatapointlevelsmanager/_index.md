---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides للغة Java مرجع API
description: حاوية مستويات نقاط البيانات. تُطبق على سلسلة Treeamp و Sunburst. فهرسة مستويات نقاط البيانات تبدأ من الصفر.
type: docs
url: /ar/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

حاوية مستويات نقاط البيانات. تُطبق على سلاسل Treeamp و Sunburst. فهرسة مستويات نقاط البيانات تبدأ من الصفر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | يُرجِع كائن IChartDataPointLevel للمستوى المحدد. |
| [getCount()](#getCount--) | يُرجِع عدد مستويات نقطة البيانات. |

### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

يُرجِع كائن IChartDataPointLevel للمستوى المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| level | int |  |

**القيمة المرجعة:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)

### getCount() {#getCount--}
```
public abstract int getCount()
```

يُرجِع عدد مستويات نقطة البيانات.

**القيمة المرجعة:**
int