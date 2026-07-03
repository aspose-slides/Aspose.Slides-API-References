---
title: MasterSlide
second_title: مرجع API Aspose.Sildes برای .NET
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
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را باز می‌گرداند. فقط خواندنی [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | سبک متن بدنه را باز می‌گرداند. فقط خواندنی [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعهٔ کنترل‌های ActiveX روی اسلاید را باز می‌گرداند. فقط خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را باز می‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | مجموعهٔ راهنمای‌های رسم برای اسلاید اصلی را باز می‌گرداند. فقط خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | اگر حداقل یک اسلاید وابسته به این اسلاید اصلی وجود داشته باشد، مقدار true را برمی‌گرداند. فقط خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید اصلی را باز می‌گرداند. فقط خواندنی [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | مجموعهٔ اسلایدهای چیدمان فرزند برای این اسلاید اصلی را باز می‌گرداند. فقط خواندنی [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | نام یک اسلاید اصلی را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | سبک متن دیگری را باز می‌گرداند. فقط خواندنی [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را باز می‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | تعیین می‌کند آیا مستند اصلی مربوطه هنگام حذف تمام اسلایدهای وابسته حذف شود یا خیر. نکته: Aspose.Slides هرگز به‌طور خودکار مستندهای استفاده نشده را حذف نمی‌کند؛ برای حذف واقعی مستندهای استفاده نشده، [`RemoveUnused`](../masterslidecollection/removeunused) را فراخوانی کنید. قابل خواندن/نوشتن Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال یک اسلاید را باز می‌گرداند. فقط خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | تعیین می‌کند آیا اشکال در اسلاید اصلی بر اسلایدهای دیگر نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه مقدار `false` را برمی‌گرداند. قابل خواندن/نوشتن Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسهٔ یک اسلاید را باز می‌گرداند. فقط خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را که شامل اطلاعات دربارهٔ پیشرفت اسلاید در نمایش اسلاید است، باز می‌گرداند. فقط خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | مدیر تم را باز می‌گرداند. فقط خواندنی [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء زمان‌بندی انیمیشن را باز می‌گرداند. فقط خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | سبک متن عنوان را باز می‌گرداند. فقط خواندنی [`ITextStyle`](../itextstyle). |

## متدها

| نام | توضیح |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | یک اسلاید اصلی جدید بر پایهٔ اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید اصلی ساخته شده را به تمام اسلایدهای وابسته اعمال می‌کند. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید باز می‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر پایهٔ ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات برابر باشند. مقایسه مقادیر شناسهٔ یکتا مثل SlideId یا محتوای پویا مثل مقدار تاریخ فعلی در جای‌دار تاریخ را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین وقوع یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید اصلی وابسته هستند، باز می‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | اجرای‌های با همان فرمت‌بندی را در تمام پاراگراف‌ها و تمام اشکال قابل قبول ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | اجرای‌های با همان فرمت‌بندی را در تمام پاراگراف‌ها و تمام اشکال قابل قبول ترکیب می‌کند. |

### موارد مرتبط

* کلاس [BaseSlide](../baseslide)
* رابط [IMasterSlide](../imasterslide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->