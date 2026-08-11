---
title: ThreeDFormat
second_title: مرجع API Aspose.Slides برای C++
description: خصوصیات سه‌بعدی را نشان می‌دهد.
type: docs
weight: 5513
url: /fa/aspose.slides/threedformat/
---
## ThreeDFormat کلاس

Represents 3-D properties.

```cpp
class ThreeDFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IThreeDFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه با شیء مشخص شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسه اشیاء با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسه اشیاء نوع ارجاعی به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() override | نوع برجستگی 3D پایین را برمی‌گرداند. فقط خواندنی [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() override | نوع برجستگی 3D بالا را برمی‌گرداند. فقط خواندنی [IShapeBevel](../ishapebevel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() override | تنظیمات دوربین را برمی‌گرداند. فقط خواندنی [ICamera](../icamera/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() override | رنگ کانتور را برمی‌گرداند. فقط خواندنی [IColorFormat](../icolorformat/). |
| **double** [get_ContourWidth](./get_contourwidth/)() override | عرض یک کانتور 3D را برمی‌گرداند. خواند **double**. |
| **double** [get_Depth](./get_depth/)() override | عمق یک شکل 3D را برمی‌گرداند. خواند **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() override | رنگ یک بیرون‌زدگی را برمی‌گرداند. فقط خواندنی [IColorFormat](../icolorformat/). |
| **double** [get_ExtrusionHeight](./get_extrusionheight/)() override | ارتفاع اثر بیرون‌زدگی را برمی‌گرداند. خواند **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() override | نوع نور را برمی‌گرداند. فقط خواندنی [ILightRig](../ilightrig/). |
| [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() override | نوع ماده را برمی‌گرداند. خواند [MaterialPresetType](../materialpresettype/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شی Parent_Immediate را برمی‌گرداند. فقط خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده مرجع مرتبط با شیء. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() override | دریافت داده‌های قالب‌بندی 3-بعدی مؤثر با اعمال وراثت. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی اینکه آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت lock() در C#. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان نسخه‌برداری انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه‌کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه‌کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقایسه اشیاء بر اساس مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقایسه اشیاء بر اساس مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده‌ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_ContourWidth](./set_contourwidth/)(**double**) override | عرض یک کانتور 3D را تنظیم می‌کند. نوشتن **double**. |
| void [set_Depth](./set_depth/)(**double**) override | عمق یک شکل 3D را تنظیم می‌کند. نوشتن **double**. |
| void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) override | ارتفاع اثر بیرون‌زدگی را تنظیم می‌کند. نوشتن **double**. |
| void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) override | نوع یک ماده را تنظیم می‌کند. نوشتن [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارنده مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارنده مرجع مشترک. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش می‌دهد و شمارنده مرجع مشترک را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی حذف قفل با عبارت lock() در C#. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارنده مرجع ضعیف. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارنده مرجع ضعیف. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## ملاحظات

The following example shows how to add 3D shape in PowerPoint [Presentation](../presentation/). 
```cpp
// یک نمونه از کلاس Presentation ایجاد کنید.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Add a shape using AddAutoShape method
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 200.0f, 200.0f);

// Define TextFrame and its properties
shape->get_TextFrame()->set_Text(u"3D");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// Define ThreeDFormat Properties
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// Save the Presentation file
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
 The following example shows how to apply Gradient affect to 3D shape in PowerPoint [Presentation](../presentation/). 
```cpp
// یک نمونه از کلاس Presentation ایجاد کنید.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// یک شکل با استفاده از متد AddAutoShape اضافه کنید
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// تعریف TextFrame و ویژگی‌های آن
shape->get_TextFrame()->set_Text(u"3D Gradient");
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(64.0f);

// تنظیم FillFormat.FillType به عنوان FillType.Gradient و تعریف ویژگی‌های گرادیان
shape->get_FillFormat()->set_FillType(FillType::Gradient);
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(0.0f, System::Drawing::Color::get_Blue());
shape->get_FillFormat()->get_GradientFormat()->get_GradientStops()->Add(100.0f, System::Drawing::Color::get_Orange());

// تعریف ویژگی‌های ThreeDFormat
auto threeDFormat = shape->get_ThreeDFormat();
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::OrthographicFront);
threeDFormat->get_Camera()->SetRotation(20.0f, 30.0f, 40.0f);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Flat);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->set_Material(MaterialPresetType::Flat);
threeDFormat->set_ExtrusionHeight(100);
threeDFormat->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Blue());
slide->GetThumbnail(2.0f, 2.0f)->Save(u"sample_3d.png");

// ذخیره فایل Presentation
pres->Save(u"sandbox_3d.pptx", SaveFormat::Pptx);
```
 The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect. 
```cpp
// یک نمونه از کلاس Presentation ایجاد کنید.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// یک شکل با استفاده از متد AddAutoShape اضافه کنید
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 150.0f, 250.0f, 250.0f);

// تعریف TextFrame و ویژگی‌های آن
shape->get_TextFrame()->set_Text(u"3D Text");

// تنظیم FillFormat.FillType به عنوان FillType.NoFill
shape->get_FillFormat()->set_FillType(FillType::NoFill);
shape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::NoFill);

// پیکربندی Portion از TextFrame و تنظیم ویژگی‌های PortionFormat
System::SharedPtr<Portion> portion = System::ExplicitCast<Portion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0));
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Pattern);
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_ForeColor()->set_Color(System::Drawing::Color::get_DarkOrange());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->get_BackColor()->set_Color(System::Drawing::Color::get_White());
portion->get_PortionFormat()->get_FillFormat()->get_PatternFormat()->set_PatternStyle(PatternStyle::LargeGrid);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_DefaultPortionFormat()->set_FontHeight(128.0f);
System::SharedPtr<ITextFrame> textFrame = shape->get_TextFrame();

// راه‌اندازی اثر تبدیل WordArt "Arch Up"
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUp);

// تعریف ویژگی‌های ThreeDFormat برای ITextFrame
auto threeDFormat = textFrame->get_TextFrameFormat()->get_ThreeDFormat();
threeDFormat->set_ExtrusionHeight(3.5f);
threeDFormat->set_Depth(3);
threeDFormat->set_Material(MaterialPresetType::Plastic);
threeDFormat->get_LightRig()->set_Direction(LightingDirection::Top);
threeDFormat->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
threeDFormat->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);
threeDFormat->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
slide->GetThumbnail(2.0f, 2.0f)->Save(u"text3d.png");

// ذخیره فایل Presentation
pres->Save(u"text3d.pptx", SaveFormat::Pptx);
```

## مراجعات

* کلاس [PVIObject](../pviobject/)
* کلاس [IThreeDFormat](../ithreedformat/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)