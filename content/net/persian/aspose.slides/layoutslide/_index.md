---
title: LayoutSlide
second_title: مرجع API Aspose.Sildes برای .NET
description: یک اسلاید طرح‌بندی را نشان می‌دهد.
type: docs
weight: 7640
url: /fa/aspose.slides/layoutslide/
---
## کلاس LayoutSlide

یک اسلاید طرح‌بندی را نشان می‌دهد.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | مجموعهٔ کنترل‌های ActiveX موجود در یک اسلاید را برمی‌گرداند. فقط-خواندنی [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | یک مجموعه از راهنماهای رسم برای اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | در صورتی که حداقل یک اسلاید که به این اسلاید طرح‌بندی وابسته است وجود داشته باشد، true برمی‌گرداند. فقط-خواندنی Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | مدیر HeaderFooter اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | نوع طرح‌بندی این اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | اسلاید مستر برای یک طرح‌بندی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | مدیر placeholder اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | اینترفیس IPresentation را برمی‌گرداند. فقط-خواندنی [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | اشکال shapes یک اسلاید را برمی‌گرداند. فقط-خواندنی [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | مشخص می‌کند آیا اشکال (shapes) روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا خیر. خواندنی/نوشتنی Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | شناسه (ID) یک اسلاید را برمی‌گرداند. فقط-خواندنی UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | شیء Transition را که شامل اطلاعاتی دربارهٔ پیشرفت اسلاید مشخص در طول نمایش اسلاید است، برمی‌گرداند. فقط-خواندنی [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | مدیر تم (theme) حاکم را برمی‌گرداند. فقط-خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | شیء animation timeline را برمی‌گرداند. فقط-خواندنی [`IAnimationTimeLine`](../ianimationtimeline). |

## متدها

| نام | توضیح |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | تعیین می‌کند آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید زمانی برابر هستند که تمام shapes، سبک‌ها، متن‌ها، animation و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در Date Placeholder را در نظر نمی‌گیرد. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | اولین رخداد یک shape با متن جایگزین مشخص شده را پیدا می‌کند. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | یک آرایه شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته‌اند را برمی‌گرداند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | دنباله‌های (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام shapes قابل قبول ترکیب می‌کند. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | دنباله‌های (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام shapes قابل قبول ترکیب می‌کند. |
| [Remove](../../aspose.slides/layoutslide/remove)() | طرح‌بندی را از ارائه حذف می‌کند. |

### موارد مرتبط

* کلاس [BaseSlide](../baseslide)
* رابط [ILayoutSlide](../ilayoutslide)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->