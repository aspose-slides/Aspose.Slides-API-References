---
title: EffectStyleCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل مجموعة من أنماط التأثير.
type: docs
url: /ar/com.aspose.slides/effectstylecollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)  
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

يمثل مجموعة من أنماط التأثير.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع العنصر في الموضع المحدد. |
| [iterator()](#iterator--) | يرجع عددًا مكرِّرًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّر java للمجموعة بأكملها. |
| [size()](#size--) | يرجع عدد العناصر في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |

### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

يرجع العنصر في الموضع المحدد. للقراءة فقط [EffectStyle](../../com.aspose.slides/effectstyle).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | موضع العنصر. |

**القيمة المرجعة:**  
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - العنصر في الموضع المحدد.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

يرجع عددًا مكرِّرًا يتنقل عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - عدد مكرِّر IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

يرجع مكرِّر java للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - java.util.Iterator للمجموعة بأكملها.

### size() {#size--}
```
public final int size()
```

يرجع عدد العناصر في المجموعة. للقراءة فقط int، للقراءة فقط int.

**القيمة المرجعة:**  
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**القيمة المرجعة:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. للقراءة فقط Object.

**القيمة المرجعة:**  
java.lang.Object