---
title: IChartSeriesCollection
second_title: Aspose.Slides للـ Java – مرجع API
description: يمثل مجموعة من
type: docs
url: /ar/com.aspose.slides/ichartseriescollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

يمثل مجموعة من [IChartSeries](../../com.aspose.slides/ichartseries)
## طرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [add(int type)](#add-int-) | ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة. |
| [insert(int index, int type)](#insert-int-int-) | ينشئ سلسلة مخطط جديدة ويُدرجها في المجموعة. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | ينشئ سلسلة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) ويضيفها إلى المجموعة. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | ينشئ سلسلة مخطط جديدة من [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ويضيفها إلى المجموعة. |
| [add(String name, int type)](#add-java.lang.String-int-) | ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | يبحث عن [IChartSeries](../../com.aspose.slides/ichartseries) المحدد ويعيد الفهرس الصفري للموقع الأول ضمن المجموعة بالكامل. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد |
| [clear()](#clear--) | يزيل جميع العناصر (بما في ذلك نمط المخطط) من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - العنصر في الفهرس المحدد.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

ينشئ سلسلة مخطط جديدة ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع السلسلة |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط جديدة.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

ينشئ سلسلة مخطط جديدة ويُدرجها في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس للإدراج |
| type | int | نوع المخطط [ChartType](../../com.aspose.slides/charttype) |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط جديدة [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

ينشئ سلسلة مخطط جديدة من [IChartDataCell](../../com.aspose.slides/ichartdatacell) ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | الخلية التي تحتوي على اسم السلسلة. |
| type | int | نوع السلسلة |

--------------------

إذا تم إنشاء سلسلة مخطط من خلية نفسها موجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرستها. |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط مضافة أو سلسلة موجودة بالفعل في المجموعة.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

ينشئ سلسلة مخطط جديدة من [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | الخلايا التي تحتوي على اسم السلسلة. |
| type | int | نوع السلسلة |

--------------------

إذا تم إنشاء سلسلة مخطط من خلية نفسها موجودة بالفعل في المجموعة، فإن الطريقة لا تضيف شيئًا وتعيد فهرستها. |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط مضافة أو سلسلة موجودة بالفعل في المجموعة.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

ينشئ سلسلة مخطط جديدة من القيمة ويضيفها إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم السلسلة. |
| type | int | نوع السلسلة |

**الإرجاع:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سلسلة مخطط مضافة.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

يبحث عن [IChartSeries](../../com.aspose.slides/ichartseries) المحدد ويعيد الفهرس الصفري للموقع الأول ضمن Collection بالكامل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | قيمة سلسلة المخطط. |

**الإرجاع:**
int - الفهرس الصفري للموقع الأول للقيمة ضمن CollectionBase بالكامل، إذا وجد؛ وإلا، -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

يزيل القيمة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر (بما في ذلك نمط المخطط) من المجموعة.