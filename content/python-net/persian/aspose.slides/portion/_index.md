---
title: Portion class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/portion/
---
## کلاس Portion

یک بخش از متن داخل یک پاراگراف متن را نشان می‌دهد.

نوع Portion اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides/portion/__init__/#) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |
| [`__init__(self, str)`](/slides/python-net/fa/aspose.slides/portion/__init__/#str) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |
| [`__init__(self, portion)`](/slides/python-net/fa/aspose.slides/portion/__init__/#portion) | یک نمونه جدید از کلاس Portion را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`portion_format`](/slides/python-net/fa/aspose.slides/portion/portion_format/) | یک شیء قالب‌بندی را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی به‌صورت صریح تنظیم‌شده برای بخش متن است بدون به‌کارگیری وراثت.<br/>            فقط-خواندنی [`IPortionFormat`](/slides/python-net/fa/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/fa/aspose.slides/portion/text/) | متن ساده یک بخش را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`field`](/slides/python-net/fa/aspose.slides/portion/field/) | یک فیلد از این بخش را برمی‌گرداند.<br/>            فقط-خواندنی [`IField`](/slides/python-net/fa/aspose.slides/ifield). |
| [`slide`](/slides/python-net/fa/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/portion/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/fa/aspose.slides/portion/add_field/#ifieldtype) | این بخش را به فیلد به‌طور خودکار به‌روز شده تبدیل می‌کند. |
| [`add_field(self, internal_string)`](/slides/python-net/fa/aspose.slides/portion/add_field/#str) | این بخش را به فیلد به‌طور خودکار به‌روز شده تبدیل می‌کند. |
| [`remove_field(self)`](/slides/python-net/fa/aspose.slides/portion/remove_field/#) | این بخش فیلد را به بخش ساده تبدیل می‌کند. |
| [`get_rect(self)`](/slides/python-net/fa/aspose.slides/portion/get_rect/#) | مختصات مستطیلی که بخش را محاط می‌کند را دریافت می‌کند. مستطیل شامل تمام خطوط <br/> متن در بخش، از جمله خطوط خالی است. |
| [`get_coordinates(self)`](/slides/python-net/fa/aspose.slides/portion/get_coordinates/#) | مختصات نقطهٔ آغاز بخش را دریافت می‌کند. مختصات X نقطه نشان‌دهندهٔ <br/> آغاز بخش از اولین کاراکتر به همراه فضای سمت چپ است. مختصات Y <br/> شامل فضای سمت بالا است. |

### مراجع
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)