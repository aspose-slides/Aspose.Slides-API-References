---
title: DSACryptoServiceProvider
second_title: مرجع API Aspose.Slides برای C++
description: "الگوریتم DSA به شکل CSP. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های assertion می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچانید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 144
url: /fa/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider کلاس

[DSA](../dsa/) الگوریتم در فرم CSP. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های Assertion می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچانید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | تمام منابع را آزاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)() | یک پیاده‌سازی پیش‌فرض الگوریتم [DSA](../dsa/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [String](../../system/string/)\&) | یک پیاده‌سازی پیش‌فرض الگوریتم [DSA](../dsa/) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(**int32_t**) | یک پیاده‌سازی پیش‌فرض الگوریتم [DSA](../dsa/) با سایز کلید مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [DSAParameters](../dsaparameters/)\&) | یک پیاده‌سازی پیش‌فرض الگوریتم [DSA](../dsa/) با پارامترهای مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [CreateFromXmlString](../dsa/createfromxmlstring/)(const [String](../../system/string/)\&) | یک پیاده‌سازی پیش‌فرض الگوریتم [DSA](../dsa/) با پارامترهای رمزگذاری‌شده XML ایجاد می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) override | امضای [DSA](../dsa/) را برای داده مشخص‌شده ایجاد می‌کند. |
| void [Dispose](./dispose/)() override | داده‌های مرتبط با شیء را آزاد می‌کند. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | سازنده. از پارامترهای پیش‌فرض استفاده می‌کند. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [DSAParameters](../dsaparameters/)\&) | سازنده. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | سازنده. پیاده‌سازی نشده. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**) | سازنده. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | سازنده. پیاده‌سازی نشده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | بروبیی (blob) با اطلاعات کلید را صادر می‌کند. پیاده‌سازی نشده. |
| [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | پارامترهای CSP را صادر می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [FromXmlString](../dsa/fromxmlstring/)([String](../../system/string/)) override | شیء را با استفاده از پارامترهای رمزگذاری‌شده XML مقداردهی اولیه می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | یک شیء [CspKeyContainerInfo](../cspkeycontainerinfo/) را برمی‌گرداند. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | الگوریتم تبادل کلید مرتبط با شیء را بررسی می‌کند. |
| **int32_t** [get_KeySize](./get_keysize/)() override | سایز کلید را برمی‌گرداند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | آرایه‌ای از سایزهای کلید مجاز را برمی‌گرداند. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | بررسی می‌کند که آیا کلید در شیء CSP حفظ شده است یا نه. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | بررسی می‌کند که آیا فقط کلید عمومی در شیء CSP موجود است یا نه. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | الگوریتم امضایی که باید استفاده شود را برمی‌گرداند. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | بررسی می‌کند که آیا کلید در مخزن ماشین به جای مخزن کاربر حفظ می‌شود یا نه. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | بروبیی (blob) با اطلاعات کلید را وارد می‌کند. پیاده‌سازی نشده. |
| void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) override | تمام پارامترها را از ساختار داده وارد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نشانه‌ای از نوع توضیح‌داده‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده نسخه‌برداری. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | سایز کلید را تنظیم می‌کند. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | تعریف می‌کند که آیا کلید در شیء CSP حفظ می‌شود یا نه. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | تعریف می‌کند که آیا کلید در مخزن ماشین به جای مخزن کاربر حفظ می‌شود یا نه. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | امضای مقدار ورودی مشخص‌شده را محاسبه می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | امضای مقدار ورودی مشخص‌شده را محاسبه می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | امضای مقدار ورودی مشخص‌شده را محاسبه می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | مقدار هش داده‌های مشخص‌شده را با استفاده از الگوریتم هش تعیین‌شده محاسبه کرده و نتیجه را امضا می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | مقدار هش داده‌های مشخص‌شده را با استفاده از الگوریتم هش تعیین‌شده محاسبه کرده و نتیجه را امضا می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش تعیین‌شده محاسبه کرده و نتیجه را امضا می‌کند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | امضای مقدار ورودی مشخص‌شده را محاسبه می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| [String](../../system/string/) [ToXmlString](../dsa/toxmlstring/)(**bool**) override | تمام پارامترها را در قالب XML صادر می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را از حالت قفل‌دار خارج می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | امضای داده را بررسی می‌کند. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | تأیید می‌کند که امضای داده مشخص‌شده معتبر است. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | تأیید می‌کند که امضای داده مشخص‌شده معتبر است. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | تأیید می‌کند که امضای جریان باینری مشخص‌شده معتبر است. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | امضای داده را بررسی می‌کند. |
| **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | امضای [DSA](../dsa/) را برای داده مشخص‌شده تأیید می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [DSA](../dsa/)
* کلاس [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* فضای‌نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)