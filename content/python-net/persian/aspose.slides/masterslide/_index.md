---
title: MasterSlide class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/masterslide/
---
## MasterSlide کلاس

یک اسلاید مستر را در یک ارائه نشان می‌دهد.

**ارث‌بری:**[`MasterSlide`](/slides/python-net/fa/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)

نوع MasterSlide اعضای زیر را در اختیار می‌گذارد:

## خواص

| ویژگی | توضیح |
| :- | :- |
| [`shapes`](/slides/python-net/fa/aspose.slides/masterslide/shapes/) | شکل‌های یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/fa/aspose.slides/masterslide/controls/) | مجموعهٔ کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IControlCollection`](/slides/python-net/fa/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/fa/aspose.slides/masterslide/name/) | نام یک اسلاید مستر را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندن/نوشتن **str**. |
| [`slide_id`](/slides/python-net/fa/aspose.slides/masterslide/slide_id/) | شناسهٔ یک اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`custom_data`](/slides/python-net/fa/aspose.slides/masterslide/custom_data/) | داده‌های سفارشی اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/fa/aspose.slides/masterslide/timeline/) | شیء جدول زمانی انیمیشن را برمی‌گرداند.<br/>            فقط-خواندنی [`IAnimationTimeLine`](/slides/python-net/fa/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/fa/aspose.slides/masterslide/slide_show_transition/) | شیء Transition را برمی‌گرداند که شامل اطلاعات دربارهٔ این است که اسلاید مشخص‌شده چگونه در طول نمایش اسلاید پیش می‌رود.<br/>            فقط-خواندنی [`ISlideShowTransition`](/slides/python-net/fa/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/fa/aspose.slides/masterslide/background/) | پس‌زمینهٔ اسلاید را برمی‌گرداند.<br/>            فقط-خواندنی [`IBackground`](/slides/python-net/fa/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/masterslide/hyperlink_queries/) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/fa/aspose.slides/masterslide/show_master_shapes/) | مشخص می‌کند که آیا شکل‌ها در اسلاید مستر باید در اسلایدها نمایش داده شوند یا نه.<br/>            برای خود اسلاید مستر این ویژگی همیشه `false` را برمی‌گرداند.<br/>            خواندن/نوشتن **bool**. |
| [`presentation`](/slides/python-net/fa/aspose.slides/masterslide/presentation/) | اینترفیس IPresentation را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/fa/aspose.slides/masterslide/header_footer_manager/) | مدیر HeaderFooter اسلاید مستر را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterSlideHeaderFooterManager`](/slides/python-net/fa/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/fa/aspose.slides/masterslide/title_style/) | سبک متن عنوان را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/fa/aspose.slides/masterslide/body_style/) | سبک متن بدنه را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/fa/aspose.slides/masterslide/other_style/) | سبک متن دیگری را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextStyle`](/slides/python-net/fa/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/fa/aspose.slides/masterslide/layout_slides/) | مجموعهٔ اسلایدهای طرح‌بندی فرزند برای این اسلاید مستر را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/fa/aspose.slides/masterslide/preserve/) | تعیین می‌کند که آیا مستر مربوطه هنگام حذف تمام اسلایدهایی که پس از آن مستر هستند حذف می‌شود یا نه.<br/>            نکته: Aspose.Slides هرگز به تنهایی مسترهای استفاده‌نشده را حذف نمی‌کند؛ برای حذف واقعی مسترهای استفاده‌نشده باید **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** را صدا بزنید.<br/>            خواندن/نوشتن **bool**. |
| [`has_depending_slides`](/slides/python-net/fa/aspose.slides/masterslide/has_depending_slides/) | اگر حداقل یک اسلاید که به این اسلاید مستر وابسته است وجود داشته باشد، true برمی‌گرداند.<br/>            فقط-خواندنی **bool**. |
| [`theme_manager`](/slides/python-net/fa/aspose.slides/masterslide/theme_manager/) | مدیر تم را برمی‌گرداند.<br/>            فقط-خواندنی [`IMasterThemeManager`](/slides/python-net/fa/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/fa/aspose.slides/masterslide/drawing_guides/) | مجموعه‌ای از راهنمای‌های رسم برای اسلاید مستر را برمی‌گرداند.<br/>            فقط-خواندنی [`IDrawingGuidesCollection`](/slides/python-net/fa/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/fa/aspose.slides/masterslide/slide/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/masterslide/join_portions_with_same_formatting/#) | دنباله‌های متنی (runs) با فرمت یکسان را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول به هم می‌پیوندد. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/fa/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | دنباله‌های متنی با فرمت یکسان را در تمام پاراگراف‌ها و در تمام شکل‌های قابل قبول به هم می‌پیوندد. |
| [`equals(self, slide)`](/slides/python-net/fa/aspose.slides/masterslide/equals/#ibaseslide) | تعیین می‌کند آیا دو نمونه از IBaseSlide برابر هستند یا خیر.<br/>            مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت آن محاسبه می‌شود.<br/>            دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ جاری در جای‌دار تاریخ را در نظر نمی‌گیرد. |
| [`create_theme_effective(self)`](/slides/python-net/fa/aspose.slides/masterslide/create_theme_effective/#) | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/fa/aspose.slides/masterslide/find_shape_by_alt_text/#str) | اولین رخداد یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/fa/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | یک اسلاید مستر جدید بر اساس اسلاید فعلی ایجاد می‌کند، با تم خارجی بر آن اعمال می‌کند <br/>            و اسلاید مستر ساخته‌شده را به تمام اسلایدهای وابسته اعمال می‌نماید. |
| [`get_depending_slides(self)`](/slides/python-net/fa/aspose.slides/masterslide/get_depending_slides/#) | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید مستر وابسته هستند را برمی‌گرداند. |

### موارد مرتبط
* کلاس [`BaseSlide`](/slides/python-net/fa/aspose.slides/baseslide)
* کلاس [`MasterSlide`](/slides/python-net/fa/aspose.slides/masterslide)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)