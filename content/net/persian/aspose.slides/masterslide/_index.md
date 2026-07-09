---
title: MasterSlide
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایانگر یک اسلاید اصلی در یک ارائه است.
type: docs
weight: 8030
url: /fa/aspose.slides/masterslide/
---
## MasterSlide کلاس

نمایانگر یک اسلاید اصلی در یک ارائه است.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را بر می‌گرداند. فقط-خواندنی [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | سبک متن بدنه را بر می‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعه‌ای از کنترل‌های ActiveX روی اسلاید را بر می‌گرداند. فقط-خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را بر می‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید اصلی را بر می‌گرداند. فقط-خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | در صورتی که حداقل یک اسلاید وابسته به این اسلاید اصلی وجود داشته باشد، مقدار true را بر می‌گرداند. فقط-خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید اصلی را بر می‌گرداند. فقط-خواندنی [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | مجموعه‌ای از اسلایدهای چیدمان فرزند برای این اسلاید اصلی را بر می‌گرداند. فقط-خواندنی [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | نام یک اسلاید اصلی را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | سبک متن دیگری را بر می‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را بر می‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | تعیین می‌کند آیا اسلاید اصلی مربوطه هنگام حذف تمام اسلایدهایی که پس از آن می‌آیند حذف می‌شود یا نه. توجه: Aspose.Slides هرگز به تنهایی اسلاید اصلی استفاده‌نشده‌ای را حذف نمی‌کند؛ برای حذف واقعی اسلایدهای اصلی استفاده‌نشده، [`RemoveUnused`](../masterslidecollection/removeunused) را فراخوانی کنید. خواندنی/قابل نوشتن Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال یک اسلاید را بر می‌گرداند. فقط-خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه `false` را بر می‌گرداند. خواندنی/قابل نوشتن Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه (ID) یک اسلاید را بر می‌گرداند. فقط-خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition که حاوی اطلاعاتی درباره نحوه پیشرفت اسلاید مشخص شده در هنگام نمایش اسلایدها است را بر می‌گرداند. فقط-خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | مدیر تم را بر می‌گرداند. فقط-خواندنی [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء animation timeline را بر می‌گرداند. فقط-خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | سبک متن عنوان را بر می‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |

## متدها

| نام | توضیح |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | یک اسلاید اصلی جدید بر پایه اسلاید فعلی ایجاد می‌کند، یک تم خارجی را بر آن اعمال می‌نماید و اسلاید اصلی ایجاد شده را به همه اسلایدهای وابسته اعمال می‌کند. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید را بر می‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و … برابر باشند. مقایسه مقادیر شناسهٔ یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در جای‌نگهدار تاریخ را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد یک شکل با متن جایگزین مشخص شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | یک آرایه شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته‌اند را بر می‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | قطعات متنی (runs) با فرمت یکسان در تمام پاراگراف‌های تمام اشکال قابل قبول را ادغام می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | قطعات متنی (runs) با فرمت یکسان در تمام پاراگراف‌های تمام اشکال قابل قبول را ادغام می‌کند. |

### موارد مرتبط

* کلاس [BaseSlide](../baseslide)
* رابط [IMasterSlide](../imasterslide)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->