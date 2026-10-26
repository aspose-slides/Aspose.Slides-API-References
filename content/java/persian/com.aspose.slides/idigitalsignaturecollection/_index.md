---
title: IDigitalSignatureCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهنده مجموعه‌ای از امضاهای دیجیتال پیوست‌شده به یک سند.
type: docs
url: /fa/com.aspose.slides/idigitalsignaturecollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

نمایشگر مجموعه‌ای از امضای دیجیتال پیوست‌شده به یک سند.
## روش‌ها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | امضا را بر اساس شاخص برمی‌گرداند. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | امضا را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | امضا را در شاخص مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام امضاها را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

امضا را بر اساس شاخص برمی‌گرداند.

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
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | امضا برای افزودن. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

امضا را در شاخص مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص امضایی که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام امضاها را از مجموعه حذف می‌کند.