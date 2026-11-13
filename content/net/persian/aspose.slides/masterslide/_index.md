---
title: MasterSlide
second_title: Aspose.Sildes برای مرجع API .NET
description: یک اسلاید مستر را در یک ارائه نشان می‌دهد.
type: docs
weight: 8050
url: /fa/aspose.slides/masterslide/
---
## MasterSlide کلاس

یک اسلاید مستر را در یک ارائه نشان می‌دهد.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط‌خواندنی [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | سبک متن بدنه را برمی‌گرداند. فقط‌خواندنی [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعهٔ کنترل‌های ActiveX روی اسلاید را برمی‌گرداند. فقط‌خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | مجموعهٔ خطوط راهنما برای اسلاید مستر را برمی‌گرداند. فقط‌خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | اگر حداقل یک اسلاید که به این اسلاید مستر وابسته باشد وجود داشته باشد، true برمی‌گرداند. فقط‌خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید مستر را برمی‌گرداند. فقط‌خواندنی [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط‌خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | مجموعهٔ اسلایدهای طرح‌بندی فرزند برای این اسلاید مستر را برمی‌گرداند. فقط‌خواندنی [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | نام یک اسلاید مستر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | سبک متن دیگری را برمی‌گرداند. فقط‌خواندنی [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | اینترفیس IPresentation را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | مشخص می‌کند آیا مستر متناظر زمانی حذف می‌شود که تمام اسلایدهای پیرو آن مستر حذف شوند. توجه: Aspose.Slides هرگز به‌صورت خودکار مسترهای استفاده نشده را حذف نمی‌کند؛ برای حذف واقعی مسترهای استفاده نشده، [`RemoveUnused`](../masterslidecollection/removeunused) را صدا بزنید. خواندنی/نوشتنی Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | شکل‌های یک اسلاید را برمی‌گرداند. فقط‌خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | مشخص می‌کند آیا شکل‌ها در اسلاید مستر باید بر روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید مستر این ویژگی همیشه `false` برمی‌گرداند. خواندنی/نوشتنی Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه (ID) یک اسلاید را برمی‌گرداند. فقط‌خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را برمی‌گرداند که اطلاعاتی دربارهٔ پیشرفت اسلاید مشخص در طول ارائه اسلایدها دارد. فقط‌خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | مدیر تم را برمی‌گرداند. فقط‌خواندنی [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء زمانبندی انیمیشن را برمی‌گرداند. فقط‌خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | سبک متن عنوان را برمی‌گرداند. فقط‌خواندنی [`ITextStyle`](../itextstyle). |

## متدها

| نام | توضیح |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | یک اسلاید مستر جدید بر پایهٔ اسلاید فعلی ایجاد می‌کند، تم خارجی را به آن اعمال می‌نماید و اسلاید مستر ساخته‌شده را به تمام اسلایدهای وابسته اعمال می‌کند. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | تم مؤثری برای این اسلاید را برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و ... برابر باشند. مقایسه مقادیر شناسایی منحصر به فرد مانند SlideId و محتوای دینامیک مانند مقدار تاریخ جاری در جای‌دار تاریخ را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | یک آرایه شامل تمام اسلایدهایی که به این اسلاید مستر وابسته‌اند را برمی‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول ترکیب می‌کند. |

### همچنین ببینید

* کلاس [BaseSlide](../baseslide)
* اینترفیس [IMasterSlide](../imasterslide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->