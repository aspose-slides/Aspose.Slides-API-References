---
title: TextAnimationCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من الرسوم المتحركة للنص.
type: docs
url: /ar/com.aspose.slides/textanimationcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

يمثل مجموعة من الرسوم المتحركة للنص.

## المنشئين

| المنشئ | الوصف |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد العناصر في المجموعة. |
| [add()](#add--) | يضيف رسماً متحركاً نصياً جديداً إلى المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد العنصر حسب الفهرس. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | يعيد جميع العناصر |
| [iterator()](#iterator--) | يعيد عدّاً يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرِّراً جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

يعيد عدد العناصر في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int
### add() {#add--}
```
public final TextAnimation add()
```

يضيف رسماً متحركاً نصياً جديداً إلى المجموعة.

**القيمة المرجعة:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

يعيد العنصر حسب الفهرس.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

يعيد جميع العناصر

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) لإزالة. |

**القيمة المرجعة:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

يعيد عدّاً يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator الذي يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

يعيد مكرِّراً جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة لتعبئتها. |
| index | int | الموضع الابتدائي في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (آمن للخيوط). boolean للقراءة فقط.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object