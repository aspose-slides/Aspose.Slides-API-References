---
title: FileSystemInfo
second_title: مرجع API Aspose.Slides برای C++
description: "کلاس پایه برای FileInfo و DirectoryInfo. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 300
url: /fa/system.io/filesysteminfo/
---
## کلاس FileSystemInfo

کلاس پایه برای [FileInfo](../fileinfo/) و [DirectoryInfo](../directoryinfo/). اشیای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class FileSystemInfo : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Delete](./delete/)() | موجودیتی که توسط شیء فعلی نمایان می‌شود را حذف می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ای شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ای شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Finalize](./finalize/)() | کاری انجام نمی‌دهد. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | خصوصیات موجودی که توسط شیء فعلی نمایان می‌شود را برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | زمان ایجاد موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | زمان ایجاد موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| virtual **bool** [get_Exists](./get_exists/)() | تشخیص می‌دهد آیا موجودی که توسط مسیر شیء فعلی ارجاع داده می‌شود وجود دارد یا نه. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | پسوند فایل نمایان‌شده توسط شیء فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | نام کامل (شامل مسیر) موجودی که توسط شیء فعلی نمایان می‌شود را برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | آخرین زمان دسترسی موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | آخرین زمان دسترسی موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | آخرین زمان نوشتن موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | آخرین زمان نوشتن موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC برمی‌گرداند. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | نام موجودی که توسط شیء فعلی نمایان می‌شود را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری توسط عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| void [Refresh](./refresh/)() | وضعیت شیء فعلی را تازه‌سازی می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | خصوصیات مشخص‌شده را بر روی موجودی که توسط شیء فعلی نمایان می‌شود تنظیم می‌کند. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | زمان ایجاد موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان دسترسی موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان محلی تنظیم می‌کند. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودی که توسط شیء فعلی نمایان می‌شود را به عنوان زمان UTC تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از شناسه‌های هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن، از شناسه‌های هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل توسط عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از شناسه‌های هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیلاً فراخوانی شود؛ به جای آن، از شناسه‌های هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)