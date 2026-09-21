---
title: InterruptionToken class
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/interruptiontoken/
---
## InterruptionToken کلاس

این کلاس نمایانگر توکنی است که برای اعلام به کارهای طولانی مدت استفاده می‌شود تا مشخص شود آیا قطع درخواست شده است یا خیر.

نوع InterruptionToken اعضای زیر را فراهم می‌کند:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`none`](/slides/python-net/fa/aspose.slides/interruptiontoken/none/) | نمایانگر یک توکن قطع‌سازی خالی است.<br/>            عملیات طولانی مدت هیچ‌گاه از طریق [`InterruptionTokenSource.interrupt`](/slides/python-net/fa/aspose.slides/interruptiontokensource/interrupt)<br/>            هنگام استفاده از این توکن قطع نخواهد شد. |
| [`is_interruption_requested`](/slides/python-net/fa/aspose.slides/interruptiontoken/is_interruption_requested/) | در صورتی که قطع درخواست شده باشد **bool**.true را برمی‌گرداند. |

## متدها

| Method | Description |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/fa/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | اگر قطع درخواست شده باشد، یک OperationCanceledException پرتاب می‌کند.<br/>            |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)