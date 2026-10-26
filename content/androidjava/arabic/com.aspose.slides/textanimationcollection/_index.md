---
title: TextAnimationCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الرسوم المتحركة للنص.
type: docs
url: /ar/com.aspose.slides/textanimationcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

يمثل مجموعة من الرسوم المتحركة للنص.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## الدوال

| طريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد العناصر في المجموعة. |
| [add()](#add--) | يضيف رسمًا متحركًا نصيًا جديدًا إلى المجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع العنصر بواسطة الفهرس. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | إرجاع جميع العناصر |
| [iterator()](#iterator--) | إرجاع مُعدِّد يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع iterator جافا للمجموعة بالكامل. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

إرجاع عدد العناصر في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### add() {#add--}
```
public final TextAnimation add()
```

يضيف رسمًا متحركًا نصيًا جديدًا إلى المجموعة.

**الإرجاع:**
[TextAnimation](../../com.aspose.slides/textanimation) - مضاف [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

إرجاع العنصر بواسطة الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

إرجاع جميع العناصر

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) للإزالة. |

**الإرجاع:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

إرجاع مُعدِّد يمر عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

إرجاع iterator جافا للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة لتعبئتها. |
| index | int | الموضع الابتدائي في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). قراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. قراءة فقط Object.

**الإرجاع:**
java.lang.Object