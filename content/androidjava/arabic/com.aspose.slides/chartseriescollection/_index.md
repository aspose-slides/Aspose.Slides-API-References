---
title: ChartSeriesCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من
type: docs
url: /ar/com.aspose.slides/chartseriescollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

يمثل مجموعة من [ChartSeries](../../com.aspose.slides/chartseries)

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [size()](#size--) | يرجع عددًا من الكائنات في المجموعة. |
| [add(int type)](#add-int-) | ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة. |
| [insert(int index, int type)](#insert-int-int-) | ينشئ سلسلة مخطط جديدة ويُدرجها في المجموعة. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | ينشئ سلسلة مخطط جديدة من [ChartDataCell](../../com.aspose.slides/chartdatacell) ويضيفها إلى المجموعة. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | ينشئ سلسلة مخطط جديدة من [ChartCellCollection](../../com.aspose.slides/chartcellcollection) ويضيفها إلى المجموعة. |
| [add(String name, int type)](#add-java.lang.String-int-) | ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | يبحث عن [ChartSeries](../../com.aspose.slides/chartseries) المحدد ويُرجع الفهرس الصفري للظهور الأول ضمن المجموعة بالكامل. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة. |
| [clear()](#clear--) | يزيل جميع عناصر التحكم من المجموعة. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ المجموعة بالكامل إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تدل على ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries) - العنصر عند الفهرس المحدد.

### size() {#size--}
```
public final int size()
```

يرجع عددًا من الكائنات في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع السلسلة |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط جديدة.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

ينشئ سلسلة مخطط جديدة ويُدرجها في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

ينشئ سلسلة مخطط جديدة من [ChartDataCell](../../com.aspose.slides/chartdatacell) ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية التي تحتوي على اسم السلسلة. |
| type | int | نوع يحدد نوع السلسلة |

--------------------
إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد الفهرس الخاص بها. |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة المخطط المضافة أو السلسلة الموجودة بالفعل في المجموعة.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

ينشئ سلسلة مخطط جديدة من [ChartCellCollection](../../com.aspose.slides/chartcellcollection) ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | الخلايا التي تحتوي على اسم السلسلة. |
| type | int | نوع يحدد نوع السلسلة |

--------------------
إذا تم إنشاء سلسلة مخطط من نفس الخلية الموجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد الفهرس الخاص بها. |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة المخطط المضافة أو السلسلة الموجودة بالفعل في المجموعة.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم السلسلة. |
| type | int | نوع يحدد نوع السلسلة |

**القيمة المرجعة:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة المخطط المضافة.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

يبحث عن [ChartSeries](../../com.aspose.slides/chartseries) المحدد ويُرجع الفهرس الصفري للظهور الأول ضمن المجموعة بالكامل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | قيمة سلسلة المخطط. |

**القيمة المرجعة:**
int - الفهرس الصفري للظهور الأول للقيمة ضمن CollectionBase بالكامل، إذا تم العثور عليها؛ وإلا -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل عنصر تحكم ActiveX المخزن في الموضع المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عنصر التحكم المراد إزالته. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع عناصر التحكم من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

يرجع مكرر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ المجموعة بالكامل إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف |
| index | int | الفهرس في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread-safe). boolean للقراءة فقط.

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. Object للقراءة فقط.