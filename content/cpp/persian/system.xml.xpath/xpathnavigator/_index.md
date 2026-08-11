---
title: XPathNavigator
second_title: مرجع API Aspose.Slides برای C++
description: یک مدل نشانگر برای پیمایش و ویرایش داده‌های XML فراهم می‌کند.
type: docs
weight: 66
url: /fa/system.xml.xpath/xpathnavigator/
---
## XPathNavigator کلاس

یک مدل مکان‌نما برای پیمایش و ویرایش داده‌های XML فراهم می‌کند.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | یک شی [XmlWriter](../../system.xml/xmlwriter/) برمی‌گرداند که برای ایجاد یک یا چند گره فرزند جدید در پایان فهرست گره‌های فرزند گرهٔ فعلی استفاده می‌شود. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | یک گره فرزند جدید در پایان فهرست گره‌های فرزند گرهٔ فعلی ایجاد می‌کند با استفاده از رشته داده XML مشخص شده. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | یک گره فرزند جدید در پایان فهرست گره‌های فرزند گرهٔ فعلی ایجاد می‌کند با استفاده از محتویات XML شی [XmlReader](../../system.xml/xmlreader/) مشخص‌شده. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | یک گره فرزند جدید در پایان فهرست گره‌های فرزند گرهٔ فعلی ایجاد می‌کند با استفاده از گره‌های موجود در [XPathNavigator](./) مشخص‌شده. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک گره عنصر فرزند جدید در پایان فهرست گره‌های فرزند گرهٔ فعلی ایجاد می‌کند با استفاده از پیشوند فضای نام، نام محلی و URI فضای نام مشخص‌شده همراه با مقدار مشخص‌شده. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | بررسی می‌کند که داده‌های XML در [XPathNavigator](./) مطابق با زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) ارائه‌شده باشد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، یک [XPathNavigator](./) جدید ایجاد می‌کند که در همان گره‌ای که این [XPathNavigator](./) قرار دارد، موقعیت دارد. |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | موقعیت [XPathNavigator](./) فعلی را با موقعیت [XPathNavigator](./) مشخص‌شده مقایسه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | یک رشته که نشانگر یک عبارت [XPath](../) است را کامپایل می‌کند و یک شی [XPathExpression](../xpathexpression/) برمی‌گرداند. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک گره ویژگی در گره عنصر فعلی ایجاد می‌کند با استفاده از پیشوند فضای نام، نام محلی و URI فضای نام مشخص‌شده همراه با مقدار مشخص‌شده. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | یک شی [XmlWriter](../../system.xml/xmlwriter/) برمی‌گرداند که برای ایجاد ویژگی‌های جدید بر روی عنصر فعلی استفاده می‌شود. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | یک نسخه از [XPathNavigator](./) را برمی‌گرداند. |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | یک محدوده از گره‌های هم‌سطح از گرهٔ فعلی تا گرهٔ مشخص‌شده را حذف می‌کند. |
| virtual void [DeleteSelf](./deleteself/)() | گرهٔ فعلی و گره‌های فرزند آن را حذف می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنابری [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عدد دوگانه به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | عبارت [XPath](../) مشخص‌شده را ارزیابی می‌کند و نتیجهٔ تایپی را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | عبارت [XPath](../) مشخص‌شده را ارزیابی می‌کند و نتیجهٔ تایپی را برمی‌گرداند، با استفاده از شی [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) مشخص‌شده برای حل پیشوندهای فضای نام در عبارت [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | [XPathExpression](../xpathexpression/) را ارزیابی می‌کند و نتیجهٔ تایپی را برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | از زمینهٔ فراهم‌شده برای ارزیابی [XPathExpression](../xpathexpression/) استفاده می‌کند و نتیجهٔ تایپی را برمی‌گرداند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، URI پایهٔ گرهٔ فعلی را دریافت می‌کند. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا [XPathNavigator](./) می‌تواند داده‌های XML زیرین را ویرایش کند. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی دارای هر ویژگی‌ای است. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی دارای گره فرزند است. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | نشانه‌گذاریی که گره‌های فرزند گرهٔ فعلی را نشان می‌دهد، برمی‌گرداند. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، مقداری را دریافت می‌کند که نشان می‌دهد آیا گرهٔ فعلی یک عنصر خالی بدون برچسب پایان است. |
| **bool** [get_IsNode](./get_isnode/)() override | مقداری را برمی‌گرداند که نشان می‌دهد آیا گرهٔ فعلی نمایانگر گرهٔ [XPath](../) است. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XPathNavigator::get_Name](./get_name/) گرهٔ فعلی را بدون هر پیشوند فضایی دریافت می‌کند. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، نام معتبر گرهٔ فعلی را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، URI فضای نام گرهٔ فعلی را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XmlNameTable](../../system.xml/xmlnametable/) [XPathNavigator](./) را دریافت می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | یک [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) برمی‌گرداند که برای مقایسهٔ مساویّت اشیا [XPathNavigator](./) استفاده می‌شود. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، XPathNodeType گرهٔ فعلی را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | نشانه‌گذاریی که برچسب‌های باز و بستهٔ گرهٔ فعلی و گره‌های فرزند آن را نشان می‌دهد، برمی‌گرداند. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، پیشوند فضای نام مرتبط با گرهٔ فعلی را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | اطلاعات طرحواره‌ای که به عنوان نتیجهٔ اعتبارسنجی طرحواره به گرهٔ فعلی اختصاص داده شده است، برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | گرهٔ فعلی را به عنوان یک شی بسته شده از مناسب‌ترین نوع برمی‌گرداند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | توسط پیاده‌سازی‌های [XPathNavigator](./) که یک نمای XML \"virtualized\" بر روی یک مخزن ارائه می‌دهند، برای دسترسی به اشیای زیرین استفاده می‌شود. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، مقدار **string** آیتم را دریافت می‌کند. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | مقدار گرهٔ فعلی را به‌عنوان [Boolean](../../system/boolean/) برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | مقدار گرهٔ فعلی را به‌عنوان [DateTime](../../system/datetime/) برمی‌گرداند. |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | مقدار گرهٔ فعلی را به‌عنوان [Double](../../system/double/) برمی‌گرداند. |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | مقدار گرهٔ فعلی را به‌عنوان [Int32](../../system/int32/) برمی‌گرداند. |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | مقدار گرهٔ فعلی را به‌عنوان [Int64](../../system/int64/) برمی‌گرداند. |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | نوع گرهٔ فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | دامنهٔ **xml:lang** گرهٔ فعلی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | اطلاعات XmlSchemaType گرهٔ فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | مقدار ویژگی با نام محلی و URI فضای نام مشخص‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیای سفارشی را فعال می‌کند. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | مقدار گرهٔ فضای نام مربوط به نام محلی مشخص‌شده را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | فضای‌نام‌های در دسترس گرهٔ فعلی را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | یک شی [XmlWriter](../../system.xml/xmlwriter/) برمی‌گرداند که برای ایجاد یک گره هم‌سطح جدید پس از گرهٔ انتخاب‌شده فعلی استفاده می‌شود. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | یک گره هم‌سطح جدید پس از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از رشته XML مشخص‌شده. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | یک گره هم‌سطح جدید پس از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از محتویات XML شی [XmlReader](../../system.xml/xmlreader/) مشخص‌شده. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | یک گره هم‌سطح جدید پس از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از گره‌های موجود در شی [XPathNavigator](./) مشخص‌شده. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | یک شی [XmlWriter](../../system.xml/xmlwriter/) برمی‌گرداند که برای ایجاد یک گره هم‌سطح جدید قبل از گرهٔ انتخاب‌شده فعلی استفاده می‌شود. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | یک گره هم‌سطح جدید قبل از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از رشته XML مشخص‌شده. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | یک گره هم‌سطح جدید قبل از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از محتویات XML شی [XmlReader](../../system.xml/xmlreader/) مشخص‌شده. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | یک گره هم‌سطح جدید قبل از گرهٔ انتخاب‌شده فعلی ایجاد می‌کند با استفاده از گره‌های موجود در [XPathNavigator](./) مشخص‌شده. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک عنصر هم‌سطح جدید پس از گرهٔ فعلی ایجاد می‌کند با استفاده از پیشوند فضای نام، نام محلی و URI فضای نام مشخص‌شده، همراه با مقدار مشخص‌شده. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک عنصر هم‌سطح جدید قبل از گرهٔ فعلی ایجاد می‌کند با استفاده از پیشوند فضای نام، نام محلی و URI فضای نام مشخص‌شده، همراه با مقدار مشخص‌شده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمایانگر یک نمونه از نوع توضیح‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | تعیین می‌کند آیا [XPathNavigator](./) مشخص‌شده یک فرزند از [XPathNavigator](./) فعلی است. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | زمانی که در کلاس مشتق‌شده بازنویسی شود، تعیین می‌کند آیا [XPathNavigator](./) فعلی در همان موقعیت [XPathNavigator](./) مشخص‌شده قرار دارد. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شی sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | URI فضای نام برای پیشوند مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | پیشوندی که برای URI فضای نام مشخص‌شده اعلام شده است را برمی‌گرداند. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | تعیین می‌کند آیا گرهٔ فعلی با [XPathExpression](../xpathexpression/) مشخص‌شده مطابقت دارد. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | تعیین می‌کند آیا گرهٔ فعلی با عبارت [XPath](../) مشخص‌شده مطابقت دارد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به همان موقعیت [XPathNavigator](./) مشخص‌شده جابجا می‌کند. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) را به ویژگی با نام محلی و URI فضای نام مطابقت‌یافته جابجا می‌کند. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) را به گره فرزند با نام محلی و URI فضای نام مشخص‌شده جابجا می‌کند. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) را به گره فرزند از XPathNodeType مشخص‌شده جابجا می‌کند. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | [XPathNavigator](./) را به اولین گره هم‌سطح گرهٔ فعلی جابجا می‌کند. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به اولین ویژگی گرهٔ فعلی جابجا می‌کند. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به اولین گره فرزند گرهٔ فعلی جابجا می‌کند. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | زمانی که در کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به اولین گره فضای نام که با XPathNamespaceScope مشخص‌شده مطابقت دارد جابجا می‌کند. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | [XPathNavigator](./) را به اولین گره فضای‌نامی گرهٔ جاری منتقل می‌کند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) را به عنصری که نام محلی و URI فضای‌نامی مشخص‌شده در ترتیب سند دارد منتقل می‌کند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./) را به عنصری که نام محلی و URI فضای‌نامی مشخص‌شده دارد، به مرز مشخص‌شده، در ترتیب سند منتقل می‌کند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) را به عنصر بعدی از XPathNodeType مشخص‌شده در ترتیب سند منتقل می‌کند. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./) را به عنصر بعدی از XPathNodeType مشخص‌شده، به مرز مشخص‌شده، در ترتیب سند منتقل می‌کند. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | وقتی در یک کلاس مشتق‌شده بازنویسی شود، به گره‌ای که دارای ویژگی از نوع **ID** است و مقدار آن با [String](../../system/string/) مطابقت دارد، منتقل می‌شود. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | [XPathNavigator](./) را به گرهٔ فضای‌نامی با پیشوند فضای‌نامی مشخص‌شده منتقل می‌کند. |
| virtual **bool** [MoveToNext](./movetonext/)() | وقتی در یک کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به گرهٔ برادر بعدی گرهٔ جاری منتقل می‌کند. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./) را به گرهٔ برادر بعدی که نام محلی و URI فضای‌نامی مشخص‌شده دارد منتقل می‌کند. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./) را به گرهٔ برادر بعدی گرهٔ جاری که با XPathNodeType مشخص‌شده مطابقت دارد، منتقل می‌کند. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | وقتی در یک کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به ویژگی بعدی منتقل می‌کند. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | وقتی در یک کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به گرهٔ فضای‌نامی بعدی که با XPathNamespaceScope مشخص‌شده مطابقت دارد، منتقل می‌کند. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | [XPathNavigator](./) را به گرهٔ فضای‌نامی بعدی منتقل می‌کند. |
| virtual **bool** [MoveToParent](./movetoparent/)() | وقتی در یک کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به گرهٔ والد گرهٔ جاری منتقل می‌کند. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | وقتی در یک کلاس مشتق‌شده بازنویسی شود، [XPathNavigator](./) را به گرهٔ برادر قبلی گرهٔ جاری منتقل می‌کند. |
| virtual void [MoveToRoot](./movetoroot/)() | [XPathNavigator](./) را به گرهٔ ریشه‌ای که گرهٔ جاری به آن تعلق دارد، منتقل می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همهٔ ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها با کپی‌سازی را فعال می‌کند. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها با کپی‌سازی را فعال می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | یک شیء [XmlWriter](../../system.xml/xmlwriter/) را بازمی‌گرداند که برای ایجاد گرهٔ فرزند جدید در ابتدای فهرست گره‌های فرزند گرهٔ جاری استفاده می‌شود. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | یک گرهٔ فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری با استفاده از رشتهٔ XML مشخص شده ایجاد می‌کند. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | یک گرهٔ فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری با استفاده از محتوای XML شیء [XmlReader](../../system.xml/xmlreader/) مشخص شده ایجاد می‌کند. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | یک گرهٔ فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری با استفاده از گره‌های موجود در شیء [XPathNavigator](./) مشخص شده ایجاد می‌کند. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | یک عنصر فرزند جدید را در ابتدای فهرست گره‌های فرزند گرهٔ جاری با استفاده از پیشوند فضای‌نامی، نام محلی و URI فضای‌نامی مشخص شده همراه با مقدار مشخص شده ایجاد می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | یک شیء [XmlReader](../../system.xml/xmlreader/) را بازمی‌گرداند که حاوی گرهٔ جاری و گره‌های فرزند آن است. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | شیء نوع مقدار را با nullptr از طریق مقایسه مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | بَرایه‌ای از گره‌های برادری را از گرهٔ جاری تا گرهٔ مشخص‌شده جایگزین می‌کند. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | گرهٔ جاری را با محتوای رشتهٔ مشخص شده جایگزین می‌کند. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | گرهٔ جاری را با محتویات شیء [XmlReader](../../system.xml/xmlreader/) مشخص شده جایگزین می‌کند. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | گرهٔ جاری را با محتویات شیء [XPathNavigator](./) مشخص شده جایگزین می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | یک مجموعهٔ گره را با استفاده از عبارت [XPath](../) مشخص شده انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | یک مجموعهٔ گره را با استفاده از عبارت [XPath](../) مشخص شده و شیء [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) مشخص شده برای حل پیشوندهای فضای‌نامی انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | یک مجموعهٔ گره را با استفاده از [XPathExpression](../xpathexpression/) مشخص شده انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | تمام گره‌های اجدادی گرهٔ جاری که XPathNodeType مطابق دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | تمام گره‌های اجدادی گرهٔ جاری که نام محلی و URI فضای‌نامی مشخص‌شده را دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | تمام گره‌های فرزند گرهٔ جاری که XPathNodeType مطابق دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | تمام گره‌های فرزند گرهٔ جاری که نام محلی و URI فضای‌نامی مشخص شده را دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | تمام گره‌های نزادی گرهٔ جاری که XPathNodeType مطابق دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | تمام گره‌های نزادی گرهٔ جاری که نام محلی و URI فضای‌نامی مشخص شده را دارند را انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | یک گرهٔ تک در [XPathNavigator](./) را با استفاده از پرس‌و‌جوی [XPath](../) مشخص شده انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | یک گرهٔ تک در شیء [XPathNavigator](./) را با استفاده از پرس‌و‌جوی [XPath](../) مشخص شده و شیء [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) برای حل پیشوندهای فضای‌نامی انتخاب می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | یک گرهٔ تک در [XPathNavigator](./) را با استفاده از شیء [XPathExpression](../xpathexpression/) مشخص شده انتخاب می‌کند. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | نشانه‌گذاری نمایانگر گره‌های فرزند گرهٔ جاری را تنظیم می‌کند. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | نشانه‌گذاری نمایانگر تگ‌های باز و بسته گرهٔ جاری و گره‌های فرزند آن را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | مقدار تایپ‌شدهٔ گرهٔ جاری را تنظیم می‌کند. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | مقدار گرهٔ جاری را تنظیم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | مقدار متنی گرهٔ جاری را بازمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت lock() در C# را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | مقدار گرهٔ جاری را به عنوان Type مشخص‌شده بازمی‌گرداند، به‌کمک شیء [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) برای حل پیشوندهای فضای‌نامی. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | مقدار آیتم را به عنوان نوع مشخص‌شده بازمی‌گرداند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | گرهٔ جاری و گره‌های فرزندش را به شیء [XmlWriter](../../system.xml/xmlwriter/) مشخص شده ارسال می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| نوع تعریف | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای shared pointer به یک نمونه از این کلاس است. |

## موارد مرتبط

* کلاس [XPathItem](../xpathitem/)
* کلاس [IXPathNavigable](../ixpathnavigable/)
* کلاس [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* فضای‌نام [System::Xml::XPath](../)
* کتابخانه [Aspose.Slides](../../)