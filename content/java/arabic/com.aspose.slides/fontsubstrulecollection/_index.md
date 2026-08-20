---
title: FontSubstRuleCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من استبدالات الخطوط.
type: docs
url: /ar/com.aspose.slides/fontsubstrulecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

يمثل مجموعة من استبدالات الخطوط.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | يضيف قاعدة استبدال الخط الجديدة إلى المجموعة |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | يزيل الظهور الأول لكائن معين من المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [iterator()](#iterator--) | يعيد عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر java للمجموعة بالكامل. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن من التعارض). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


يحصل على عدد العناصر الموجودة فعليًا في المجموعة. عدد صحيح للقراءة فقط.

**الإرجاع:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


يضيف قاعدة استبدال الخط الجديدة إلى المجموعة

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


يزيل الظهور الأول لكائن معين من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | قاعدة استبدال الخط لإزالتها من المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


يحصل على العنصر عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


يعيد عدّادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


يعيد مكرّر java للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


يعيد قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة مُزامنًا (آمن من التعارض). قيمة منطقية للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


يعيد جذر المزامنة. كائن للقراءة فقط.

**الإرجاع:**
java.lang.Object