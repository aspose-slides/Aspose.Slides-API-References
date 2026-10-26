---
title: XmlSchemaSet
second_title: Aspose.Slides برای مرجع API C++
description: یک حافظهٔ کش از اسکیماهای تعریف زبان XML Schema (XSD) را شامل می‌شود.
type: docs
weight: 781
url: /fa/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet کلاس

حاوی یک کش از اسکیماهای تعریف زبان XML [Schema](../) (XSD) است.

```cpp
class XmlSchemaSet : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | اسکیماهای تعریف زبان XML [Schema](../) (XSD) را در URL مشخص شده به [XmlSchemaSet](./) اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | اسکیماهای تعریف زبان XML [Schema](../) (XSD) که در [XmlReader](../../system.xml/xmlreader/) موجود است را به [XmlSchemaSet](./) اضافه می‌کند. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) داده‌شده را به [XmlSchemaSet](./) اضافه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | [XmlSchema](../xmlschema/) ارائه‌شده را به [XmlSchemaSet](./) اضافه می‌کند. |
| void [Compile](./compile/)() | اسکیماهای تعریف زبان XML [Schema](../) (XSD) که به [XmlSchemaSet](./) اضافه شده‌اند را به یک اسکیما منطقی کامپایل می‌کند. |
| **bool** [Contains](./contains/)([String](../../system/string/)) | نشان می‌دهد آیا یک اسکیما تعریف زبان XML [Schema](../) (XSD) با فضای‌نام هدف مشخص در [XmlSchemaSet](./) وجود دارد یا نه. |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | نشان می‌دهد آیا شیء [XmlSchema](../xmlschema/) تعریف زبان XML [Schema](../) (XSD) مشخص‌شده در [XmlSchemaSet](./) وجود دارد یا نه. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | تمام شیء [XmlSchema](../xmlschema/) را از [XmlSchemaSet](./) به آرایه داده‌شده کپی می‌کند، شروع از ایندکس مشخص‌شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) مربوط به [XmlSchemaSet](./) را برمی‌گرداند. |
| **int32_t** [get_Count](./get_count/)() | تعداد اسکیماهای منطقی XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | تمام ویژگی‌های سراسری در تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | تمام المان‌های سراسری در تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | تمام انواع ساده و پیچیده سراسری در تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) را برمی‌گرداند. |
| **bool** [get_IsCompiled](./get_iscompiled/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) کامپایل شده‌اند یا نه. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | [XmlNameTable](../../system.xml/xmlnametable/) پیش‌فرضی که توسط [XmlSchemaSet](./) هنگام بارگذاری اسکیماهای جدید XML [Schema](../) (XSD) استفاده می‌شود را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هشش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن بیانیه lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء پیش‌پا [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr برحسب مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | اسکیما تعریف زبان XML [Schema](../) (XSD) مشخص‌شده را از [XmlSchemaSet](./) حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | اسکیما تعریف زبان XML [Schema](../) (XSD) مشخص‌شده و تمام اسکیماهای وارد‌شده توسط آن را از [XmlSchemaSet](./) حذف می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | اسکیما تعریف زبان XML [Schema](../) (XSD) که در حال حاضر در [XmlSchemaSet](./) وجود دارد را دوباره پردازش می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | یک مجموعه از تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | یک مجموعه از تمام اسکیماهای تعریف زبان XML [Schema](../) (XSD) موجود در [XmlSchemaSet](./) که به فضای‌نام داده‌شده تعلق دارند را برمی‌گرداند. |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) برای [XmlSchemaSet](./) را تنظیم می‌کند. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlResolver](../../system.xml/xmlresolver/) استفاده‌شده برای حل فضای‌نام یا مکان‌های ارجاع‌شده در عناصر include و import یک اسکیما را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیانیه lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء پیش‌پا [LockContext](../../system/lockcontext/) استفاده شود. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | یک هندلر رویداد برای دریافت اطلاعات دربارهٔ خطاهای اعتبارسنجی اسکیما تعریف زبان XML [Schema](../) (XSD) اضافه می‌کند. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | یک هندلر رویداد برای دریافت اطلاعات دربارهٔ خطاهای اعتبارسنجی اسکیما تعریف زبان XML [Schema](../) (XSD) حذف می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع weak را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع weak را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
|  [XmlSchemaSet](./xmlschemaset/)() | یک نمونه جدید از کلاس [XmlSchemaSet](./) را مقداردهی اولیه می‌کند. |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | یک نمونه جدید از کلاس [XmlSchemaSet](./) را با [XmlNameTable](../../system.xml/xmlnametable/) مشخص‌شده مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای shared pointer به نمونه‌ای از این کلاس است. |

## توضیحات

شیءهای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌های این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به‌عنوان آرگومان استفاده کنید. 

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)