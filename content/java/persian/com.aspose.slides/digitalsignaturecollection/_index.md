---
title: DigitalSignatureCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر مجموعه‌ای از امضاهای دیجیتال که به یک سند پیوست شده‌اند.
type: docs
url: /fa/com.aspose.slides/digitalsignaturecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

نمایشگر مجموعه‌ای از امضای دیجیتال‌ئی که به یک سند پیوست شده‌اند.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | امضای موجود در ایندکس را برمی‌گرداند. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | امضا را در انتهای مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | امضا را در ایندکس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام امضاها را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه می‌گذرد را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [size()](#size--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهنده این که دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است را برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | ریشه‌ی همگام‌سازی را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه‌ی مشخص‌شده کپی می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

امضای موجود در ایندکس را برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | امضایی که باید اضافه شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

امضا را در ایندکس مشخص حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
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

یک enumerator که از مجموعه می‌گذرد را برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه از آن استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - یک java.util.Iterator برای کل مجموعه.
### size() {#size--}
```
public final int size()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقدار نشان‌دهنده این که دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است را برمی‌گرداند. فقط-خواندنی boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**Returns:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه‌ی مشخص‌شده کپی می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه‌ی هدف. |
| index | int | ایندکس شروع در آرایه‌ی هدف. |