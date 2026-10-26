---
title: MasterSlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک مجموعه از اسلایدهای اصلی.
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

نمایانگر مجموعه‌ای از اسلایدهای اصلی.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Removes unused master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified master slide to the end of the collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserts a copy of a specified master slide to specified position of the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود است را برمی‌گرداند. int فقط خواندنی.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

عنصری را در ایندکس مشخص شده برمی‌گرداند. [MasterSlide](../../com.aspose.slides/masterslide) فقط خواندنی.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**مقدار بازگشتی:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

اولین رخداد یک شیء مشخص را از مجموعه حذف می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید اصلی که باید از مجموعه حذف شود. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص‌شده را از مجموعه حذف می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنا برای حذف عنصر. |

--------------------

برای جلوگیری از پرتاب استثنای PptxEditException، قبل از آن ویژگی HasDependingSlides استاد را بررسی کنید. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

اسلایدهای اصلی استفاده‌نشده را حذف می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ignorePreserveField | boolean | تعیین می‌کند آیا این متد باید اسلایدهای اصلی استفاده‌نشده را حتی اگر ویژگی [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) آن به true تنظیم شده باشد، حذف کند. |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

یک کپی از اسلاید اصلی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. اسلایدهای طرح‌بندی پیوند‌شده نیز کپی می‌شوند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلایدی که باید کلون شود. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اضافه‌شده.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

یک کپی از اسلاید اصلی مشخص‌شده را در موقعیت مشخص‌شده از مجموعه وارد می‌کند. اسلایدهای طرح‌بندی پیوند‌شده نیز کپی می‌شوند.

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
>          // کلون اسلاید اصلی موردنظر از ارائه منبع به مجموعه اسلایدهای اصلی در
>          // ارائه مقصد
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // مجموعه‌ای از اسلایدها در ارائه مقصد
>          ISlideCollection slds = destPres.getSlides();
>          // کلون اسلاید منبع به مجموعه اسلایدهای مقصد.
>          slds.addClone(SourceSlide, iSlide, true);
>          // ذخیرهٔ ارائه مقصد روی دیسک
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلایدی که باید کلون شود. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اصلی وارد‌شده.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | ایندکس شروع در آرایهٔ هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (Thread-safe) است. boolean فقط خواندنی.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط خواندنی.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

یک Enumerator که مجموعه را پیمایش می‌کند را برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.