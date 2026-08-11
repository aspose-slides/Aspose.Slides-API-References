---
title: ProtectionManager
second_title: Aspose.Slides برای C++ مرجع API
description: مدیریت حفاظت با گذرواژهٔ ارائه.
type: docs
weight: 4915
url: /fa/aspose.slides/protectionmanager/
---
## کلاس ProtectionManager

[Presentation](../presentation/) مدیریت حفاظت با گذرواژه.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | مشخص می‌کند که آیا یک ارائه برای اصلاح با رمز محافظت شده است یا خیر. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | [Presentation](../presentation/) را با گذرواژهٔ مشخص‌شده رمزنگاری می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | این ویژگی زمانی معنا دارد که ارائه با رمز محافظت شده باشد. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزنگاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزنگاری شده است. فقط خواندنی **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | گرفتن گذرواژه‌ای که برای رمزنگاری ارائه استفاده می‌شود. فقط خواندنی [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | دریافت مقداری که نشان می‌دهد آیا این نمونه رمزنگاری شده است یا خیر. فقط خواندنی **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | این ویژگی زمانی معنا دارد که فایل ارائه با رمز محافظت شده باشد و ویژگی‌های سند این فایل عمومی باشند. مقدار true به این معنی است که تنها ویژگی‌های سند از یک فایل ارائه رمزنگاری‌شده بدون استفاده از گذرواژه بارگیری می‌شود. مقدار false به این معنی است که تمام ارائه رمزنگاری‌شده با استفاده از گذرواژهٔ صحیح بارگیری می‌شود، نه فقط ویژگی‌های سند. اگر ارائه رمزنگاری نشده باشد، مقدار ویژگی همیشه false است. اگر ویژگی‌های سند یک فایل رمزنگاری‌شده عمومی نباشند، مقدار ویژگی همیشه false است. اگر Presentation.EncryptDocumentProperties برابر true باشد، مقدار ویژگی IsOnlyDocumentPropertiesLoaded همیشه false است. فقط خواندنی **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | دریافت مقداری که نشان می‌دهد آیا این ارائه از نوشتن محافظت شده است یا خیر. فقط خواندنی **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | دریافت توصیهٔ فقط-خواندنی. خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور lock() در C#. مستقیم فراخوانی شود یا از شیء سرنگر [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کپی‌برداری از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شیء. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌بردار. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌بردار از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌بردار از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemoveEncryption](./removeencryption/)() override | رمزنگاری را حذف می‌کند. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | محافظت نوشتن برای این ارائه را حذف می‌کند. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | این ویژگی زمانی معنا دارد که ارائه با رمز محافظت شده باشد. اگر true باشد، ویژگی‌های سند در فایل ارائه رمزنگاری می‌شوند. اگر false باشد، ویژگی‌های سند عمومی هستند در حالی که ارائه رمزنگاری شده است. نوشتنی **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | تعیین توصیهٔ فقط-خواندنی. نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان nام الگو به یک اشاره‌گر ضعیف (به‌جای مشترک). امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | محافظت نوشتن برای این ارائه را با گذرواژهٔ مشخص تنظیم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ ارجاع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای آزادسازی قفل دستور lock() در C#. مستقیم فراخوانی شود یا از شیء سرنگر [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## ارجاع‌ها

* کلاس [IProtectionManager](../iprotectionmanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)