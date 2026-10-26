---
title: MasterSlideCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از اسلایدهای اصلی.
type: docs
url: /fa/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

نمایشی از مجموعه اسلایدهای اصلی.
## متدها

| Method | Description |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | اولین رخداد یک شی خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | اسلایدهای اصلی استفاده‌نشده را حذف می‌کند. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید اصلی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید اصلی مشخص‌شده را در موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه‌ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه می‌چرخد را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه وجود دارند را برمی‌گرداند. int فقط‌خواندنی.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند. [MasterSlide](../../com.aspose.slides/masterslide) فقط‌خواندنی.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

اولین رخداد یک شی خاص را از مجموعه حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید اصلی برای حذف از مجموعه. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس صفر مبنا از عنصری که باید حذف شود. |

--------------------

برای جلوگیری از پرتاب PptxEditException قبل از آن ویژگی HasDependingSlides اصلی را بررسی کنید. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

اسلایدهای اصلی استفاده‌نشده را حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | تعیین می‌کند که آیا این متد باید اسلاید اصلی استفاده‌نشده را حتی اگر ویژگی [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) آن روی true تنظیم شده باشد، حذف کند. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

یک نسخه از اسلاید اصلی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. اسلایدهای طرح‌بندی پیوندی نیز کپی می‌شوند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید برای کلون. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید افزوده‌شده.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

یک نسخه از اسلاید اصلی مشخص‌شده را در موقعیت مشخص‌شده در مجموعه وارد می‌کند. اسلایدهای طرح‌بندی پیوندی نیز کپی می‌شوند.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // نمونه‌سازی کلاس Presentation برای بارگذاری فایل ارائه منبع
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // نمونه‌سازی کلاس Presentation برای ارائه مقصد (جایی که اسلاید باید کلون شود)
>      Presentation destPres = new Presentation();
>      try {
>          // نمونه‌سازی ISlide از مجموعه اسلایدها در ارائه منبع همراه با
>          // اسلاید اصلی
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // دریافت اسلایدهای اصلی ارائه مقصد
>          IMasterSlideCollection masters = destPres.getMasters();
>          // کلون اسلاید اصلی موردنظر از ارائه منبع به مجموعه‌ای از اسلایدهای اصلی در
>          // ارائه مقصد
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // مجموعه اسلایدها در ارائه مقصد
>          ISlideCollection slds = destPres.getSlides();
>          // کلون اسلاید منبع به مجموعه اسلایدهای مقصد.
>          slds.addClone(SourceSlide, iSlide, true);
>          // ذخیره ارائه مقصد روی دیسک
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید برای کلون. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اصلی وارد‌شده.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه‌ مشخص‌شده کپی می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (thread-safe). boolean فقط‌خواندنی.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط‌خواندنی.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

یک شمارنده که از طریق مجموعه می‌چرخد را برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - یک java.util.Iterator برای کل مجموعه.