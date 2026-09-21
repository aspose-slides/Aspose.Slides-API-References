---
title: BaseSlide class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/baseslide/
---
## کلاس BaseSlide

داده‌های مشترک برای تمام انواع اسلاید را نشان می‌دهد.

نوع BaseSlide اعضای زیر را در دسترس قرار می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/baseslide/shapes/) | اشکال یک اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/baseslide/controls/) | مجموعه کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/baseslide/name/) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند.<br/>            قابل خواندن/نوشتن **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/baseslide/slide_id/) | شناسه یک اسلاید را برمی‌گرداند.<br/>            فقط خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/baseslide/custom_data/) | داده‌های سفارشی اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/baseslide/timeline/) | شیء زمان‌بندی انیمیشن را برمی‌گرداند.<br/>            فقط خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/baseslide/slide_show_transition/) | شیء Transition را برمی‌گرداند که شامل اطلاعات درباره<br/>            نحوه پیشرفت اسلاید مشخص‌شده در طول ارائه اسلاید است.<br/>            فقط خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/baseslide/background/) | پس‌زمینه اسلاید را برمی‌گرداند.<br/>            فقط خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/baseslide/hyperlink_queries/) | دسترسی آسان به لینک‌های موجود را فراهم می‌کند.<br/>            فقط خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/baseslide/show_master_shapes/) | مشخص می‌کند آیا اشکال روی اسلاید اصلی بر روی اسلایدها نشان داده شود یا خیر.<br/>            برای خود اسلاید اصلی این ویژگی همیشه `false` برمی‌گرداند.<br/>            قابل خواندن/نوشتن **bool**. |
| [`presentation`](/slides/python-net/fa/aspose.slides/baseslide/presentation/) | رابط IPresentation را برمی‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/fa/aspose.slides/baseslide/slide/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/baseslide/join_portions_with_same_formatting/#) | دنباله‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها و تمام اشکال قابل قبول ترکیب می‌کند. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fa/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | دنباله‌ها را با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/baseslide/equals/#ibaseslide) | مشخص می‌کند آیا دو نمونه IBaseSlide برابر هستند یا خیر.<br/>            مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود.<br/>            دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسه یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ جاری در جای‌دار تاریخ را در نظر نمی‌گیرد. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/baseslide/create_theme_effective/#) | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/baseslide/find_shape_by_alt_text/#str) | اولین رخداد یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |


### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)