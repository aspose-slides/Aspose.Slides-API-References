---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل خصائص التوقيت لسلوك التأثير.
type: docs
url: /ar/com.aspose.slides/ibehaviorpropertycollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

يمثل خصائص التوقيت لسلوك التأثير.
## الأساليب

| الدالة | الوصف |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | يضيف خاصية جديدة إلى المجموعة. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | يحدد فهرس عنصر معين بقيمة الخاصية في القائمة. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | يدخل خاصية جديدة (بقيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد. |
| [remove(String propertyValue)](#remove-java.lang.String-) | يزيل الخاصية المحددة من المجموعة. |
| [contains(String propertyValue)](#contains-java.lang.String-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


يضيف خاصية جديدة إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إضافتها. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


يحدد فهرس عنصر معين بقيمة الخاصية في القائمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية |

**الإرجاع:**
int - فهرس الخاصية ذات القيمة المحددة
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


يدخل خاصية جديدة (بقيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدخال خاصية جديدة. |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إضافتها. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


يزيل الخاصية المحددة من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إزالتها. |

**الإرجاع:**
boolean - صحيح إذا تم إزالة الخاصية بنجاح boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية للعثور عليها في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - صحيح إذا تم العثور على propertyValue في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا، خطأ.