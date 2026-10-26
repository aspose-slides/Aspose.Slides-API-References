---
title: PictureFillFormat
second_title: مرجع API Aspose.Slides برای C++
description: یک سبک پرکردن با تصویر را نمایش می‌دهد.
type: docs
weight: 4720
url: /fa/aspose.slides/picturefillformat/
---
## کلاس PictureFillFormat

یک سبک پرکردن با تصویر را نشان می‌دهد.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | تصویر را با کاهش اندازهٔ آن بر اساس اندازهٔ شکل و وضوح مشخص شده فشرده می‌کند. در صورت نیاز، نواحی بریده‌شده را نیز حذف می‌کند. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | تصویر را با کاهش اندازهٔ آن بر اساس اندازهٔ شکل و وضوح مشخص شده فشرده می‌کند. در صورت نیاز، نواحی بریده‌شده را نیز حذف می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | نواحی بریده‌شدهٔ پرکردن [Picture](../picture/) را حذف می‌کند. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | با شیء مشخص‌شده مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌ای سبک C# را شبیه‌سازی می‌کند؛ دو مقدار NaN همچنان برابر در نظر گرفته می‌شوند هرچند بر اساس IEC 60559:1989 NaN برابر هیچ‌مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌ای سبک C# را شبیه‌سازی می‌کند؛ دو مقدار NaN همچنان برابر در نظر گرفته می‌شوند هرچند بر اساس IEC 60559:1989 NaN برابر هیچ‌مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_CropBottom](./get_cropbottom/)() override | تعداد درصدهای ارتفاع واقعی تصویر که از پایین تصویر بریده می‌شود را برمی‌گرداند. خواندنی **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | تعداد درصدهای عرض واقعی تصویر که از چپ تصویر بریده می‌شود را برمی‌گرداند. خواندنی **float**. |
| **float** [get_CropRight](./get_cropright/)() override | تعداد درصدهای عرض واقعی تصویر که از راست تصویر بریده می‌شود را برمی‌گرداند. خواندنی **float**. |
| **float** [get_CropTop](./get_croptop/)() override | تعداد درصدهای ارتفاع واقعی تصویر که از بالای تصویر بریده می‌شود را برمی‌گرداند. خواندنی **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | dpi‌ای که برای پر کردن تصویر استفاده می‌شود را برمی‌گرداند. خواندنی **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | تصویر را برمی‌گرداند. فقط-خواندنی [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | حالت پر کردن تصویر را برمی‌گرداند. فقط [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | لبهٔ پایین مستطیل پرکردن که به‌وسیلهٔ درصدی نسبت به لبهٔ پایین جعبهٔ محدودهٔ شکل تعریف می‌شود را برمی‌گرداند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. خواندنی **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | لبهٔ چپ مستطیل پرکردن که به‌وسیلهٔ درصدی نسبت به لبهٔ چپ جعبهٔ محدودهٔ شکل تعریف می‌شود را برمی‌گرداند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. خواندنی **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | لبهٔ راست مستطیل پرکردن که به‌وسیلهٔ درصدی نسبت به لبهٔ راست جعبهٔ محدودهٔ شکل تعریف می‌شود را برمی‌گرداند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. خواندنی **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | لبهٔ بالای مستطیل پرکردن که به‌وسیلهٔ درصدی نسبت به لبهٔ بالای جعبهٔ محدودهٔ شکل تعریف می‌شود را برمی‌گرداند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. خواندنی **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | نحوهٔ تراز بافت درون شکل را برمی‌گرداند. این تنظیم نقطهٔ شروع الگوی بافت و نحوهٔ تکرار آن را در سراسر شکل کنترل می‌کند. خواندنی [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. خواندنی [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | مقدار افقی جابجایی بافت نسبت به مبدأ شکل را بر حسب پوینت برمی‌گرداند. مقدار مثبت بافت را به راست می‌برد، مقدار منفی به چپ. خواندنی **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | مقدار عمودی جابجایی بافت نسبت به مبدأ شکل را بر حسب پوینت برمی‌گرداند. مقدار مثبت بافت را به پایین می‌برد، مقدار منفی به بالا. خواندنی **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | مقیاس افقی بافت پرکردن را به‌صورت درصد برمی‌گرداند. خواندنی **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | مقیاس عمودی بافت پرکردن را به‌صورت درصد برمی‌گرداند. خواندنی **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# ‘is’. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری C#‌ی ‎lock()‎. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند؛ فقط شیء جدیدی را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع چیزی را کپی نمی‌کند؛ فقط شیء جدیدی را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را بر اساس مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | تعداد درصدهای ارتفاع واقعی تصویر که از پایین تصویر بریده می‌شود را تنظیم می‌کند. قابِل نوشتن **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | تعداد درصدهای عرض واقعی تصویر که از چپ تصویر بریده می‌شود را تنظیم می‌کند. قابِل نوشتن **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | تعداد درصدهای عرض واقعی تصویر که از راست تصویر بریده می‌شود را تنظیم می‌کند. قابِل نوشتن **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | تعداد درصدهای ارتفاع واقعی تصویر که از بالای تصویر بریده می‌شود را تنظیم می‌کند. قابِل نوشتن **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | dpi‌ای که برای پر کردن تصویر استفاده می‌شود را تنظیم می‌کند. قابِل نوشتن **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | حالت پر کردن تصویر را تنظیم می‌کند. قابِل نوشتن [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | لبهٔ پایین مستطیل پرکردن را که به‌وسیلهٔ درصدی نسبت به لبهٔ پایین جعبهٔ محدودهٔ شکل تعریف می‌شود تنظیم می‌کند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. قابِل نوشتن **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | لبهٔ چپ مستطیل پرکردن را که به‌وسیلهٔ درصدی نسبت به لبهٔ چپ جعبهٔ محدودهٔ شکل تعریف می‌شود تنظیم می‌کند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. قابِل نوشتن **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | لبهٔ راست مستطیل پرکردن را که به‌وسیلهٔ درصدی نسبت به لبهٔ راست جعبهٔ محدودهٔ شکل تعریف می‌شود تنظیم می‌کند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. قابِل نوشتن **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | لبهٔ بالای مستطیل پرکردن را که به‌وسیلهٔ درصدی نسبت به لبهٔ بالای جعبهٔ محدودهٔ شکل تعریف می‌شود تنظیم می‌کند. درصد مثبت مقدار داخلی و درصد منفی مقدار بیرونی را تعیین می‌کند. قابِل نوشتن **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | نحوهٔ تراز بافت درون شکل را تنظیم می‌کند. این تنظیم نقطهٔ شروع الگوی بافت و نحوهٔ تکرار آن را در سراسر شکل کنترل می‌کند. قابِل نوشتن [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. قابِل نوشتن [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | مقدار افقی جابجایی بافت نسبت به مبدأ شکل را تنظیم می‌کند. مقدار مثبت بافت را به راست می‌برد، مقدار منفی به چپ. قابِل نوشتن **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | مقدار عمودی جابجایی بافت نسبت به مبدأ شکل را تنظیم می‌کند. مقدار مثبت بافت را به پایین می‌برد، مقدار منفی به بالا. قابِل نوشتن **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | مقیاس افقی بافت پرکردن را به‌صورت درصد تنظیم می‌کند. قابِل نوشتن **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | مقیاس عمودی بافت پرکردن را به‌صورت درصد تنظیم می‌کند. قابِل نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب n‌ام را به‌عنوان اشاره‌گر ضعیف تنظیم می‌کند (به‌جای اشاره‌گر اشتراکی). امکان تغییر اشاره‌گرها در مجموعه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی قفل‌گذاری C# ‎lock()‎ برای باز کردن قفل. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. همهٔ ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## همچنین ببینید

* کلاس [PVIObject](../pviobject/)
* کلاس [IPictureFillFormat](../ipicturefillformat/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)