---
title: DirectoryInfo
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر مسیر سیستم فایل، یک پوشه‌ای که توسط این مسیر ارجاع داده می‌شود و متدهای نمونه برای دستکاری پوشه‌ها را فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 248
url: /fa/system.io/directoryinfo/
---
## کلاس DirectoryInfo

نمایانگر مسیر سیستم فایل، یک پوشه‌ای که توسط این مسیر ارجاع داده می‌شود و متدهای نمونه برای دستکاری پوشه‌ها را فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال آن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Create](./create/)() | یک پوشه در مسیری که توسط شیء فعلی نمایانده می‌شود ایجاد می‌کند. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | زیرپوشه‌ها را در مسیر مشخص شده ایجاد می‌کند. |
| void [Delete](./delete/)() override | اگر پوشه خالی باشد، پوشه‌ای که توسط مسیر نمایانده شده توسط شیء فعلی ارجاع داده می‌شود را حذف می‌کند. |
| void [Delete](./delete/)(**bool**) | پوشه‌ای که توسط مسیر نمایانده شده توسط شیء فعلی ارجاع داده می‌شود را حذف می‌کند. یک پارامتر مشخص می‌کند که آیا محتوای پوشه به صورت بازگشتی حذف شود اگر پوشه خالی نباشد. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | یک نمونه از کلاس [DirectoryInfo](./) را در مسیر مشخص شده می‌سازد. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | یک مجموعه قابل پیمایش شامل تمام پوشه‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | پوشه‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | پوشه‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | یک مجموعه قابل پیمایش شامل تمام فایل‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | فایل‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | یک مجموعه قابل پیمایش شامل تمام فایل‌ها و پوشه‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | کاری انجام نمی‌دهد. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | ویژگی‌های موجودیتی که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | زمان ایجاد موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | زمان ایجاد موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| **bool** [get_Exists](./get_exists/)() override | تشخیص می‌دهد که آیا مسیر نمایانده شده توسط شیء فعلی به یک پوشه موجود اشاره دارد یا خیر. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | پسوند فایل نمایانده شده توسط شیء فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | نام کامل (شامل مسیر) موجودیتی که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | آخرین زمان دسترسی به موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | آخرین زمان دسترسی به موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | آخرین زمان نوشتن موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | آخرین زمان نوشتن موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() override | نام موجودیتی که توسط مسیر نمایانده شده توسط شیء فعلی ارجاع داده می‌شود را برمی‌گرداند. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | یک اشاره‌گر مشترک به شیء [DirectoryInfo](./) که مسیر ارجاع‌دهنده به پوشه والد پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | یک اشاره‌گر مشترک به شیء [DirectoryInfo](./) که مسیر ارجاع‌دهنده به پوشه ریشه پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [DirectoryInfo](./) که تمام پوشه‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را نشان می‌دهند، برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | پوشه‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | پوشه‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [FileInfo](../fileinfo/) که تمام پوشه‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را نشان می‌دهند، برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | فایل‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [FileSystemInfo](../filesysteminfo/) که تمام فایل‌ها و پوشه‌های واقع در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود را نشان می‌دهند، برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود، جستجو می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء فعلی نمایانده می‌شود یا در کل درخت پوشه‌ای که از آن ریشه دارد، جستجو می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به طور مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | پوشه‌ای که توسط شیء فعلی نمایانده می‌شود و تمام محتوای آن را به مکان مشخص شده منتقل می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| void [Refresh](../filesysteminfo/refresh/)() | وضعیت شیء فعلی را تازه‌سازی می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | ویژگی‌های مشخص‌شده را بر موجودیتی که توسط شیء فعلی نمایانده می‌شود تنظیم می‌کند. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی به موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی به موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیتی که توسط شیء فعلی نمایانده می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | یک رشته حاوی مسیر نمایانده شده توسط شیء فعلی را برمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. به طور مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [FileSystemInfo](../filesysteminfo/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)