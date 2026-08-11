---
title: Handle()
second_title: مرجع API Aspose.Slides برای C++
description: یک تابع پردازشگر را برای هر استثنای داخلی فراخوانی می‌کند و هر استثنای بدون پردازش را مجدداً پرتاب می‌نماید.
type: docs
weight: 66
url: /fa/system/details_aggregateexception/handle/
---
## جزئیات_AggregateException::Handle(const Func\<Exception, bool\>\&) متد

یک تابع پردازشگر را بر روی هر استثنای داخلی فراخوانی می‌کند و هر استثنای بدون پردازش را مجدداً پرتاب می‌نماید.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | توابعی که یک Exception می‌گیرد و در صورتی که پردازش شده باشد true بر می‌گرداند. |

## توضیحات

اگر تمام استثناها پردازش شوند، متد به‌طور عادی بازمی‌گردد؛ در غیر این صورت، یک AggregateException جدید که حاوی استثناهای بدون پردازش است پرتاب می‌شود.

## موارد مرتبط

* typedef [Exception](../../exception/)
* کلاس [Func](../../func/)
* کلاس [Details_AggregateException](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)