---
title: XmlTextWriter
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر یک نويسنده که روش سریع، بدون حافظه‌پنهان، یک‌سویه برای تولید جریان‌ها یا فایل‌های حاوی داده‌های XML که با استاندارد W3C Extensible Markup Language (XML) 1.0 و توصیه‌های Namespaces in XML سازگار است، فراهم می‌کند.
type: docs
weight: 521
url: /fa/system.xml/xmltextwriter/
---
## XmlTextWriter کلاس

نمایانگر یک نويسنده که روش سریع، بدون حافظه‌پنهان، یک‌سویه برای تولید جریان‌ها یا فایل‌های حاوی داده‌های XML که با استاندارد W3C Extensible Markup Language (XML) 1.0 و توصیه‌های Namespaces in XML سازگار است، فراهم می‌کند.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## متدها

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | این جریان و جریان زیرین را می‌بندد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از نام فایل مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از نام فایل و شیء [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از جریان مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از جریان و شیء [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از TextWriter مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از TextWriter و شیءهای [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از [Text::StringBuilder](../../system.text/stringbuilder/) مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از شیءهای [Text::StringBuilder](../../system.text/stringbuilder/) و [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از شیء [XmlWriter](../xmlwriter/) مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونهٔ جدید [XmlWriter](../xmlwriter/) را با استفاده از شیءهای [XmlWriter](../xmlwriter/) و [XmlWriterSettings](../xmlwritersettings/) مشخص‌شده ایجاد می‌کند. |
| void [Dispose](../xmlwriter/dispose/)() override | تمام منابع استفاده‌شده توسط نمونهٔ فعلی کلاس [XmlWriter](../xmlwriter/) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | هر مبنایی که در بافر است را به جریان‌های زیرین تخلیه می‌کند و همچنین جریان زیرین را تخلیه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | شیء جریان زیرین را برمی‌گرداند. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | نشان می‌دهد خروجی چگونه قالب‌بندی شده است. |
| **int32_t** [get_Indentation](./get_indentation/)() | تعداد نویسه‌های تورفتگی (IndentChars) را برای هر سطح در سلسله‌مراتب وقتی [XmlTextWriter::set_Formatting](./set_formatting/) برابر [Formatting::Indented](../formatting/) تنظیم شده است، برمی‌گرداند. |
| char16_t [get_IndentChar](./get_indentchar/)() | کاراکتری که برای تورفتگی استفاده می‌شود را زمانی که [XmlTextWriter::set_Formatting](./set_formatting/) برابر [Formatting::Indented](../formatting/) باشد، برمی‌گرداند. |
| **bool** [get_Namespaces](./get_namespaces/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا پشتیبانی از فضای‌نام فعال باشد یا نه. |
| char16_t [get_QuoteChar](./get_quotechar/)() | کاراکتری را برمی‌گرداند که برای نقل قول مقادیر ویژگی استفاده می‌شود. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | شیء [XmlWriterSettings](../xmlwritersettings/) که برای ایجاد این نمونهٔ [XmlWriter](../xmlwriter/) استفاده شده است را برمی‌گرداند. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | وضعیت نويسنده را برمی‌گرداند. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | محدودهٔ فعلی **xml:lang** را برمی‌گرداند. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | یک XmlSpace که نمایانگر محدودهٔ فعلی **xml:space** است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری گزارهٔ lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | پیشوند نزدیک‌ترین تعریف‌شده در محدودهٔ فضای‌نام فعلی برای URI فضای‌نام را برمی‌گرداند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | نشان می‌دهد خروجی چگونه قالب‌بندی شده است. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | تعداد IndentChars را برای هر سطح در سلسله‌مراتب وقتی [XmlTextWriter::set_Formatting](./set_formatting/) برابر [Formatting::Indented](../formatting/) تنظیم می‌شود، تنظیم می‌کند. |
| void [set_IndentChar](./set_indentchar/)(char16_t) | تنظیم می‌کند که کدام کاراکتر برای تورفتگی استفاده شود وقتی [XmlTextWriter::set_Formatting](./set_formatting/) برابر [Formatting::Indented](../formatting/) باشد. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | مقدارایی را تنظیم می‌کند که نشان دهد آیا پشتیبانی از فضای‌نام فعال باشد یا نه. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | تنظیم می‌کند که کدام کاراکتر برای نقل قول مقادیر ویژگی استفاده شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری گزارهٔ lock() در C# را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، تمام ویژگی‌های موجود در موقعیت فعلی در [XmlReader](../xmlreader/) را می‌نویسد. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، یک ویژگی با نام محلی، URI فضای‌نام و مقدار مشخص‌شده می‌نویسد. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، ویژگی با نام محلی و مقدار مشخص‌شده را می‌نویسد. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، ویژگی با پیشوند، نام محلی، URI فضای‌نام و مقدار مشخص‌شده را می‌نویسد. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | بایت‌های باینری مشخص‌شده را به base64 کدگذاری کرده و متن حاصل را می‌نویسد. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | بایت‌های باینری مشخص‌شده را به binhex کدگذاری کرده و متن حاصل را می‌نویسد. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | یک بلوک **...** شامل متن مشخص‌شده را می‌نویسد. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | تولید یک موجودیت کاراکتری برای مقدار کاراکتر یونی‌کد مشخص‌شده را مجبور می‌کند. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | متن را به صورت یک بافر در هر بار می‌نویسد. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | یک توضیح **** شامل متن مشخص‌شده را می‌نویسد. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | اعلامیه DOCTYPE را با نام مشخص‌شده و ویژگی‌های اختیاری می‌نویسد. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با نام محلی و مقدار مشخص‌شده می‌نویسد. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با نام محلی، URI فضای‌نام و مقدار مشخص‌شده می‌نویسد. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با پیشوند، نام محلی، URI فضای‌نام و مقدار مشخص‌شده می‌نویسد. |
| void [WriteEndAttribute](./writeendattribute/)() override | فراخوانی [XmlTextWriter::WriteStartAttribute](./writestartattribute/) قبلی را می‌بندد. |
| void [WriteEndDocument](./writeenddocument/)() override | هر عنصر یا ویژگی باز را می‌بندد و نويسنده را به حالت Start بازمی‌گرداند. |
| void [WriteEndElement](./writeendelement/)() override | یک عنصر را می‌بندد و محدودهٔ فضای‌نام مربوطه را برمی‌دارد. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | یک مرجع موجودیت را به صورت **&name**; می‌نویسد. |
| void [WriteFullEndElement](./writefullendelement/)() override | یک عنصر را می‌بندد و محدودهٔ فضای‌نام مربوطه را برمی‌دارد. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | نام مشخص‌شده را می‌نویسد و اطمینان می‌دهد که نام معتبر بر پایهٔ [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) است. |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | نام مشخص‌شده را می‌نویسد و اطمینان می‌دهد که یک **NmToken** معتبر طبق [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) است. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، تمام محتوا را از خواننده به نویسنده کپی می‌کند و خواننده را به ابتدای خواهر بعدی منتقل می‌کند. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | تمام محتوا را از شیء XPathNavigator به نویسنده کپی می‌کند. موقعیت XPathNavigator تغییر نمی‌کند. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | یک دستور پردازش را با یک فاصله بین نام و متن به شکل **<?name text?>** می‌نویسد. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | نام دارای فضای‌نام را می‌نویسد. این متد پیشوند موجود در محدوده برای فضای‌نام داده‌شده را جستجو می‌کند. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | علامت‌گذاری خام را به‌صورت دستی از یک بافر کاراکتر می‌نویسد. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | علامت‌گذاری خام را به‌صورت دستی از یک رشته می‌نویسد. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | شروع یک ویژگی را می‌نویسد. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | شروع یک ویژگی با نام محلی و URI فضای‌نام مشخص‌شده را می‌نویسد. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | شروع یک ویژگی با نام محلی مشخص‌شده را می‌نویسد. |
| void [WriteStartDocument](./writestartdocument/)() override | اعلامیه XML را با نسخه "1.0" می‌نویسد. |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | اعلامیه XML را با نسخه "1.0" و ویژگی standalone می‌نویسد. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | برچسب شروع مشخص‌شده را می‌نویسد و آن را با فضای‌نام و پیشوند داده‌شده مرتبط می‌کند. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، برچسب شروع مشخص‌شده را می‌نویسد و آن را با فضای‌نام داده‌شده مرتبط می‌کند. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | هنگامی که در کلاس مشتق‌شده بازنویسی شود، برچسب شروعی با نام محلی مشخص‌شده را می‌نویسد. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | محتوای متنی داده‌شده را می‌نویسد. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | موجودیت کاراکتر سوڕجیت برای جفت سوڕجیت تولید و می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | مقدار شیء را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | مقدار [String](../../system/string/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | مقدار [Boolean](../../system/boolean/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | مقدار [DateTime](../../system/datetime/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | مقدار [DateTimeOffset](../../system/datetimeoffset/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | مقدار [Double](../../system/double/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | عدد اعشاری تک دقت (float) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | مقدار [Decimal](../../system/decimal/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | مقدار [Int32](../../system/int32/) را می‌نویسد. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | مقدار [Int64](../../system/int64/) را می‌نویسد. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | فضای سفید داده‌شده را می‌نویسد. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | یک نمونه از کلاس [XmlTextWriter](./) را با استفاده از جریان و رمزگذاری مشخص‌شده ایجاد می‌کند. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | یک نمونه از کلاس [XmlTextWriter](./) را با استفاده از فایل مشخص‌شده ایجاد می‌کند. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | یک نمونه از کلاس [XmlTextWriter](./) را با استفاده از TextWriter مشخص‌شده ایجاد می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس است. |

## ملاحظات

توصیه می‌شود به‌جای آن از کلاس [XmlWriter](../xmlwriter/) استفاده کنید. 

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید. 

## مراجع

* کلاس [XmlWriter](../xmlwriter/)
* فضایی‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)