---
title: DigitalSignatureCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک مجموعه از امضاهای دیجیتال پیوست‌شده به سند را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/digitalsignaturecollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

یک مجموعه از امضاهای دیجیتال پیوست‌شده به سند را نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | امضای با ایندکس را برمی‌گرداند. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | امضا را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | امضا را در ایندکس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام امضاها را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [size()](#size--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان‌دهنده این است که دسترسی به مجموعه همگام‌سازی شده ( thread-safe ) است. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه همگام‌سازی را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

امضای با ایندکس را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
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
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | امضا برای افزودن. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

امضا را در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس امضایی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام امضاها را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - یک IGenericEnumerator که می‌توان از آن برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - یک java.util.Iterator برای کل مجموعه.
### size() {#size--}
```
public final int size()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده ( thread-safe ) است. فقط خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | ایندکس شروع در آرایهٔ هدف. |