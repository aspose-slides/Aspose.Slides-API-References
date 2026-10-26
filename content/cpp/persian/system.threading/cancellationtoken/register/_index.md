---
title: Register()
second_title: مرجع API Aspose.Slides برای C++
description: یک callback را ثبت می‌کند که هنگام درخواست لغو فراخوانی می‌شود.
type: docs
weight: 40
url: /fa/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const متد

یک callback را ثبت می‌کند که زمانی که لغو درخواست می‌شود، فراخوانی می‌شود.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Action<>ی که در هنگام درخواست لغو باید اجرا شود. |

### مقدار بازگشتی

[CancellationTokenRegistration](../../cancellationtokenregistration/) شیئی که می‌توان برای لغو ثبت callback استفاده کرد.

## نکات

اگر لغو قبلاً درخواست شده باشد، callback بلافاصله فراخوانی می‌شود. 

callback باید کوتاه‌مدت و غیرمسدودکننده باشد زیرا در روی رشته‌ای که Cancel() را روی [CancellationTokenSource](../../cancellationtokensource/) فراخوانی می‌کند، اجرا می‌شود.

## همچنین ببینید

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)