---
title: XmlSerializer
second_title: مرجع API Aspose.Slides برای C++
description: "سریال‌سازی و دسیریال‌سازی اشیاء به‌صورت XML و از آن انجام می‌دهد. اشیاء این کلاس باید فقط با تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 66
url: /fa/system.xml.serialization/xmlserializer/
---
## XmlSerializer کلاس

عملیات سریال‌سازی و دسیریال‌سازی اشیاء به‌صورت XML و از آن‌را انجام می‌دهد. اشیاء این کلاس باید فقط با تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در قالب اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class XmlSerializer : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [CanDeserialize](./candeserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | بررسی می‌کند که آیا خواننده خاص در وضعیت قابل‌دیسریالیزه است. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | سند XML را به شیء دیسریالیزه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | سند XML را به شیء دیسریالیزه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | سند XML را به شیء دیسریالیزه می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>, [String](../../system/string/)) | سند XML را به شیء دیسریالیزه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. قابلیت هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/)) | سند را به XML سریال‌سازی می‌کند. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/), [String](../../system/string/)) | سند را به XML سریال‌سازی می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در سازنده‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی رفع قفل عبارت lock() در C#. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | نام فضای نام رمزگذاری. |
| static [WsdlNamespace](./wsdlnamespace/) | نام فضای نام WSDL. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | نام فضای نام انواع WSDL. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Xml::Serialization](../)
* کتابخانه [Aspose.Slides](../../)