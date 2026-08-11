---
title: XmlSchemaChoice
second_title: مرجع API Aspose.Slides برای C++
description: عنصر choice (کامپوزیت) را از XML Schema که توسط World Wide Web Consortium (W3C) تعریف شده است، نشان می‌دهد. choice فقط اجازه می‌دهد یکی از فرزندان آن در یک نمونه ظاهر شود.
type: docs
weight: 209
url: /fa/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice کلاس

عنصر **choice** (کامپوزیت) را از XML [Schema](../) که توسط کنسرسیوم World Wide [Web](../../system.web/) (W3C) تعریف شده است، نمایان می‌کند. **choice** تنها اجازه می‌دهد یکی از فرزندان آن در یک نمونه ظاهر شود.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | خاصیت **annotation** را برمی‌گرداند. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | شناسهٔ رشته‌ای را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() override | مجموعهٔ عناصری که توسط کامپوزیت (**choice**) شامل می‌شوند را برمی‌گرداند: [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/) یا [XmlSchemaAny](../xmlschemaany/). |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | شمارهٔ خط در فایلی را که عنصر **schema** به آن ارجاع می‌دهد، برمی‌گرداند. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | موقعیتٔ خط در فایلی را که عنصر **schema** به آن ارجاع می‌دهد، برمی‌گرداند. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | حداکثر تعداد دفعاتی را که ذره می‌تواند ظاهر شود، برمی‌گرداند. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | عدد را به عنوان مقدار رشته‌ای برمی‌گرداند. حداکثر تعداد دفعاتی که ذره می‌تواند ظاهر شود. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | حداقل تعداد دفعاتی که ذره می‌تواند ظاهر شود را برمی‌گرداند. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | عدد را به صورت مقدار رشته‌ای برمی‌گرداند. حداقل تعداد دفعاتی که ذره می‌تواند ظاهر شود. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | والد این [XmlSchemaObject](../xmlschemaobject/) را برمی‌گرداند. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | محیط منبع برای فایلی که schema را بارگذاری کرده است، برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | خصوصیات صلاحیتی که به فضای‌نام هدف فعلی schema تعلق ندارند را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری را طبق بیان C# lock() پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کپی‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه کرده و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه کرده و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | خاصیت **annotation** را تنظیم می‌کند. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | شناسهٔ رشته‌ای را تنظیم می‌کند. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | شمارهٔ خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را تنظیم می‌کند. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | موقعیتٔ خط در فایلی که عنصر **schema** به آن ارجاع می‌دهد را تنظیم می‌کند. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | حداکثر تعداد دفعاتی که ذره می‌تواند ظاهر شود را تنظیم می‌کند. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | عدد را به عنوان مقدار رشته‌ای تنظیم می‌کند. حداکثر تعداد دفعاتی که ذره می‌تواند ظاهر شود. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | حداقل تعداد دفعاتی که ذره می‌تواند ظاهر شود را تنظیم می‌کند. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | عدد را به صورت مقدار رشته‌ای تنظیم می‌کند. حداقل تعداد دفعاتی که ذره می‌تواند ظاهر شود. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | XmlSerializerNamespaces را که برای این شیء schema استفاده می‌شود تنظیم می‌کند. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | والد این [XmlSchemaObject](../xmlschemaobject/) را تنظیم می‌کند. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | محیط منبع برای فایلی که schema را بارگذاری کرده است تنظیم می‌کند. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | خصوصیات صلاحیتی که به فضای‌نام هدف فعلی schema تعلق ندارند را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. اجازه می‌دهد اشاره‌گرها در کانتینرها به حالت ضعیف تغییر یابند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | قالب typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری را طبق بیان C# lock() باز می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaChoice](./xmlschemachoice/)() | یک نمونه جدید از کلاس [XmlSchemaChoice](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | یک نمونه جدید از کلاس [XmlSchemaObject](../xmlschemaobject/) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | یک نمونه جدید از کلاس [XmlSchemaParticle](../xmlschemaparticle/) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | نام مستعاری برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## ملاحظات

شیءهای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال آن به توابع به عنوان آرگومان استفاده کنید. 

## مراجع مرتبط

* کلاس [XmlSchemaGroupBase](../xmlschemagroupbase/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)