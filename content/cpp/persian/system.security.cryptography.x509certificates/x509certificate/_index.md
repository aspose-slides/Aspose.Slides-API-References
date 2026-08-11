---
title: X509Certificate
second_title: Aspose.Slides برای C++ مرجع API
description: "گواهی X.509 نسخه 3. گواهی‌های رمزنگاری‌شده پشتیبانی نمی‌شوند. فقط پرچم X509KeyStorageFlags::DefaultKeySet پشتیبانی می‌شود. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را در پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 27
url: /fa/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate کلاس

گواهی X.509 نسخه 3. گواهی‌های رمزنگاری‌شده پشتیبانی نمی‌شوند. فقط پرچم [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) پشتیبانی می‌شود. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## متدها

| متد | توضیح |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | یک گواهی را از فایل PKCS7 مشخص شده ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | یک گواهی را از فایل امضا شده مشخص شده ایجاد می‌کند. |
| void [Dispose](./dispose/)() override | کاری انجام نمی‌دهد. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | دو گواهی را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | شیء فعلی را به آرایه بایت با استفاده از فرمت مشخص صادر می‌کند. پیاده‌سازی نشده. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | شیء فعلی را به آرایه بایت با استفاده از فرمت مشخص صادر می‌کند. پیاده‌سازی نشده. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | شیء فعلی را به آرایه بایت با استفاده از فرمت مشخص صادر می‌کند. پیاده‌سازی نشده. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| IntPtr [get_Handle](./get_handle/)() const | یک هندل به زمینه گواهی Microsoft Cryptographic API دریافت می‌کند. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | نام مرجع گواهی که گواهی X.509v3 را صادر کرده است، دریافت می‌کند. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | نام متمایز موضوع را از گواهی دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | هش شیء فعلی را به صورت آرایه بایت دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | هش شیء فعلی را به صورت آرایه بایت دریافت می‌کند. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | هش [SHA1](../../system.security.cryptography/sha1/) شیء فعلی را به صورت رشته هگزادسیمال دریافت می‌کند. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | هش [SHA1](../../system.security.cryptography/sha1/) شیء فعلی را به صورت رشته هگزادسیمال دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | تاریخ اعتبار گواهی فعلی را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | تاریخ انقضای گواهی فعلی را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | نام فرمت گواهی را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | کد هش گواهی را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | نام مرجع صدور گواهی که گواهی فعلی را صادر کرده است را دریافت می‌کند. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | اطلاعات کلید گواهی فعلی را به صورت رشته دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | اطلاعات کلید گواهی فعلی را به صورت آرایه بایت دریافت می‌کند. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | اطلاعات کلید گواهی فعلی را به صورت رشته هگزادسیمال دریافت می‌کند. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | نام شخصی که گواهی فعلی برای او صادر شده است را دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | کلید عمومی را از گواهی به صورت آرایه بایت دریافت می‌کند. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | کلید عمومی را از گواهی به صورت رشته هگزادسیمال دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | داده‌های خام گواهی را به صورت آرایه بایت دریافت می‌کند. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | داده‌های خام گواهی را به صورت رشته هگزادسیمال دریافت می‌کند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | شماره سریال گواهی را به صورت آرایه بایت دریافت می‌کند. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | شماره سریال گواهی را به صورت رشته هگزادسیمال دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | اطلاعات را از فایل گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | اطلاعات را از فایل گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | اطلاعات را از داده‌های گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | اطلاعات را از داده‌های گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | اطلاعات را از فایل گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | اطلاعات را از داده‌های گواهی مشخص شده وارد می‌کند. پیاده‌سازی نشده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# `is`. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل C# lock() را انجام می‌دهد. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع مقدار نوعی با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [Reset](./reset/)() | وضعیت گواهی را بازنشانی می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | مقدار nام آرگومان قالب را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | اطلاعات گواهی را به قالب متنی برمی‌گرداند. |
| [String](../../system/string/) [ToString](./tostring/)() const override | اطلاعات گواهی را به قالب متنی برمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی قفل C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## تعاریف

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | نوع اشاره‌گر. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)