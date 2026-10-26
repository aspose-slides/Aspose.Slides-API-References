---
title: XslCompiledTransform
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های XML را با استفاده از یک سبک‌برگ XSLT تبدیل می‌کند.
type: docs
weight: 53
url: /fa/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform کلاس

داده‌های XML را با استفاده از یک سبک‌برگ XSLT تبدیل می‌کند.

```cpp
class XslCompiledTransform : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از اصول [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور (double) به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | یک شیء [XmlWriterSettings](../../system.xml/xmlwritersettings/) را برمی‌گرداند که شامل اطلاعات خروجی استخراج شده از عنصر **xsl:output** سبک‌برگ است. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | سبک‌برگی که در [XmlReader](../../system.xml/xmlreader/) موجود است را کامپایل می‌کند. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | سبک‌برگ XSLT موجود در [XmlReader](../../system.xml/xmlreader/) را کامپایل می‌کند. [XmlResolver](../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را حل می‌کند و تنظیمات XSLT مجوزهای سبک‌برگ را تعیین می‌کند. |
| void [Load](./load/)(const [String](../../system/string/)\&) | سبک‌برگی که در URI مشخص شده قرار دارد را بارگیری و کامپایل می‌کند. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | سبک‌برگ XSLT مشخص‌شده توسط URI را بارگیری و کامپایل می‌کند. [XmlResolver](../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را حل می‌کند و تنظیمات XSLT مجوزهای سبک‌برگ را تعیین می‌کند. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | سبک‌برگی که در شیء IXPathNavigable موجود است را کامپایل می‌کند. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | سبک‌برگ XSLT موجود در IXPathNavigable را کامپایل می‌کند. [XmlResolver](../../system.xml/xmlresolver/) هر عنصر **import** یا **include** XSLT را حل می‌کند و تنظیمات XSLT مجوزهای سبک‌برگ را تعیین می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء IXPathNavigable اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء IXPathNavigable اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء IXPathNavigable اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء IXPathNavigable اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء [XmlReader](../../system.xml/xmlreader/) اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء [XmlReader](../../system.xml/xmlreader/) اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء [XmlReader](../../system.xml/xmlreader/) اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء [XmlReader](../../system.xml/xmlreader/) اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط URI اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط URI اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط URI اجرا می‌کند و نتایج را به یک TextWriter خروجی می‌دهد. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط URI اجرا می‌کند و نتایج را به یک جریان خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط URI اجرا می‌کند و نتایج را به یک فایل خروجی می‌دهد. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | تبدیل را با استفاده از سند ورودی مشخص‌شده توسط شیء [XmlReader](../../system.xml/xmlreader/) اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند و [XmlResolver](../../system.xml/xmlresolver/) تابع **document()** XSLT را حل می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | تبدیل را با استفاده از سند ورودی که توسط شیء IXPathNavigable مشخص شده است اجرا می‌کند و نتایج را به یک [XmlWriter](../../system.xml/xmlwriter/) خروجی می‌دهد. [XsltArgumentList](../xsltargumentlist/) آرگومان‌های اجرایی زمان اجرا را فراهم می‌کند و [XmlResolver](../../system.xml/xmlresolver/) تابع **document()** XSLT را حل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() C# را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XslCompiledTransform](./xslcompiledtransform/)() | یک نمونه جدید از کلاس [XslCompiledTransform](./) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | Description |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به نمونه‌ای از این کلاس. |

## ملاحظات

اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات استثنا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید. 

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Xml::Xsl](../)
* کتابخانه [Aspose.Slides](../../)