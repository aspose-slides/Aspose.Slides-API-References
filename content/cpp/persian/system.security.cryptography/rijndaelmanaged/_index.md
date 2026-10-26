---
title: RijndaelManaged
second_title: "مرجع API Aspose.Slides برای C++"
description: "الگوریتم Rijndael مدیریت‌شده. فقط حالت‌های ECB و CFB با پدینگ None و حالت CBC با پدینگ‌های None و Zeros را پشتیبانی می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همواره این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 417
url: /fa/system.security.cryptography/rijndaelmanaged/
---
## RijndaelManaged کلاس


Managed [Rijndael](../rijndael/) algorithm. Only supports ECB and CFB modes with None padding and CBC mode with None and Zeros paddings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RijndaelManaged : public System::Security::Cryptography::Rijndael
```

## متدها

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | ایجاد یک نمونه از الگوریتم. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ایجاد شیء رمزگشای با پارامترهای صریح. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | ایجاد شیء رمزگشای با پارامترهای تعریف‌شده توسط شیء الگوریتم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ایجاد شیء رمزگشای با پارامترهای تعریف‌شده توسط شیء الگوریتم. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ایجاد شیء رمزنگار با پارامترهای صریح. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | ایجاد شیء رمزنگار با پارامترهای تعریف‌شده توسط شیء الگوریتم. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ایجاد شیء رمزنگار با پارامترهای تعریف‌شده توسط شیء الگوریتم. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسه اشیاء با استفاده از معنای C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسه اشیاء نوع ارجاعی به سبک C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسه اشیاء نوع مقداری به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [GenerateIV](./generateiv/)() override | ایجاد مقدار اولیه تصادفی و ذخیره آن در درون‌ریزی‌های الگوریتم. |
| void [GenerateKey](./generatekey/)() override | ایجاد کلید تصادفی و ذخیره آن در درون‌ریزی‌های الگوریتم. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | دریافت اندازه بلوک عملیات رمزنگاری. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | دریافت اندازه بازخورد عملیات رمزنگاری. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | دریافت مقدار اولیه عملیات رمزنگاری. اگر هنوز ایجاد نشده باشد، جدید ایجاد می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | دریافت کلید عملیات رمزنگاری. اگر هنوز ایجاد نشده باشد، جدید ایجاد می‌کند. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | دریافت اندازه کلید عملیات رمزنگاری. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | دریافت حالت عملیات رمزنگاری. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | دریافت پدینگ عملیات رمزنگاری. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده مرجع مرتبط با شیء. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی اینکه آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان C# lock(). به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلیون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شیء. همه ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقایسه اشیاء بر اساس مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقایسه اشیاء بر اساس مرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | کاهش شمارنده مرجع مشترک به مقدار مشخص‌شده. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | تنظیم اندازه بلوک عملیات رمزنگاری. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | تنظیم اندازه بازخورد عملیات رمزنگاری. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تنظیم مقدار اولیه عملیات رمزنگاری. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | تنظیم کلید عملیات رمزنگاری. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | تنظیم اندازه کلید عملیات رمزنگاری. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | تنظیم حالت عملیات رمزنگاری. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | تنظیم پدینگ عملیات رمزنگاری. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان nام الگو به عنوان weak pointer (به جای shared). امکان تعویض اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارنده مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارنده مرجع مشترک. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش و برگرداندن شمارنده مرجع مشترک. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل بیان C# lock(). به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | بررسی اعتبار اندازه کلید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارنده مرجع weak. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارنده مرجع weak. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | از بین بردن شیء. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Rijndael](../rijndael/)
* فضای‌نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)