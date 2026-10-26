---
title: Picture
second_title: Aspose.Slides برای C++ مرجع API
description: نماینده یک تصویر در ارائه.
type: docs
weight: 4707
url: /fa/aspose.slides/picture/
---
## Picture کلاس

Represents a picture in a presentation.

```cpp
class Picture : public Aspose::Slides::IPVIObject,
                public Aspose::Slides::ISlidesPicture
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه می‌کند با شیء مشخص شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسه می‌کند اشیاء با استفاده از معنی‌سازهای C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسه می‌کند اشیای نوع مرجع به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه‌ی شناور به سبک C# که دو NaN را برابر در نظر می‌گیرد، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه‌ی شناور به سبک C# که دو NaN را برابر در نظر می‌گیرد، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)() override | بازگرداندن تصویر جاسازی‌شده. خواندن [IPPImage](../ippimage/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IImageTransformOperationCollection](../../aspose.slides.effects/iimagetransformoperationcollection/)\> [get_ImageTransform](./get_imagetransform/)() override | بازگرداندن مجموعه اثرهای تبدیل تصویر. فقط-خواندنی [IImageTransformOperationCollection](../../aspose.slides.effects/iimagetransformoperationcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IImageTransformOperation](../../aspose.slides.effects/iimagetransformoperation/)\> [get_ImageTransformOperation](./get_imagetransformoperation/)(**int32_t**) override | بازگرداندن عملیات تبدیل تصویر در ایندکس مشخص‌شده. |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | بازگرداندن یا تنظیم URL تصویر پیوند شده. خواندن [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | بازگرداندن شیء Parent_Immediate. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | بازگرداندن والد [IPresentationComponent](../ipresentationcomponent/). فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | بازگرداندن ارائه. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | بازگرداندن اسلاید والد یک تصویر. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../ipviobject/get_version/)() | نسخه. فقط-خواندنی **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده مرجع مرتبط با شیء. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | بازگرداندن هش. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C#. مستقیماً فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان ایجاد نسخهٔ تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شیء. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقایسه می‌کند اشیاء بر پایهٔ ارجاع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقایسه می‌کند اشیاء بر پایهٔ ارجاع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع ارزش با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به میزان مقدار مشخص کاهش می‌دهد. |
| void [set_Image](./set_image/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | تنظیم تصویر جاسازی‌شده. نوشتن [IPPImage](../ippimage/). |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | بازگرداندن یا تنظیم URL تصویر پیوند شده. نوشتن [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان nام الگو به یک اشاره‌گر ضعیف (به جای مشترک). اجازه می‌دهد اشاره‌گرها در کانتینرها به حالت ضعیف تغییر کنند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ ارجاع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارندهٔ ارجاع مشترک. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش می‌دهد و شمارندهٔ ارجاع مشترک را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری بیان lock() در C#. مستقیماً فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارندهٔ ارجاع ضعیف. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارندهٔ ارجاع ضعیف. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | از بین می‌برد شیء. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IPVIObject](../ipviobject/)
* کلاس [ISlidesPicture](../islidespicture/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)