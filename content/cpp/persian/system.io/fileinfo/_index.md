---
title: FileInfo
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایانگر مسیری به یک فایل و فایلی است که توسط این مسیر ارجاع داده می‌شود و روش‌هایی برای دستکاری آن فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 274
url: /fa/system.io/fileinfo/
---
## کلاس FileInfo

نمایانگر مسیری به یک فایل و فایلی است که توسط این مسیر ارجاع داده می‌شود و روش‌هایی برای دستکاری آن فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بسته‌بندی کنید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## متدها

| متد | توضیح |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | فایلی که توسط شی جاری نمایانده می‌شود را برای نوشتن متن با استفاده از رمزگذاری UTF-8، در حالت «Append» بدون اشتراک باز می‌کند. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | فایلی که توسط شی جاری نمایانده می‌شود را به مکان مشخص شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، کپی کردن شکست می‌خورد. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | فایلی که توسط شی جاری نمایانده می‌شود را به مکان مشخص شده کپی می‌کند. یک پارامتر مشخص می‌کند که آیا فایل مقصد موجود باید بازنویسی شود یا خیر. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | فایلی در مکانی که توسط مسیر شی جاری نمایانده می‌شود ایجاد می‌کند و آن را برای خواندن و نوشتن، در حالت truncate و بدون اشتراک باز می‌کند. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | فایلی در مکانی که توسط مسیر شی جاری نمایانده می‌شود ایجاد می‌کند و آن را برای نوشتن متن با استفاده از رمزگذاری UTF-8 و بدون اشتراک باز می‌کند. |
| void [Decrypt](./decrypt/)() | NOT IMPLEMENTED. |
| void [Delete](./delete/)() override | فایلی که توسط شی جاری نمایانده می‌شود را حذف می‌کند. |
| void [Encrypt](./encrypt/)() | NOT IMPLEMENTED. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN به هیچ مقدار، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN به هیچ مقدار، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | نمونهٔ جدیدی از کلاس [FileInfo](./) می‌سازد که فایل مشخص شده را نمایانده می‌شود. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | کاری انجام نمی‌دهد. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | ویژگی‌های موجودیتی که توسط شی جاری نمایانده می‌شود را بر می‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | زمان ایجاد موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی بر می‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | زمان ایجاد موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC بر می‌گرداند. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | شیء [DirectoryInfo](../directoryinfo/)ی را بر می‌گرداند که دایرکتوری‌ای را نشان می‌دهد که فایل نمایانده‌شده توسط شی جاری در آن قرار دارد. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | نام کامل دایرکتوری‌ای که فایل نمایانده‌شده توسط شی جاری در آن واقع است را بر می‌گرداند. |
| **bool** [get_Exists](./get_exists/)() override | مقداری را بر می‌گرداند که نشان می‌دهد آیا فایل وجود دارد یا خیر. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | پسوند فایلی که توسط شی جاری نمایانده می‌شود را بر می‌گرداند. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | نام کامل (شامل مسیر) موجودیتی که توسط شی جاری نمایانده می‌شود را بر می‌گرداند. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | مقداری را بر می‌گرداند که نشان می‌دهد آیا ویژگی ReadOnly تنظیم شده است یا خیر. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | آخرین زمان دسترسی به موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی بر می‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | آخرین زمان دسترسی به موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC بر می‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | آخرین زمان نوشتن موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی بر می‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | آخرین زمان نوشتن موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC بر می‌گرداند. |
| **int64_t** [get_Length](./get_length/)() | اندازهٔ فایل را به بایت بر می‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() override | نام فایل را بر می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایان‌دهندهٔ نمونه‌ای از نوعی است که توسط targetType توصیف شده. مشابه عملگر «is» در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیانیهٔ lock() در C#. مستقیماً فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | فایل نمایانده‌شده توسط شی جاری را به مکان مشخص شده منتقل می‌کند. |
| [Object](../../system/object/object/)() | شیء را می‌سازد. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | فایلی که توسط شی جاری نمایانده می‌شود را در حالت مشخص‌شده برای خواندن و نوشتن و بدون اشتراک باز می‌کند. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | فایلی که توسط شی جاری نمایانده می‌شود را در حالت مشخص‌شده، با نوع دسترسی مشخص و بدون اشتراک باز می‌کند. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | فایلی که توسط شی جاری نمایانده می‌شود را در حالت مشخص‌شده، با نوع دسترسی مشخص و گزینهٔ اشتراک باز می‌کند. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | فایلی که توسط شی جاری نمایانده می‌شود را فقط برای خواندن، در حالت «Open» با دسترسی مشترک برای خواندن باز می‌کند. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | فایلی موجود در مکانی که توسط مسیر شی جاری نمایانده می‌شود را برای خواندن متن با استفاده از رمزگذاری UTF-8 و بدون اشتراک باز می‌کند. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | فایلی که توسط شی جاری نمایانده می‌شود را فقط برای نوشتن، در حالت «OpenOrCreate» و بدون اشتراک باز می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مقدار مرجع شیء مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| void [Refresh](../filesysteminfo/refresh/)() | وضعیت شیء جاری را تازه‌سازی می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | محتویات یک فایل مقصد مشخص را با فایلی که توسط شی [FileInfo](./) جاری نمایانده می‌شود جایگزین می‌کند و یک پشتیبان از فایل جایگزین‌شده ایجاد می‌نماید. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | محتویات یک فایل مقصد مشخص را با فایلی که توسط شی [FileInfo](./) جاری نمایانده می‌شود جایگزین می‌کند و یک پشتیبان از فایل جایگزین‌شده ایجاد می‌نماید. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | ویژگی‌های مشخص‌شده را بر موجودیتی که توسط شی جاری نمایانده می‌شود تنظیم می‌کند. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | ویژگی ReadOnly را برای فایل تنظیم یا غیرفعال می‌کند. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیتی که توسط شی جاری نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n-ام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان سوئیچ کردن اشاره‌گرها در مجموعه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را بر می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | مسیری را که توسط شی جاری نمایانده می‌شود بر می‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازندهٔ C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی قفل‌گذاری بیانیهٔ lock() در C# برای بازکردن قفل. مستقیماً فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## همچنین ببینید

* کلاس [FileSystemInfo](../filesysteminfo/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)