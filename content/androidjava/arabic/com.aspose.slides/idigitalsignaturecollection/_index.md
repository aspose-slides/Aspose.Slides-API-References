---
title: IDigitalSignatureCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل مجموعة من التواقيع الرقمية المرتبطة بمستند.
type: docs
url: /ar/com.aspose.slides/idigitalsignaturecollection/
---
**جميع الواجهات المنفذة:**  
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

يمثل مجموعة من التواقيع الرقمية المرتبطة بمستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يُعيد التوقيع حسب الفهرس. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | يُضيف التوقيع في نهاية المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يُزيل التوقيع عند الفهرس المحدد. |
| [clear()](#clear--) | يُزيل جميع التواقيع من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

يُعيد التوقيع حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

يُضيف التوقيع في نهاية المجموعة.

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
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | التوقيع للإضافة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يُزيل التوقيع عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التوقيع الذي يجب حذفه. |

### clear() {#clear--}
```
public abstract void clear()
```

يُزيل جميع التواقيع من المجموعة.