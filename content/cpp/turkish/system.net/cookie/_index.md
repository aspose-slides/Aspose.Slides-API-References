---
title: Cookie
second_title: Aspose.Slides for C++ API Referansı
description: "Bir HTTP çerezi temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığına (stack) ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1
url: /tr/system.net/cookie/
---
## Cookie sınıfı

Bir HTTP çerezi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığına (stack) ya da operator new kullanarak oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Cookie : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Mevcut örneğin bir kopyasını oluşturur. |
| [Cookie](./cookie/)() | Yeni bir örnek oluşturur. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Yeni bir örnek oluşturur. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Yeni bir örnek oluşturur. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Yeni bir örnek oluşturur. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere (NaN dahil) eşit olmamasına rağmen, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere (NaN dahil) eşit olmamasına rağmen, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | 'Comment' özniteliğinin değerini alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | 'CommentURL' özniteliğinin değerini alır. |
| **bool** [get_Discard](./get_discard/)() const | 'Discard' özniteliğinin değerini alır. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | 'Domain' özniteliğinin değerini alır. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Alan adının örtük olup olmadığını gösteren bir değer alır. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Alan adı anahtarını döndürür. |
| **bool** [get_Expired](./get_expired/)() | Çerezin süresinin dolup dolmadığını gösteren bir değer alır. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | 'Expires' özniteliğinin değerini alır. |
| **bool** [get_HttpOnly](./get_httponly/)() const | 'HttpOnly' özniteliğinin değerini alır. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Çerezin adını alır. |
| [String](../../system/string/) [get_Path](./get_path/)() const | 'Path' özniteliğinin değerini alır. |
| **bool** [get_Plain](./get_plain/)() const | Çerez tanımının 'Plain' olup olmadığını gösteren bir değer döndürür. |
| [String](../../system/string/) [get_Port](./get_port/)() const | 'Port' özniteliğinin değerini alır. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | 'Port' özniteliğinin değerlerinin koleksiyonunu döndürür. |
| **bool** [get_Secure](./get_secure/)() const | 'Secure' özniteliğinin değerini alır. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Çerezin oluşturulduğu zamanı döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Çerezin değerini alır. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Çerezin tanımını alır. |
| **int32_t** [get_Version](./get_version/)() const | '[Version](../../system/version/)' özniteliğinin değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Bu yöntem diğer yöntemler tarafından bir yöntem adını ayarlamak için çağrılır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | 'Comment' özniteliğinin değerini ayarlar. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | 'CommentURL' özniteliğinin değerini ayarlar. |
| void [set_Discard](./set_discard/)(**bool**) | 'Discard' özniteliğinin değerini ayarlar. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | 'Domain' özniteliğinin değerini ayarlar. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Alan adının örtük olup olmadığını gösteren bir değeri ayarlar. |
| void [set_Expired](./set_expired/)(**bool**) | Çerezin süresinin dolup dolmadığını gösteren bir değeri ayarlar. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | 'Expires' özniteliğinin değerini ayarlar. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | 'HttpOnly' özniteliğinin değerini ayarlar. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Çerezin adını ayarlar. |
| void [set_Path](./set_path/)([String](../../system/string/)) | 'Path' özniteliğinin değerini ayarlar. |
| void [set_Port](./set_port/)([String](../../system/string/)) | 'Port' özniteliğinin değerini ayarlar. |
| void [set_Secure](./set_secure/)(**bool**) | 'Secure' özniteliğinin değerini ayarlar. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Çerezin değerini ayarlar. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Çerezin tanımını ayarlar. |
| void [set_Version](./set_version/)(**int32_t**) | '[Version](../../system/version/)' özniteliğinin değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Mevcut örneği dize temsiline serileştirir. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Varsayılan öznitelik değerlerini doğrular ve ayarlar. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | 'Comment' özniteliğinin adı. |
| static [CommentUrlAttributeName](./commenturlattributename/) | 'CommentURL' özniteliğinin adı. |
| static [DiscardAttributeName](./discardattributename/) | 'Discard' özniteliğinin adı. |
| static [DomainAttributeName](./domainattributename/) | 'Domain' özniteliğinin adı. |
| static [EqualsLiteral](./equalsliteral/) | Bir özniteliğin adını ve değerini ayırmak için kullanılan ayırıcı. |
| static [ExpiresAttributeName](./expiresattributename/) | 'Expires' özniteliğinin adı. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | 'HttpOnly' özniteliğinin adı. |
| static [MaxAgeAttributeName](./maxageattributename/) | 'Max-Age' özniteliğinin adı. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Desteklenen en yüksek sürüm. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Desteklenen en yüksek sürümün dize temsili. |
| static [PathAttributeName](./pathattributename/) | 'Path' özniteliğinin adı. |
| static [PortAttributeName](./portattributename/) | 'Port' özniteliğinin adı. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | 'Port' özniteliğinin değerleri için ayırıcıları içeren dizi. |
| static [QuotesLiteral](./quotesliteral/) | Özniteliğin bölümlerini sarmak için kullanılan sembol. |
| static [ReservedToName](./reservedtoname/) | Çerez adı için ayrılmış bir değer. |
| static [ReservedToValue](./reservedtovalue/) | Çerez değeri için ayrılmış bir değer. |
| static [SecureAttributeName](./secureattributename/) | 'Secure' özniteliğinin adı. |
| static [SeparatorLiteral](./separatorliteral/) | Öznitelik ayırıcı. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Özel öznitelik adlarının öneki. |
| static [VersionAttributeName](./versionattributename/) | '[Version](../../system/version/)' özniteliğinin adı. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* İsim Uzayı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)