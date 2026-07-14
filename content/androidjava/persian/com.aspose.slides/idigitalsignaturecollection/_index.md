---
title: IDigitalSignatureCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از امضاهای دیجیتال پیوست‌شده به یک سند است.
type: docs
url: /fa/com.aspose.slides/idigitalsignaturecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

نمایانگر مجموعه‌ای از امضاهای دیجیتال پیوست‌شده به یک سند است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | امضا را بر اساس اندیس برمی‌گرداند. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | امضا را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | امضا را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام امضاها را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

امضا را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

امضا را در انتهای مجموعه اضافه می‌کند.

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | امضایی برای افزودن. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

امضا را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس امضایی که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام امضاها را از مجموعه حذف می‌کند.