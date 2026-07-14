---
title: IMasterSlideCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده یک مجموعه از مستر اسلایدها.
type: docs
url: /fa/com.aspose.slides/imasterslidecollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

نمایش‌دهنده یک مجموعه از مستر اسلایدها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | مستر اسلایدهای استفاده نشده را حذف می‌کند. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | یک کپی از مستر اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | یک کپی از مستر اسلاید مشخص‌شده را به موقعیت مشخص‌شده در مجموعه وارد می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


عنصر را در ایندکس مشخص‌شده دریافت می‌کند. فقط خواندنی [IMasterSlide](../../com.aspose.slides/imasterslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**برگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلایدی که باید از مجموعه حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-محور عنصری که باید حذف شود. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


مستر اسلایدهای استفاده نشده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ignorePreserveField | boolean | تعیین می‌کند که آیا این متد باید مسترهای استفاده نشده را حذف کند حتی اگر ویژگی [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) آن روی true تنظیم شده باشد. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


یک کپی از مستر اسلاید مشخص‌شده را به انتهای مجموعه اضافه می‌کند. اسلایدهای چیدمان مرتبط نیز کپی می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید برای تکثیر. |

**برگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اضافه‌شده.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


یک کپی از مستر اسلاید مشخص‌شده را به موقعیت مشخص‌شده در مجموعه وارد می‌کند. اسلایدهای چیدمان مرتبط نیز کپی می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید برای تکثیر. |

**برگرداندن:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - مستر اسلاید وارد شده.