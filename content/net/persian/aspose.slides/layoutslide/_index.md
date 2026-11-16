---
title: LayoutSlide
second_title: Aspose.Sildes برای .NET مرجع API
description: یک اسلاید طرح‌بندی را نشان می‌دهد.
type: docs
weight: 7660
url: /fa/aspose.slides/layoutslide/
---
## کلاس LayoutSlide

یک اسلاید چیدمان را نشان می‌دهد.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعه کنترل‌های ActiveX روی اسلاید را برمی‌گرداند. فقط خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | مجموعه راهنمای‌های رسم برای اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | در صورتی که حداقل یک اسلاید که به این اسلاید چیدمان وابسته باشد، true را برمی‌گرداند. فقط خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | نوع چیدمان این اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | اسلاید اصلی برای یک چیدمان را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن و نوشتن String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | مدیر جای‌دارهای اسلاید چیدمان را برمی‌گرداند. فقط خواندنی [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را برمی‌گرداند. فقط خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | شکل‌های یک اسلاید را برمی‌گرداند. فقط خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | مشخص می‌کند که آیا شکل‌های اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. قابل خواندن و نوشتن Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه یک اسلاید را برمی‌گرداند. فقط خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را برمی‌گرداند که شامل اطلاعات درباره چگونگی پیشرفت اسلاید مشخص شده در طول نمایش اسلاید است. فقط خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | مدیر تم حاکم را برمی‌گرداند. فقط خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء animation timeline را برمی‌گرداند. فقط خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند که آیا دو نمونه IBaseSlide برابر هستند یا نه. مقدار بازگردانده شده بر اساس ساختار اسلاید و محتوای استاتیک محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسه‌های یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در Date Placeholder را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد یک شکل با متن جایگزین مشخص شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید چیدمان وابسته هستند را برمی‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | دنباله‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام شکل‌های قابل قبول، ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | دنباله‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [Remove](../../aspose.slides/layoutslide/remove)() | چیدمان را از ارائه حذف می‌کند. |

### مراجع

* کلاس [BaseSlide](../baseslide)
* رابط [ILayoutSlide](../ilayoutslide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->