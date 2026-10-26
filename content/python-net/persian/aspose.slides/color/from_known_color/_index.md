---
title: from_known_color method
second_title: Aspose.Slides برای پایتون از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
یک رنگ را از رنگ پیش‌تعریف‌شدهٔ مشخص‌شده ایجاد می‌کند.<br/>این تنها راه برای به‌دست آوردن یک رنگ سیستم (مانند `KnownColor.CONTROL`) است: رنگ‌های سیستم به عنوان ویژگی‌های `Color` در دسترس نیستند زیرا مقادیر آن‌ها به تم دسکتاپ وابسته است، بنابراین از زمان اجرای کتابخانه خوانده می‌شوند.

### بازگشت

رنگی که این متد ایجاد می‌کند.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| known_color | **KnownColor** | یک عنصر از شمارندهٔ `KnownColor` (یک `IntEnum` که .NET `System.Drawing.KnownColor` را بازتاب می‌دهد) یا مقدار عددی آن. |

### استثناها

| Exception | Description |
| :- | :- |
| **ValueError** | مقدار یک عضو معتبر `KnownColor` نیست. |



### موارد مرتبط
* کلاس [`Color`](/slides/python-net/fa/aspose.slides/color)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)