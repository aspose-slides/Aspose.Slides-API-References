---
title: LayoutSlide
second_title: مرجع API Aspose.Sildes برای .NET
description: یک اسلاید طرح‌بندی را نشان می‌دهد.
type: docs
weight: 7640
url: /fa/aspose.slides/layoutslide/
---
## LayoutSlide کلاس

یک اسلاید طرح‌بندی را نشان می‌دهد.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعهٔ کنترل‌های ActiveX موجود در اسلاید را برمی‌گرداند. فقط-خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | مجموعه‌ای از راهنمایی‌های ترسیم برای اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | در صورتی که حداقل یک اسلاید وابسته به این اسلاید طرح‌بندی وجود داشته باشد true برمی‌گرداند. فقط-خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | نوع طرح‌بندی این اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | اسلاید اصلی برای یک طرح‌بندی را برمی‌گرداند یا تنظیم می‌کند. قابل-نوشتن [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل-نوشتن String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | مدیر جای‌گیرها (placeholder) اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | رابط IPresentation را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال یک اسلاید را برمی‌گرداند. فقط-خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | مشخص می‌کند که آیا اشکال روی اسلاید اصلی باید روی اسلایدها نشان داده شود یا نه. قابل-نوشتن Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسهٔ یک اسلاید را برمی‌گرداند. فقط-خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition که شامل اطلاعاتی دربارهٔ نحوه پیشرفت اسلاید مشخص در نمایش اسلایدها است را برمی‌گرداند. فقط-خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | مدیر تم حاکم را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء زمان‌بند انیمیشن را برمی‌گرداند. فقط-خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند که آیا دو نمونهٔ IBaseSlide برابر هستند یا خیر. مقدار بازگشتی بر پایه ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ منحصر به‌فرد مانند SlideId و محتوای دینامیک مانند مقدار تاریخ فعلی در Date Placeholder را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | آرایه‌ای شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته هستند را برمی‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | بخش‌های متنی (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام اشکال قابل‌قبول ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | بخش‌های متنی (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام اشکال قابل‌قبول ترکیب می‌کند. |
| [Remove](../../aspose.slides/layoutslide/remove)() | طرح‌بندی را از ارائه حذف می‌کند. |

### ارجاع‌ها

* کلاس [BaseSlide](../baseslide)
* رابط [ILayoutSlide](../ilayoutslide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->