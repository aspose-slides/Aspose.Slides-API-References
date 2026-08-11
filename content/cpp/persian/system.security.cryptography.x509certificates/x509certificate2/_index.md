---
title: X509Certificate2
second_title: مرجع API Aspose.Slides برای C++
description: "نماینده گواهی X509 است. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا باعث خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 40
url: /fa/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 کلاس

نماینده گواهی X509. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## متدها

| متد | توضیح |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | یک گواهی از فایل PKCS7 مشخص ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | یک گواهی از فایل امضاشدهٔ مشخص ایجاد می‌کند. |
| void [Dispose](../x509certificate/dispose/)() override | کاری انجام نمی‌دهد. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | دو گواهی را مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | شیء فعلی را با استفاده از فرمت مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | شیء فعلی را با استفاده از فرمت مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | شیء فعلی را با استفاده از فرمت مشخص به یک آرایه بایت صادر می‌کند. پیاده‌سازی نشده. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_Archived](./get_archived/)() const | مقداری را برمی‌گرداند که نشان می‌دهد گواهی بایگانی شده است. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | مجموعه‌ای از اشیای افزونهٔ مرتبط با گواهی را برمی‌گرداند. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | نام دوستانهٔ گواهی را برمی‌گرداند. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | دستگاهی به زمینهٔ گواهی Microsoft Cryptographic API را برمی‌گرداند. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | بررسی می‌کند که آیا گواهی کلید خصوصی دارد یا نه. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | نام مرجع صدور گواهی که گواهی X.509v3 را صادر کرده است را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | نام طرفی که گواهی را صادر کرده است را برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | تاریخ و زمان محلی را که پس از آن گواهی دیگر معتبر نیست، برمی‌گرداند. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | تاریخ و زمان محلی را که گواهی در آن معتبر می‌شود، برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | کلید خصوصی مرتبط با گواهی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | یک شیء [PublicKey](../publickey/) گواهی را برمی‌گرداند. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | دادهٔ خام گواهی را برمی‌گرداند. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | شماره سریال گواهی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | الگوریتم مورد استفاده برای ایجاد امضای گواهی را برمی‌گرداند. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | نام متمایز موضوع را از گواهی برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | نام موضوع را از گواهی برمی‌گرداند. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | اثر انگشت گواهی را برمی‌گرداند. |
| **int32_t** [get_Version](./get_version/)() const | نسخهٔ فرمت گواهی را برمی‌گرداند. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | نوع گواهی موجود در آرایهٔ بایت مشخص را برمی‌گرداند. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | نوع گواهی موجود در فایل مشخص را برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | هش شیء فعلی را به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | هش شیء فعلی را به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | هش [SHA1](../../system.security.cryptography/sha1/) شیء فعلی را به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | هش [SHA1](../../system.security.cryptography/sha1/) شیء فعلی را به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | کلید خصوصی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند؛. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | کلید عمومی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | کلید خصوصی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند؛. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | کلید عمومی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | تاریخ اعتباردهی گواهی فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | تاریخ انقضای گواهی فعلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | نام فرمت گواهی را برمی‌گرداند. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | کد هش گواهی را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | نام مرجع صدور گواهی که گواهی فعلی را صادر کرده است را برمی‌گرداند. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | اطلاعات کلید گواهی فعلی را به صورت رشته برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | اطلاعات کلید گواهی فعلی را به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | اطلاعات کلید گواهی فعلی را به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | نام شخص اصلی که گواهی فعلی برای آن صادر شده است را برمی‌گرداند. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | نام موضوع یا صادرکننده را از گواهی برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | کلید عمومی را از گواهی به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | کلید عمومی را از گواهی به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | دادهٔ خام را از گواهی به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | دادهٔ خام را از گواهی به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | کلید خصوصی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند؛. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | کلید عمومی [RSA](../../system.security.cryptography/rsa/) را برمی‌گرداند. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | شماره سریال را از گواهی به صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | شماره سریال را از گواهی به صورت رشتهٔ هگزادسیمال برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | اطلاعات را از فایل گواهی مشخص وارد می‌کند. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | اطلاعات را از فایل گواهی مشخص وارد می‌کند. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | اطلاعات را از دادهٔ گواهی مشخص وارد می‌کند. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | اطلاعات را از دادهٔ گواهی مشخص وارد می‌کند. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | اطلاعات را از فایل گواهی مشخص وارد می‌کند. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | اطلاعات را از دادهٔ گواهی مشخص وارد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [Reset](./reset/)() override | وضعیت گواهی را بازنشانی می‌کند. |
| void [set_Archived](./set_archived/)(**bool**) const | مقداری را تنظیم می‌کند که نشان می‌دهد گواهی بایگانی شده است. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | نام دوستانهٔ گواهی را تنظیم می‌کند. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | کلید خصوصی مرتبط با گواهی را تنظیم یا پاک می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب n ام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | اطلاعات گواهی را در قالب متن بازمی‌گرداند. |
| [String](../../system/string/) [ToString](./tostring/)() const override | اطلاعات گواهی را در قالب متن بازمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| **bool** [Verify](./verify/)() const | زنجیره گواهی را بررسی می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate2](./x509certificate2/)() | یک [X509Certificate2](./) خالی می‌سازد. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | سازنده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [X509Certificate](../x509certificate/)
* فضای نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)