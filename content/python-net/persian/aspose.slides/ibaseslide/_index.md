---
title: IBaseSlide class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ibaseslide/
---
## کلاس IBaseSlide

داده‌های مشترک برای تمام انواع اسلاید را نشان می‌دهد.

نوع IBaseSlide اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/ibaseslide/shapes/) | شکل‌های یک اسلاید را باز می‌گرداند.<br/>            فقط-خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/ibaseslide/controls/) | مجموعهٔ کنترل‌های ActiveX در یک اسلاید را باز می‌گرداند.<br/>            فقط-خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/ibaseslide/name/) | نام یک اسلاید را باز می‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/ibaseslide/slide_id/) | شناسهٔ یک اسلاید را باز می‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/ibaseslide/custom_data/) | داده‌های سفارشی اسلاید را باز می‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/ibaseslide/timeline/) | شیء زمان‌بند انیمیشن را باز می‌گرداند.<br/>            فقط-خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/ibaseslide/slide_show_transition/) | شیء TransitionEx را باز می‌گرداند که شامل اطلاعات دربارهٔ<br/>            نحوه پیشرفت اسلاید مشخص شده در طول نمایش اسلایدها است.<br/>            فقط-خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/ibaseslide/background/) | پس‌زمینهٔ اسلاید را باز می‌گرداند.<br/>            فقط-خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/ibaseslide/hyperlink_queries/) | دسترسی آسان به پیوندهای داخلی را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/ibaseslide/show_master_shapes/) | مشخص می‌کند آیا شکل‌های اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه.<br/>            برای خود اسلاید اصلی این ویژگی همیشه `false` بر می‌گرداند.<br/>            خواندنی/نوشتنی **bool**. |
| [`slide`](/slides/python-net/fa/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/ibaseslide/presentation/) |  |

## متدها

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | اولین رخداد یک شکل با متن جایگزین مشخص شده را پیدا می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | بخش‌های متنی با قالب‌بندی یکسان را در تمامی پاراگراف‌ها در تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/ibaseslide/equals/#ibaseslide) | تعیین می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه.<br/>            مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود.<br/>            دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ منحصر به فرد مانند SlideId و محتوای پویا مانند مقدار تاریخ کنونی در مکان‌دار تاریخ را در نظر نمی‌گیرد. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)