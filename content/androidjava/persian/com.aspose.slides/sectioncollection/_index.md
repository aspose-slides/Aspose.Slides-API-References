---
title: SectionCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشی از یک مجموعه از بخش‌ها.
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

Represents a collection of sections. → **نمایش یک مجموعه از بخش‌ها.**

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص‌شده دریافت می‌کند. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | افزودن بخش اسلایدها که از اسلاید خاصی شروع می‌شود. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | افزودن بخش خالی به انتهای مجموعه. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | افزودن بخش خالی به موقعیت مشخص‌شده در مجموعه. |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود است را برمی‌گرداند. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | اندیسی از بخش مشخص‌شده در مجموعه را برمی‌گرداند. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | حذف بخش و اسلایدهای موجود در آن. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | حذف بخش. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | جابه‌جایی بخش و اسلایدهای آن از مجموعه به موقعیت مشخص‌شده. |
| [clear()](#clear--) | حذف تمام بخش‌ها از مجموعه. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از طریق آن می‌توان بر روی مجموعه تکرار کرد را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

عنصر را در اندیس مشخص‌شده دریافت می‌کند. فقط-خواندنی [ISection](../../com.aspose.slides/isection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**مقدار بازگشت:**
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

افزودن بخش اسلایدها که از اسلاید خاصی شروع می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | اولین اسلاید بخش |

**مقدار بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش افزوده‌شده.

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

افزودن بخش خالی به انتهای مجموعه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |

**مقدار بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش افزوده‌شده.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

افزودن بخش خالی به موقعیت مشخص‌شده در مجموعه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام بخش |
| index | int | اندیس بخش جدید. |

**مقدار بازگشت:**
[ISection](../../com.aspose.slides/isection) - بخش افزوده‌شده.

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود است را برمی‌گرداند. فقط-خواندنی int.

**مقدار بازگشت:**
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

ایندکس بخش مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید پیدا شود. |

**مقدار بازگشت:**
int - اندیس بخش یا -1 اگر بخش متعلق به این مجموعه نباشد.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

حذف بخش و اسلایدهای موجود در آن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید از مجموعه حذف شود. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

حذف بخش. اسلایدهای موجود در بخش به بخش قبلی منتقل می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید از مجموعه حذف شود. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

جابه‌جایی بخش و اسلایدهای آن از مجموعه به موقعیت مشخص‌شده.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | بخشی که باید جابه‌جا شود. |
| index | int | اندیس هدف. |

### clear() {#clear--}
```
public final void clear()
```

حذف تمام بخش‌ها از مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف |
| index | int | اندیس در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی‌شده (thread-safe) است یا نه. فقط-خواندنی boolean.

**مقدار بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**مقدار بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

یک enumerator که از طریق آن می‌توان بر روی مجموعه تکرار کرد را برمی‌گرداند.

**مقدار بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - یک IGenericEnumerator که می‌توان برای تکرار بر روی مجموعه از آن استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**مقدار بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - یک java.util.Iterator برای کل مجموعه.