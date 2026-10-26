---
title: XmlWriter
second_title: Aspose.Slides برای مرجع API C++
description: نمایندهٔ نویسنده‌ای است که روش سریع، بدون کش، فقط-به‌جهت برای تولید جریان‌ها یا فایل‌هایی که شامل داده‌های XML هستند، فراهم می‌آورد.
type: docs
weight: 573
url: /fa/system.xml/xmlwriter/
---
## کلاس XmlWriter

نویسنده‌ای را نمایندگی می‌کند که روشی سریع، بدون کش، فقط‌به‌جهت برای تولید جریان‌ها یا فایل‌هایی که شامل داده‌های XML هستند، فراهم می‌آورد.

```cpp
class XmlWriter : public System::IDisposable
```
## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Close](./close/)() | زمانی که در یک کلاس مشتق بازنویسی شود، این جریان و جریان زیرین را می‌بندد. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | یک نمونه جدید [XmlWriter](./) را با استفاده از نام پروندهٔ مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونه جدید [XmlWriter](./) را با استفاده از نام پرونده و شیء [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک نمونه جدید [XmlWriter](./) را با استفاده از جریان مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونه جدید [XmlWriter](./) را با استفاده از جریان و شیء [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | یک نمونه جدید [XmlWriter](./) را با استفاده از TextWriter مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونه جدید [XmlWriter](./) را با استفاده از TextWriter و شیءهای [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | یک نمونه جدید [XmlWriter](./) را با استفاده از [Text::StringBuilder](../../system.text/stringbuilder/) مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونه جدید [XmlWriter](./) را با استفاده از شیءهای [Text::StringBuilder](../../system.text/stringbuilder/) و [XmlWriterSettings](../xmlwritersettings/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | یک نمونه جدید [XmlWriter](./) را با استفاده از شیء [XmlWriter](./) مشخص‌شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | یک نمونه جدید [XmlWriter](./) را با استفاده از شیءهای [XmlWriter](./) و [XmlWriterSettings](../xmlwritersettings/) مشخص‌شده ایجاد می‌کند. |
| void [Dispose](./dispose/)() override | تمام منابع مورد استفاده توسط نمونهٔ فعلی کلاس [XmlWriter](./) را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنایی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Flush](./flush/)() | زمانی که در یک کلاس مشتق بازنویسی شود، محتوای بافر را به جریان‌های زیرین و همچنین جریان زیرین تخلیه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | شیء [XmlWriterSettings](../xmlwritersettings/) مورد استفاده برای ایجاد این نمونهٔ [XmlWriter](./) را بازمی‌گرداند. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | زمانی که در یک کلاس مشتق بازنویسی شود، وضعیت نویسنده را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | زمانی که در یک کلاس مشتق بازنویسی شود، محدودهٔ **xml:lang** فعلی را دریافت می‌کند. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | زمانی که در یک کلاس مشتق بازنویسی شود، یک XmlSpace که نمایانگر محدودهٔ **xml:space** فعلی است، دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مربوط به شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | زمانی که در یک کلاس مشتق بازنویسی شود، نزدیک‌ترین پیشوند تعریف‌شده در محدودهٔ نام‌فضای فعلی برای URI نام‌فضا را بازمی‌گرداند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را براساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگوئی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | قالب typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | زمانی که در یک کلاس مشتق بازنویسی شود، تمام ویژگی‌های یافت‌شده در موقعیت فعلی در [XmlReader](../xmlreader/) را می‌نویسد. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، ویژگیی با نام محلی، URI نام‌فضا و مقدار مشخص‌شده می‌نویسد. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، ویژگی را با نام محلی و مقدار مشخص‌شده می‌نویسد. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، ویژگی را با پیشوند، نام محلی، URI نام‌فضا و مقدار مشخص‌شده می‌نویسد. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | زمانی که در یک کلاس مشتق بازنویسی شود، بایت‌های باینری مشخص‌شده را به Base64 کدگذاری کرده و متن حاصل را می‌نویسد. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | زمانی که در یک کلاس مشتق بازنویسی شود، بایت‌های باینری مشخص‌شده را به **BinHex** کدگذاری کرده و متن حاصل را می‌نویسد. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | زمانی که در یک کلاس مشتق بازنویسی شود، یک بلوک **...** حاوی متن مشخص‌شده را می‌نویسد. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | زمانی که در یک کلاس مشتق بازنویسی شود، تولید یک موجودیت کاراکتر برای مقدار یونیکد مشخص‌شده را اجباری می‌کند. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | زمانی که در یک کلاس مشتق بازنویسی شود، متن را به صورت یک بافر در هر بار می‌نویسد. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | زمانی که در یک کلاس مشتق بازنویسی شود، یک کامنت **** حاوی متن مشخص‌شده را می‌نویسد. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، اعلان DOCTYPE را با نام مشخص‌شده و ویژگی‌های اختیاری می‌نویسد. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با نام محلی و مقدار مشخص‌شده می‌نویسد. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با نام محلی، URI نام‌فضا و مقدار مشخص‌شده می‌نویسد. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | یک عنصر با پیشوند، نام محلی، URI نام‌فضا و مقدار مشخص‌شده می‌نویسد. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | زمانی که در یک کلاس مشتق بازنویسی شود، فراخوانی قبلی XmlWriter::WriteStartAttribute(String,String) را می‌بندد. |
| virtual void [WriteEndDocument](./writeenddocument/)() | زمانی که در یک کلاس مشتق بازنویسی شود، همهٔ عناصر یا ویژگی‌های باز را می‌بندد و نویسنده را به وضعیت Start برمی‌گرداند. |
| virtual void [WriteEndElement](./writeendelement/)() | زمانی که در یک کلاس مشتق بازنویسی شود، یک عنصر را می‌بندد و محدودهٔ نام‌فضای مربوطه را برمی‌دارد. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، یک مرجع موجودیت را به صورت **&name**; می‌نویسد. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | زمانی که در یک کلاس مشتق بازنویسی شود، یک عنصر را می‌بندد و محدودهٔ نام‌فضای مربوطه را برمی‌دارد. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، نام مشخص‌شده را می‌نویسد و اطمینان می‌یابد که مطابق توصیهٔ W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) یک نام معتبر است. |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، نام مشخص‌شده را می‌نویسد و اطمینان می‌یابد که مطابق توصیهٔ W3C XML 1.0 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) یک NmToken معتبر است. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | زمانی که در یک کلاس مشتق بازنویسی شود، همه چیز را از خواننده به نویسنده کپی می‌کند و خواننده را به ابتدای خواهر بعدی منتقل می‌سازد. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | همه چیز را از شیء XPathNavigator به نویسنده کپی می‌کند. موقعیت XPathNavigator بدون تغییر می‌ماند. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | زمانی که در یک کلاس مشتق بازنویسی شود، یک دستور پردازش با فاصله بین نام و متن به شکل **<?name text?>** می‌نویسد. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، نام-qualified توسط نام‌فضا را می‌نویسد. این روش پیشوندی را که در محدوده برای نام‌فضای داده‌شده است، جستجو می‌کند. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | زمانی که در یک کلاس مشتق بازنویسی شود، نشانه‌گذاری خام را به‌صورت دستی از یک بافر کاراکتری می‌نویسد. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، نشانه‌گذاری خام را به‌صورت دستی از یک رشته می‌نویسد. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | شروع یک ویژگی با نام محلی و URI نام‌فضای مشخص‌شده را می‌نویسد. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، شروع یک ویژگی با پیشوند، نام محلی و URI نام‌فضای مشخص‌شده را می‌نویسد. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | شروع یک ویژگی با نام محلی مشخص‌شده را می‌نویسد. |
| virtual void [WriteStartDocument](./writestartdocument/)() | زمانی که در یک کلاس مشتق بازنویسی شود، اعلان XML را با نسخه "1.0" می‌نویسد. |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | زمانی که در یک کلاس مشتق بازنویسی شود، اعلان XML را با نسخه "1.0" و ویژگی standalone می‌نویسد. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، تگ شروع مشخص‌شده را می‌نویسد و آن را به نام‌فضای داده‌شده مرتبط می‌کند. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، تگ شروع مشخص‌شده را می‌نویسد و آن را به نام‌فضای داده‌شده و پیشوند مرتبط می‌کند. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، تگ شروعی با نام محلی مشخص‌شده می‌نویسد. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | زمانی که در یک کلاس مشتق بازنویسی شود، محتوای متنی داده‌شده را می‌نویسد. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | زمانی که در یک کلاس مشتق بازنویسی شود، موجودیت کاراکتر جفت‌سورژانت را تولید و می‌نویسد. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | مقدار شیء را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | یک مقدار [String](../../system/string/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(**bool**) | یک مقدار [Boolean](../../system/boolean/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | یک مقدار [DateTime](../../system/datetime/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | یک مقدار [DateTimeOffset](../../system/datetimeoffset/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(**double**) | یک مقدار [Double](../../system/double/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(**float**) | یک عدد نقطه شناور تک‌دقت را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | یک مقدار [Decimal](../../system/decimal/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | یک مقدار [Int32](../../system/int32/) را می‌نویسد. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | یک مقدار [Int64](../../system/int64/) را می‌نویسد. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | زمانی که در یک کلاس مشتق بازنویسی شود، فضای سفید داده‌شده را می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## موارد مرتبط

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)