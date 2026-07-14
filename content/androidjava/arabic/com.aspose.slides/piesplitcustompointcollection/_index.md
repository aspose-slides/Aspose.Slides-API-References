---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides لـ Android عبر مرجع API للـ Java
description: يمثل مجموعة من النقاط لنقطة التقسيم في مخطط شريط-دائري أو مخطط دائرة-داخل-دائرة مع تقسيم مخصص.
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

يمثل مجموعة من النقاط لنقطة الانقسام في مخطط شريطي داخل شريحة أو شريحة داخل شريحة مع انقسام مخصص.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع نقطة بيانات المخطط للمؤشر المحدد. |
| [add(int dataPointIndex)](#add-int-) | يضيف نقطة بيانات حسب مؤشرها في مجموعة نقاط السلسلة الأم. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | يضيف نقطة بيانات إلى المجموعة. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | يزيل العنصر من المجموعة. |
| [remove(int dataPointIndex)](#remove-int-) | يزيل العنصر من المجموعة حسب مؤشره في مجموعة نقاط السلسلة الأم. |
| [clear()](#clear--) | يزيل جميع العناصر من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة محدد. |
| [size()](#size--) | يرجع أو يعيّن عدد نقاط بيانات المخطط. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل خلال المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر java للمجموعة بالكامل. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

يرجع نقطة بيانات المخطط للمؤشر المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات المخطط.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

يضيف نقطة بيانات حسب مؤشرها في مجموعة نقاط السلسلة الأم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | مؤشر نقطة البيانات في مجموعة نقاط السلسلة الأم. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

يضيف نقطة بيانات إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة البيانات التي ستُضاف إلى. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

يزيل العنصر من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطة البيانات التي ستُزال من. |

**القيمة المرجعة:**
منطقي - true إذا تم إزالة العنصر بنجاح؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في System.Collections.Generic.List{T}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

يزيل العنصر من المجموعة حسب مؤشره في مجموعة نقاط السلسلة الأم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| dataPointIndex | int | مؤشر نقطة البيانات في مجموعة نقاط السلسلة الأم. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | الكائن لتحديد موقعه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
منطقي - true إذا وجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة محدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | المصفوفة أحادية البعد التي هي وجهة العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة تبدأ من الصفر. |
| arrayIndex | int | الفهرس الصفري في المصفوفة الذي يبدأ عنده النسخ. |
### size() {#size--}
```
public final int size()
```

يرجع أو يعيّن عدد نقاط بيانات المخطط. int للقراءة فقط.

**القيمة المرجعة:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. منطقي للقراءة فقط.

**القيمة المرجعة:**
منطقي - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). منطقي للقراءة فقط.

**القيمة المرجعة:**
منطقي
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. Object للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

يرجع مكرّر java للمجموعة بالكامل.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.