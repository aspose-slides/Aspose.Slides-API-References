---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل خصائص التوقيت لسلوك التأثير.
type: docs
url: /ar/com.aspose.slides/ibehaviorpropertycollection/
---
**جميع الواجهات التي تم تنفيذها:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

يمثل خصائص التوقيت لسلوك التأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | تضيف خاصية جديدة إلى المجموعة. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | تحدد فهرس العنصر المحدد بقيمة الخاصية في القائمة. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | تُدرج خاصية جديدة (بقيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد. |
| [remove(String propertyValue)](#remove-java.lang.String-) | تزيل الخاصية المحددة من المجموعة. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

تضيف خاصية جديدة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية للإضافة. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

تحدد فهرس العنصر المحدد بقيمة الخاصية في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية |

**الإرجاع:**
int - فهرس الخاصية ذات القيمة المحددة

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

تُدرج خاصية جديدة (بقيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدراج خاصية جديدة. |
| propertyValue | java.lang.String | قيمة الخاصية للإضافة. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

تزيل الخاصية المحددة من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية للإزالة. |

**الإرجاع:**
boolean - true إذا تم حذف الخاصية بنجاح boolean

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

تحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية للعثور عليها في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - true إذا تم العثور على propertyValue في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.