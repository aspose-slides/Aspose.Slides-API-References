---
title: XmlWriterSettings
second_title: Aspose.Slides برای مرجع API C++
description: "یک مجموعه از ویژگی‌ها را برای پشتیبانی روی شیء XmlWriter که توسط متد XmlWriter::Create ایجاد می‌شود، مشخص می‌کند."
type: docs
weight: 586
url: /fa/system.xml/xmlwritersettings/
---
## XmlWriterSettings کلاس

یک مجموعه از ویژگی‌ها را برای پشتیبانی روی شیء [XmlWriter](../xmlwriter/) که توسط متد [XmlWriter::Create](../xmlwriter/create/) ایجاد می‌شود، مشخص می‌کند.

```cpp
class XmlWriterSettings : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | یک کپی از نمونه [XmlWriterSettings](./) ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا نویسنده XML باید بررسی کند که تمام کاراکترهای سند با بخش "2.2 Characters" از [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) W3C مطابقت دارند یا نه. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) باید هنگام فراخوانی متد [XmlWriter::Close](../xmlwriter/close/)، جریان پایه یا TextWriter را نیز ببندد یا خیر. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | سطح انطباقی را که نویسنده XML برای خروجی XML بررسی می‌کند، برمی‌گرداند. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) ویژگی‌های URI را Escape نمی‌کند یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | نوع رمزگذاری متن مورد استفاده را برمی‌گرداند. |
| **bool** [get_Indent](./get_indent/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا عناصر باید تو.indent شوند یا نه. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | رشته کاراکتری که هنگام تو.indent استفاده می‌شود را برمی‌گرداند. این تنظیم زمانی استفاده می‌شود که مقدار [XmlWriterSettings::set_Indent](./set_indent/) برابر **true** باشد. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) باید هنگام نوشتن محتوای XML، اعلان‌های فضای‌نام تکراری را حذف کند یا نه. رفتار پیش‌فرض این است که نویسنده تمام اعلان‌های فضای‌نام موجود در حل‌کننده فضای‌نام نویسنده را خروجی دهد. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | رشته کاراکتری که برای شکست خط استفاده می‌شود را برمی‌گرداند. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا شکست‌های خط در خروجی نرمال‌سازی شوند یا نه. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا ویژگی‌ها در خط جدید نوشته شوند یا نه. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا یک اعلان XML حذف شود یا نه. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | روشی که برای سریالایز خروجی [XmlWriter](../xmlwriter/) استفاده می‌شود را برمی‌گرداند. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) هنگام فراخوانی متد [XmlWriter::Close](../xmlwriter/close/)، تگ‌های بسته برای تمام تگ‌های عنصر باز نشده اضافه می‌کند یا نه. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌کردن آبجکت‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل (lock()) در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | آبجکت نوع مقدار را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده‌ی مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [Reset](./reset/)() | اعضای کلاس تنظیمات را به مقادیر پیش‌فرض بازنشانی می‌کند. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا نویسنده XML باید بررسی کند که تمام کاراکترهای سند با بخش "2.2 Characters" از [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) W3C مطابقت دارند یا نه. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) هنگام فراخوانی متد [XmlWriter::Close](../xmlwriter/close/)، جریان پایه یا TextWriter را نیز ببندد یا نه. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | سطح انطباقی که نویسنده XML برای خروجی XML بررسی می‌کند را تنظیم می‌کند. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) ویژگی‌های URI را Escape نمی‌کند یا نه. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | نوع رمزگذاری متن مورد استفاده را تنظیم می‌کند. |
| void [set_Indent](./set_indent/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا عناصر تو.indent شوند یا نه. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | رشته کاراکتری که هنگام تو.indent استفاده می‌شود را تنظیم می‌کند. این تنظیم زمانی استفاده می‌شود که مقدار [XmlWriterSettings::set_Indent](./set_indent/) برابر **true** باشد. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | مقداری تنظیم می‌کند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) هنگام نوشتن محتوای XML، اعلان‌های فضای‌نام تکراری را حذف کند یا نه. رفتار پیش‌فرض این است که نویسنده تمام اعلان‌های فضای‌نام موجود در حل‌کننده فضای‌نام نویسنده را خروجی دهد. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | رشته کاراکتری که برای شکست خط استفاده می‌شود را تنظیم می‌کند. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | مقداری تنظیم می‌کند که نشان می‌دهد آیا شکست‌های خط در خروجی نرمال‌سازی شوند یا نه. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا ویژگی‌ها در خط جدید نوشته شوند یا نه. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا یک اعلان XML حذف شود یا نه. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | مقداری تنظیم می‌کند که نشان می‌دهد آیا [XmlWriter](../xmlwriter/) هنگام فراخوانی متد [XmlWriter::Close](../xmlwriter/close/)، تگ‌های بسته برای تمام تگ‌های عنصر باز نشده اضافه می‌کند یا نه. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام تمپلت را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل (lock()) در C# را باز می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [XmlWriterSettings](./xmlwritersettings/)() | یک نمونه جدید از کلاس [XmlWriterSettings](./) را مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | نام مستعاری برای اشاره‌گر مشترک به یک نمونه از این کلاس. |

## توضیحات

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)