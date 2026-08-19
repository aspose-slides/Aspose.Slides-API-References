---
title: ISectionCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: یک مجموعه از بخش‌ها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/isectioncollection/
---
**تمام واسط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

یک مجموعه از بخش‌ها را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در شاخص مشخص شده قرار دارد دریافت می‌کند. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | بخش جدیدی را که از اسلاید خاصی شروع می‌شود اضافه می‌کند. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | بخش خالی را در موقعیت مشخص شده در مجموعه اضافه می‌کند. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | بخش و اسلایدهای موجود در آن را حذف می‌کند. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | بخش را حذف می‌کند. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | بخش و اسلایدهای آن را از مجموعه به موقعیت مشخص شده منتقل می‌کند. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | بخش خالی را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | شاخص بخشی که مشخص شده در مجموعه را برمی‌گرداند. |
| [clear()](#clear--) | تمام بخش‌ها را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

عنصری را که در شاخص مشخص شده قرار دارد دریافت می‌کند. فقط-خواندنی [ISection](../../com.aspose.slides/isection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

بخش جدیدی را که از اسلاید خاصی شروع می‌شود اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | اولین اسلاید بخش |

**بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شده.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

بخش خالی را در موقعیت مشخص شده در مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| index | int | شاخص بخش جدید. |

**بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شده.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

بخش و اسلایدهای موجود در آن را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که از مجموعه حذف می‌شود. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

بخش را حذف می‌کند. اسلایدهای موجود در بخش به بخش قبلی ادغام می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که از مجموعه حذف می‌شود. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

بخش و اسلایدهای آن را از مجموعه به موقعیت مشخص شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای جابجایی. |
| index | int | شاخص هدف. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

بخش خالی را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |

**بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شده.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

شاخص بخشی که مشخص شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخش برای یافتن. |

**بازگشت:**
int - شاخص بخشی یا -1 اگر بخش از این مجموعه نباشد.
### clear() {#clear--}
```
public abstract void clear()
```

تمام بخش‌ها را از مجموعه حذف می‌کند.