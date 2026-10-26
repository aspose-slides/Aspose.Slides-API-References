---
title: SoapDocumentMethodAttribute
second_title: مرجع API Aspose.Slides برای C++
description: "مشخص می‌کند که تمام پیام‌های SOAP که از روش عبور می‌کنند یا از آن بازگردانده می‌شوند، از قالب Document استفاده می‌کنند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های ادعایی می‌شود. همواره این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 53
url: /fa/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute کلاس

مشخص می‌کند که تمام پیام‌های SOAP که از روش عبور می‌کنند یا از آن بازگردانده می‌شوند، از قالب Document استفاده می‌کنند. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یافته شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های ادعایی می‌شود. همواره این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | با استفاده از semantics C# [Object.Equals](../../system/object/equals/) اشیاء را مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [String](../../system/string/) [get_Action](./get_action/)() | مقدار ویژگی 'SOAPAction' را دریافت می‌کند. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | binding را دریافت می‌کند که روش سرویس وب XML برای آن یک عملیات را پیاده‌سازی می‌کند. |
| **bool** [get_OneWay](./get_oneway/)() | مقداری دریافت می‌کند که نشان می‌دهد آیا کلاینت صبر نمی‌کند تا سرور پردازش روش را تمام کند. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | مقداری دریافت می‌کند که نشان می‌دهد آیا پارامترها در یک عنصر XML واحد زیر عنصر 'Body' محصور شده‌اند. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | نام عنصر XML مرتبط با درخواست SOAP را دریافت می‌کند که در توصیف سرویس به عنوان یک عملیات تعریف شده است. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | فضای نام مرتبط با درخواست SOAP را دریافت می‌کند. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | نام عنصر XML مرتبط با پاسخ SOAP را دریافت می‌کند. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | فضای نام مرتبط با پاسخ SOAP را دریافت می‌کند. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | مقداری دریافت می‌کند که روش رمزگذاری پیام را تعیین می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | یک ویژگی سفارشی از نوع مشخص شده را که به نوع مشخص شده اعمال شده است، برمی‌گرداند. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | تمام ویژگی‌های سفارشی اعمال شده به نوع مشخص شده را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری statement lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr برحسب مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع‌ اشتراک‌گذاری شده را به میزان مشخص‌شده کاهش می‌دهد. |
| void [set_Action](./set_action/)([String](../../system/string/)) | مقدار ویژگی 'SOAPAction' را تنظیم می‌کند. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | binding را تنظیم می‌کند که روش سرویس وب XML برای آن یک عملیات را پیاده‌سازی می‌کند. |
| void [set_OneWay](./set_oneway/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا کلاینت صبر نمی‌کند تا سرور پردازش روش را تمام کند. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | مقداری تنظیم می‌کند که نشان می‌دهد آیا پارامترها در یک عنصر XML واحد زیر عنصر 'Body' محصور شده‌اند. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | نام عنصر XML مرتبط با درخواست SOAP را تنظیم می‌کند که در توصیف سرویس به عنوان یک عملیات تعریف شده است. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | فضای نام مرتبط با درخواست SOAP را تنظیم می‌کند. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | نام عنصر XML مرتبط با پاسخ SOAP را تنظیم می‌کند. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | فضای نام مرتبط با پاسخ SOAP را تنظیم می‌کند. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | مقداری تنظیم می‌کند که روش رمزگذاری پیام را تعیین می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌ اشتراک‌گذاری شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع‌ اشتراک‌گذاری شده را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع‌ اشتراک‌گذاری شده را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند اشاره‌گرها یا ThisProtector استفاده کنید. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | یک نمونه جدید را می‌سازد. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | یک نمونه جدید را می‌سازد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل statement lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمند اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## همچنین ببینید

* کلاس [Attribute](../../system/attribute/)
* فضای نام [System::Web::Services::Protocols](../)
* کتابخانه [Aspose.Slides](../../)