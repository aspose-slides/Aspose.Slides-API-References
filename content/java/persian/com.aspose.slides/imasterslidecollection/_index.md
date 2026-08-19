---
title: IMasterSlideCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایشی از مجموعه‌ای از اسلایدهای اصلی.
type: docs
url: /fa/com.aspose.slides/imasterslidecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

نمایشی از مجموعه‌ای از اسلایدهای اصلی.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در شاخص مشخص شده است دریافت می‌کند. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در شاخص مشخص شده از مجموعه است حذف می‌کند. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | اسلایدهای اصلی استفاده‌نشده را حذف می‌کند. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید اصلی مشخص شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید اصلی مشخص شده را در موقعیت مشخص شده از مجموعه وارد می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

عنصری را که در شاخص مشخص شده است دریافت می‌کند. فقط-خواندنی [IMasterSlide](../../com.aspose.slides/imasterslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید اصلی که باید از مجموعه حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصری را که در شاخص مشخص شده از مجموعه است حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-پایه عنصر برای حذف. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

اسلایدهای اصلی استفاده‌نشده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ignorePreserveField | boolean | تعیین می‌کند که آیا این روش باید اسلایدهای اصلی استفاده‌نشده را حتی اگر ویژگی [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) آن روی true تنظیم شده باشد حذف کند. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

یک نسخه از اسلاید اصلی مشخص شده را به انتهای مجموعه اضافه می‌کند. اسلایدهای طرح‌بندی پیوند شده نیز کپی می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلایدی برای کلون کردن. |

**باز می‌گرداند:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اضافه شده.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

یک نسخه از اسلاید اصلی مشخص شده را در موقعیت مشخص شده از مجموعه وارد می‌کند. اسلایدهای طرح‌بندی پیوند شده نیز کپی می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص اسلاید جدید. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلایدی برای کلون کردن. |

**باز می‌گرداند:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - اسلاید اصلی وارد شده.