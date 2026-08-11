---
title: IPresentationInfo
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات دربارهٔ فایل ارائه
type: docs
weight: 3420
url: /fa/aspose.slides/ipresentationinfo/
---
## کلاس IPresentationInfo

اطلاعات دربارهٔ فایل ارائه

```cpp
class IPresentationInfo : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [CheckPassword](./checkpassword/)([System::String](../../system/string/)) | بررسی می‌کند که آیا رمز عبور برای ارائه‌ای که با رمز باز محافظت شده است صحیح است یا خیر. |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | بررسی می‌کند که آیا رمز عبور برای تغییر یک ارائهٔ محافظت‌شده صحیح است یا خیر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیاء با استفاده از معانی [Object.Equals](../../system/object/equals/) در C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء از نوع مرجع به سبک C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء از نوع مقدار به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | مقدار True را برمی‌گرداند اگر ارائهٔ پیوست‌شده رمزنگاری شده باشد، در غیر این صورت False. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsPasswordProtected](./get_ispasswordprotected/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده با رمز برای باز کردن محافظت شده است یا خیر. |
| virtual [NullableBool](../nullablebool/) [get_IsWriteProtected](./get_iswriteprotected/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا ارائهٔ پیوست‌شده برای نوشتن محافظت شده است یا خیر. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | فرمت ارائهٔ پیوست‌شده را برمی‌گرداند. فقط-خواندنی [Slides::LoadFormat](../loadformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل C# متد [Object.GetHashCode()](../../system/object/gethashcode/). امکان هَش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# `is`. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری (lock) در C#. مستقیماً فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل C# متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نمونهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نمونهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [ReadDocumentProperties](./readdocumentproperties/)() | ویژگی‌های سند ارائهٔ پیوست‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان šامپلۀ nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل C# متد [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل (unlock) در C#. مستقیماً فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual void [UpdateDocumentProperties](./updatedocumentproperties/)([System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\>) | ویژگی‌های ارائهٔ پیوست‌شده را به‌روزرسانی می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteBindedPresentation](./writebindedpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | ارائهٔ پیوست‌شده را به جریان می‌نویسد. |
| virtual void [WriteBindedPresentation](./writebindedpresentation/)([System::String](../../system/string/)) | ارائهٔ پیوست‌شده را به فایل می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)