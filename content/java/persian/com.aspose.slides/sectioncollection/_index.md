---
title: SectionCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایندهٔ مجموعه‌ای از بخش‌ها.
type: docs
url: /fa/com.aspose.slides/sectioncollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)  
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

نمایش‌دهندهٔ مجموعه‌ای از بخش‌ها.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص قرار دارد دریافت می‌کند. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | بخش اسلایدها را که از اسلاید خاصی شروع می‌شود اضافه می‌کند. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | بخش خالی را به انتهای مجموعه اضافه می‌کند. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | بخش خالی را در موقعیت مشخص شده از مجموعه اضافه می‌کند. |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | اندیس بخش مشخص‌شده در مجموعه را برمی‌گرداند. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | بخش و اسلایدهای موجود در آن را حذف می‌کند. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | بخش را حذف می‌کند. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | بخش و اسلایدهای آن را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. |
| [clear()](#clear--) | تمام بخش‌ها را از مجموعه حذف می‌کند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (ایمن برای چندین رشته) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک مرورگر جاوا برای کل مجموعه را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

عنصری را که در ایندکس مشخص قرار دارد دریافت می‌کند. فقط‌خواندنی [ISection](../../com.aspose.slides/isection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

بخش اسلایدها را که از اسلاید خاصی شروع می‌شود اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | اولین اسلاید بخش |

**باز می‌گرداند:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شد.

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

بخش خالی را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |

**باز می‌گرداند:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شد.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

بخش خالی را در موقعیت مشخص شده از مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| index | int | ایندکس بخش جدید. |

**باز می‌گرداند:**
[ISection](../../com.aspose.slides/isection) - بخش اضافه شد.

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. فقط‌خواندنی int.

**باز می‌گرداند:**
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

اندیس بخش مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید پیدا شود. |

**باز می‌گرداند:**
int - اندیس یک بخش یا -1 اگر بخش از این مجموعه نباشد.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

بخش و اسلایدهای موجود در آن را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید از مجموعه حذف شود. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

بخش را حذف می‌کند. اسلایدهای موجود در بخش به بخش قبلی ادغام خواهند شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید از مجموعه حذف شود. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

بخش و اسلایدهای آن را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید منتقل شود. |
| index | int | ایندکس هدف. |

### clear() {#clear--}
```
public final void clear()
```

تمام بخش‌ها را از مجموعه حذف می‌کند.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف |
| index | int | ایندکس در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (ایمن برای چندین رشته) است یا نه. فقط‌خواندنی boolean.

**باز می‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**باز می‌گرداند:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - یک IGenericEnumerator که می‌توان از آن برای پیمایش مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

یک مرورگر جاوا برای کل مجموعه را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - یک java.util.Iterator برای کل مجموعه.