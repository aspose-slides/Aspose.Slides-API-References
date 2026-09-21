---
title: ExternalResourceResolver class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver کلاس

کلاس Callback که برای حل منابع خارجی هنگام واردات اسناد Html و Svg استفاده می‌شود.  
استفاده از این resolver می‌تواند یک آسیب‌پذیری ایجاد کند وقتی فایلی HTML یا SVG توسط کلاینت فراهم می‌شود و باعث می‌شود نرم‌افزار سرور به فایل‌های محلی یا شبکه‌ای دسترسی پیدا کند. با احتیاط استفاده کنید. توصیه می‌شود به‌هیچ‌وجه ExternalResourceResolver را مشخص نکنید (فقط اشیای جاسازی‌شده خوانده می‌شوند) یا یک زیرکلاس ایجاد کنید که بررسی کند آیا uri مشخص شده معتبر است.

نوع ExternalResourceResolver اعضای زیر را فراهم می‌کند:

## سازنده‌ها

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/fa/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | URI مطلق را از URIهای پایه و نسبی حل می‌کند. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/fa/aspose.slides.importing/externalresourceresolver/get_entity/#str) | URI را به شیئی که منبع واقعی را شامل می‌شود نگاشت می‌کند. |

### ارجاعات
* ماژول [`aspose.slides.importing`](/slides/python-net/fa/aspose.slides.importing)
* کتابخانه [`Aspose.Slides`](/slides/python-net)