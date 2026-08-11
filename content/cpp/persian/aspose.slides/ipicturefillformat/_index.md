---
title: IPictureFillFormat
second_title: Aspose.Slides برای C++ مرجع API
description: یک سبک پر کردن تصویر را نشان می‌دهد.
type: docs
weight: 3225
url: /fa/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat کلاس

یک سبک پر کردن تصویر را نشان می‌دهد.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص شده فشرده می‌کند. به‌صورت اختیاری، همچنین قسمت‌های بریده شده را حذف می‌کند. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص شده فشرده می‌کند. به‌صورت اختیاری، همچنین قسمت‌های بریده شده را حذف می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | قسمت‌های بریده شدهٔ پر کننده [Picture](../picture/) را حذف می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از اصول [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ‌ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ‌ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | تعداد درصدهای ارتفاع واقعی تصویر که از پایین تصویر بریده می‌شود را بازمی‌گرداند. فقط خواندنی **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | تعداد درصدهای عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را بازمی‌گرداند. فقط خواندنی **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | تعداد درصدهای عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را بازمی‌گرداند. فقط خواندنی **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | تعداد درصدهای ارتفاع واقعی تصویر که از بالای تصویر بریده می‌شود را بازمی‌گرداند. فقط خواندنی **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | dpi‌ای که برای پر کردن تصویر استفاده می‌شود را بازمی‌گرداند. فقط خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | تصویر را بازمی‌گرداند. فقط خواندنی [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | حالت پر کردن تصویر را بازمی‌گرداند. فقط خواندنی [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | لبهٔ پایین مستطیل پر کننده که به‌وسیلهٔ درصدی از لبهٔ پایین جعبه محصور شکل تعریف می‌شود را بازمی‌گرداند. درصد مثبت تو رفتگی، درصد منفی برون‌رفتگی. فقط خواندنی **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | لبهٔ چپ مستطیل پر کننده که به‌وسیلهٔ درصدی از لبهٔ چپ جعبه محصور شکل تعریف می‌شود را بازمی‌گرداند. درصد مثبت تو رفتگی، درصد منفی برون‌رفتگی. فقط خواندنی **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | لبهٔ راست مستطیل پر کننده که به‌وسیلهٔ درصدی از لبهٔ راست جعبه محصور شکل تعریف می‌شود را بازمی‌گرداند. درصد مثبت تو رفتگی، درصد منفی برون‌رفتگی. فقط خواندنی **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | لبهٔ بالای مستطیل پر کننده که به‌وسیلهٔ درصدی از لبهٔ بالای جعبه محصور شکل تعریف می‌شود را بازمی‌گرداند. درصد مثبت تو رفتگی، درصد منفی برون‌رفتگی. فقط خواندنی **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | نحوهٔ تراز بافت درون شکل را بازمی‌گرداند. این تنظیم نقطهٔ شروع الگوی بافت و نحوهٔ تکرار آن را در طول شکل کنترل می‌کند. فقط خواندنی [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. فقط خواندنی [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | اختلاف افقی بافت از مبدأ شکل را به‌پیکسل بازمی‌گرداند. مقدار مثبت بافت را به سمت راست حرکت می‌دهد، در حالی‌که مقدار منفی آن را به سمت چپ می‌برد. فقط خواندنی **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | اختلاف عمودی بافت از مبدأ شکل را به‌پیکسل بازمی‌گرداند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی‌که مقدار منفی آن را به سمت بالا می‌برد. فقط خواندنی **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | مقیاس افقی پر کردن بافت را به‌صورت درصد بازمی‌گرداند. فقط خواندنی **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | مقیاس عمودی پر کردن بافت را به‌صورت درصد بازمی‌گرداند. فقط خواندنی **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | داده‌ساختار شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | عملکرد قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کپی) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت کپی ساخته شوند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت کپی ساخته شوند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌وار شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | تعداد درصدهای ارتفاع واقعی تصویر که از پایین تصویر بریده می‌شود را تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | تعداد درصدهای عرض واقعی تصویر که از سمت چپ تصویر بریده می‌شود را تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | تعداد درصدهای عرض واقعی تصویر که از سمت راست تصویر بریده می‌شود را تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | تعداد درصدهای ارتفاع واقعی تصویر که از بالای تصویر بریده می‌شود را تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | dpi‌ای که برای پر کردن تصویر استفاده می‌شود را تنظیم می‌کند. قابل نوشتن **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | حالت پر کردن تصویر را تنظیم می‌کند. قابل نوشتن [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | لبهٔ پایین مستطیل پر کننده را که به‌وسیلهٔ درصدی از لبهٔ پایین جعبه محصور شکل تعریف می‌شود تنظیم می‌کند. مقدار مثبت تو رفتگی، مقدار منفی برون‌رفتگی. قابل نوشتن **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | لبهٔ چپ مستطیل پر کننده را که به‌وسیلهٔ درصدی از لبهٔ چپ جعبه محصور شکل تعریف می‌شود تنظیم می‌کند. مقدار مثبت تو رفتگی، مقدار منفی برون‌رفتگی. قابل نوشتن **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | لبهٔ راست مستطیل پر کننده را که به‌وسیلهٔ درصدی از لبهٔ راست جعبه محصور شکل تعریف می‌شود تنظیم می‌کند. مقدار مثبت تو رفتگی، مقدار منفی برون‌رفتگی. قابل نوشتن **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | لبهٔ بالای مستطیل پر کننده را که به‌وسیلهٔ درصدی از لبهٔ بالای جعبه محصور شکل تعریف می‌شود تنظیم می‌کند. مقدار مثبت تو رفتگی، مقدار منفی برون‌رفتگی. قابل نوشتن **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | نحوهٔ تراز بافت درون شکل را تنظیم می‌کند. این تنظیم نقطهٔ شروع الگوی بافت و نحوهٔ تکرار آن را در طول شکل کنترل می‌کند. قابل نوشتن [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | کاشی بافت را حول محور افقی، عمودی یا هر دو محور می‌چرخاند. قابل نوشتن [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | اختلاف افقی بافت از مبدأ شکل را به‌پیکسل تنظیم می‌کند. مقدار مثبت بافت را به سمت راست حرکت می‌دهد، در حالی‌که مقدار منفی آن را به سمت چپ می‌برد. قابل نوشتن **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | اختلاف عمودی بافت از مبدأ شکل را به‌پیکسل تنظیم می‌کند. مقدار مثبت بافت را به سمت پایین حرکت می‌دهد، در حالی‌که مقدار منفی آن را به سمت بالا می‌برد. قابل نوشتن **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | مقیاس افقی پر کردن بافت را به‌صورت درصد تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | مقیاس عمودی پر کردن بافت را به‌صورت درصد تنظیم می‌کند. قابل نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به‌عنوان اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IFillParamSource](../ifillparamsource/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)