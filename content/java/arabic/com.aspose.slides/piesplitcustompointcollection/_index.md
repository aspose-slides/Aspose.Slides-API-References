---
title: PieSplitCustomPointCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من النقاط لتقسيم النقطة في مخطط شريحة-بار أو مخطط شريحة-شريحة مع تقسيم مخصص.
type: docs
url: /ar/com.aspose.slides/piesplitcustompointcollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

يمثل مجموعة من النقاط لتقسيم نقطة في مخطط شريحة-بار أو مخطط شريحة-شريحة مع تقسيم مخصص.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يُرجِع نقطة بيانات المخطط للمؤشر المحدد. |
| [add(int dataPointIndex)](#add-int-) | يضيف نقطة بيانات حسب مؤشرها في مجموعة نقاط السلسلة الأصلية. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | يضيف نقطة بيانات إلى المجموعة. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | يزيل العنصر من المجموعة. |
| [remove(int dataPointIndex)](#remove-int-) | يزيل العنصر من المجموعة حسب موقعه في مجموعة نقاط السلسلة الأصلية. |
| [clear()](#clear--) | يزيل جميع العناصر من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | يحدِّد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [size()](#size--) | يُرجِع أو يعيِّن عدد نقاط بيانات المخطط. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تُشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [isSynchronized()](#isSynchronized--) | يُرجِع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يُرجِع جذر التزامن. |
| [iterator()](#iterator--) | يُرجِع عدّادًا يتنقّل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُرجِع مكرِّرًا جافا للمجموعة بأكملها. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

يُرجِع نقطة بيانات المخطط للمؤشر المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس. |

**القيم المُرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات المخطط.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

يضيف نقطة بيانات حسب مؤشرها في مجموعة نقاط السلسلة الأصلية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

يضيف نقطة بيانات إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة البيانات التي تُضاف إليها. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

يزيل العنصر من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة البيانات التي تُزال منها. |

**القيم المُرجعة:**
boolean - true إذا تمت إزالة العنصر بنجاح؛ وإلا false. تُعيد هذه الطريقة أيضًا false إذا لم يُعثر على العنصر في System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

يزيل العنصر من المجموعة حسب موقعه في مجموعة نقاط السلسلة الأصلية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | فهرس نقطة البيانات في مجموعة نقاط السلسلة الأصلية. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

يحدِّد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | الكائن الذي يُبحث عنه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيم المُرجعة:**
boolean - true إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | المصفوفة أحادية البُعد التي هي هدف العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة تبدأ من الصفر. |
| arrayIndex | int | الفهرس الذي يبدأ منه النسخ في المصفوفة. |

### size() {#size--}
```
public final int size()
```

يُرجِع أو يعيِّن عدد نقاط بيانات المخطط. عدد صحيح للقراءة فقط.

**القيم المُرجعة:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تُشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. منطق للقراءة فقط.

**القيم المُرجعة:**
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُرجِع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). منطق للقراءة فقط.

**القيم المُرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُرجِع جذر التزامن. كائن للقراءة فقط.

**القيم المُرجعة:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

يُرجِع عدّادًا يتنقّل عبر المجموعة.

**القيم المُرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator يمكن استعماله للتنقّل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

يُرجِع مكرِّرًا جافا للمجموعة بأكملها.

**القيم المُرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator للمجموعة بأكملها.