---
title: XmlSchemaInfo
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر مجموعهٔ اطلاعات پس از اعتبارسنجی طرح‌وارهٔ یک گره XML معتبر است.
type: docs
weight: 521
url: /fa/system.xml.schema/xmlschemainfo/
---
## کلاس XmlSchemaInfo

نمایانگر مجموعهٔ اطلاعات پس از اعتبارسنجی طرح‌وارهٔ XML برای یک گره XML معتبر است.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## متدها

| متد | شرح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | شی XmlSchemaContentType را که با نوع محتواى این گره XML معتبر مطابقت دارد، برمی‌گرداند. |
| **bool** [get_IsDefault](./get_isdefault/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا این گره XML معتبر به عنوان نتیجهٔ اعمال مقدار پیش‌فرض در طول اعتبارسنجی طرح‌وارهٔ XML [Schema](../) Definition Language (XSD) تنظیم شده است یا نه. |
| **bool** [get_IsNil](./get_isnil/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا مقدار این گره XML معتبر **nil** است یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_MemberType](./get_membertype/)() override | نوع طرح‌وارهٔ پویا را برای این گره XML معتبر برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\> [get_SchemaAttribute](./get_schemaattribute/)() override | شی کامپایل‌شدهٔ [XmlSchemaAttribute](../xmlschemaattribute/) را که با این گره XML معتبر مطابقت دارد، برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\> [get_SchemaElement](./get_schemaelement/)() override | شی کامپایل‌شدهٔ [XmlSchemaElement](../xmlschemaelement/) را که با این گره XML معتبر مطابقت دارد، برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() override | نوع طرح‌وارهٔ ثابت XML [Schema](../) Definition Language (XSD) این گره XML معتبر را برمی‌گرداند. |
| [XmlSchemaValidity](../xmlschemavalidity/) [get_Validity](./get_validity/)() override | مقدار XmlSchemaValidity این گره XML معتبر را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیا سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شی نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به میزان مشخص‌شده کاهش می‌دهد. |
| void [set_ContentType](./set_contenttype/)([XmlSchemaContentType](../xmlschemacontenttype/)) | شی XmlSchemaContentType را که با نوع محتواى این گره XML معتبر مطابقت دارد، تنظیم می‌کند. |
| void [set_IsDefault](./set_isdefault/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا این گره XML معتبر به عنوان نتیجهٔ اعمال مقدار پیش‌فرض در طول اعتبارسنجی طرح‌وارهٔ XML [Schema](../) Definition Language (XSD) تنظیم شده است یا نه. |
| void [set_IsNil](./set_isnil/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا مقدار این گره XML معتبر **nil** است یا نه. |
| void [set_MemberType](./set_membertype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | نوع طرح‌وارهٔ پویا را برای این گره XML معتبر تنظیم می‌کند. |
| void [set_SchemaAttribute](./set_schemaattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\&) | شی کامپایل‌شدهٔ [XmlSchemaAttribute](../xmlschemaattribute/) را که با این گره XML معتبر مطابقت دارد، تنظیم می‌کند. |
| void [set_SchemaElement](./set_schemaelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaElement](../xmlschemaelement/)\>\&) | شی کامپایل‌شدهٔ [XmlSchemaElement](../xmlschemaelement/) را که با این گره XML معتبر مطابقت دارد، تنظیم می‌کند. |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | نوع طرح‌وارهٔ ثابت XML [Schema](../) Definition Language (XSD) این گره XML معتبر را تنظیم می‌کند. |
| void [set_Validity](./set_validity/)([XmlSchemaValidity](../xmlschemavalidity/)) | مقدار XmlSchemaValidity این گره XML معتبر را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف تنظیم می‌کند (به جای مشترک). امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشای بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlSchemaInfo](./xmlschemainfo/)() | یک نمونه جدید از کلاس [XmlSchemaInfo](./) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعریف‌های Typedef

| تعریف‌نوع | شرح |
| --- | --- |
| [Ptr](./ptr/) | نام مستعاری برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## ملاحظات

شی‌های این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص یابند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از operator new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید. 

## مراجع

* کلاس [IXmlSchemaInfo](../ixmlschemainfo/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)