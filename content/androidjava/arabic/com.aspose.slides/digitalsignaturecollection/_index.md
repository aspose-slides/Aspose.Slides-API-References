---
title: DigitalSignatureCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API Java
description: يمثل مجموعة من التوقيعات الرقمية المرفقة بوثيقة.
type: docs
url: /ar/com.aspose.slides/digitalsignaturecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

يمثل مجموعة من التوقيعات الرقمية المرفقة بوثيقة.
## الطرق

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تُعيد التوقيع حسب الفهرس. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | يضيف التوقيع في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل التوقيع عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع التوقيعات من المجموعة. |
| [iterator()](#iterator--) | تُعيد عدّادًا يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | تُعيد java iterator للمجموعة بأكملها. |
| [size()](#size--) | تُعيد عدد العناصر في المجموعة. |
| [isSynchronized()](#isSynchronized--) | تُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | تُعيد جذر المزامنة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تنسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


تُعيد التوقيع حسب الفهرس.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```


يضيف التوقيع في نهاية المجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | التوقيع للإضافة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


يزيل التوقيع عند الفهرس المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس التوقيع الذي يجب حذفه. |

### clear() {#clear--}
```
public final void clear()
```


يزيل جميع التوقيعات من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


تُعيد عدّادًا يتكرر عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - مُعداد IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


تُعيد java iterator للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - java.util.Iterator للمجموعة بأكملها.
### size() {#size--}
```
public final int size()
```


تُعيد عدد العناصر في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


تُعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). boolean للقراءة فقط.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


تُعيد جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تنسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |