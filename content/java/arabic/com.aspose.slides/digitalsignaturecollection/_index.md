---
title: DigitalSignatureCollection
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides for Java
description: يمثل مجموعة من التوقيعات الرقمية المرفقة بمستند.
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

يمثِّل مجموعة من التوقيعات الرقمية المرفقة بمستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع التوقيع حسب الفهرس. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | إضافة التوقيع في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة التوقيع عند الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع التوقيعات من المجموعة. |
| [iterator()](#iterator--) | إرجاع مُعدد (enumerator) يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع java iterator للمجموعة بأكملها. |
| [size()](#size--) | إرجاع عدد العناصر في المجموعة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |

### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

إرجاع التوقيع حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**  
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)

### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

إضافة التوقيع في نهاية المجموعة.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | التوقيع للإضافة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

إزالة التوقيع عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التوقيع الذي يجب حذفه. |

### clear() {#clear--}
```
public final void clear()
```

إزالة جميع التوقيع من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

إرجاع مُعدد (enumerator) يتكرر عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - IGenericEnumerator يمكن استخدامها للتكرار عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

إرجاع java iterator للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - java.util.Iterator للمجموعة بأكملها.

### size() {#size--}
```
public final int size()
```

إرجاع عدد العناصر في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**  
int

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). boolean للقراءة فقط.

**القيمة المرجعة:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**  
java.lang.Object

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الابتدائي في مصفوفة الهدف. |