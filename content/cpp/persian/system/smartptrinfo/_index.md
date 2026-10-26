---
title: SmartPtrInfo
second_title: مرجع API Aspose.Slides برای C++
description: کلاس سرویس برای آزمایش و تغییر محتویات SmartPtr بدون دانستن نوع نهایی. برای جمع‌آوری زباله و تشخیص حلقه‌های ارجاعی، و غیره استفاده می‌شود. آن را به‌عنوان 'pointer to pointer' در نظر بگیرید. نمی‌توانیم از basetype SmartPtr استفاده کنیم چون هیچکدام ندارد؛ در عوض، از این کلاس 'info' استفاده می‌کنیم.
type: docs
weight: 1249
url: /fa/system/smartptrinfo/
---
## کلاس SmartPtrInfo

کلاس سرویس برای آزمایش و تغییر محتویات [SmartPtr](../smartptr/) بدون دانستن نوع نهایی. برای جمع‌آوری زباله و تشخیص حلقه‌های ارجاعی، و غیره استفاده می‌شود. آن را به‌عنوان 'pointer to pointer' در نظر بگیرید. نمی‌توانیم از basetype [SmartPtr](../smartptr/) استفاده کنیم زیرا هیچ‌کدام ندارد؛ در عوض، از این کلاس 'info' استفاده می‌کنیم.

```cpp
class SmartPtrInfo
```

## متدها

| Method | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | دریافت شیء خامی که اشاره‌گر مرجع به آن اشاره می‌کند. |
| [Object](../object/) * [getObject](./getobject/)() const | دریافت شیء‌ای که اشاره‌گر مرجع به آن اشاره می‌کند. |
| [Object](../object/) * [getOwned](./getowned/)() const | دریافت اشاره‌گر مالک شیء. |
|  [operator bool](./operator_bool/)() const | بررسی می‌کند که آیا شیء info به اشاره‌گر غیر تهی اشاره می‌کند یا نه. |
| **bool** [operator!](./operator_not/)() const | بررسی می‌کند که آیا شیء info به اشاره‌گر غیر تهی اشاره نمی‌کند. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | اجازه می‌دهد متدهای [Object](../object/) که توسط اشاره‌گر مرجع اشاره می‌شود، فراخوانی شوند. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | مقادیر اشاره‌گرهای مرجع توسط دو شیء info را به صورت کمتر مقایسه می‌کند. |
|  [SmartPtrInfo](./smartptrinfo/)() | یک شیء خالی [SmartPtrInfo](./) ایجاد می‌کند. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | شیء [SmartPtrInfo](./) را با اطلاعات در مورد اشاره‌گر هوشمند خاصی ایجاد می‌کند. |

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)