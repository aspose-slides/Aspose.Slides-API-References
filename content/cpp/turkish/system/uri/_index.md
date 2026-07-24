---
title: Uri
second_title: Aspose.Slides for C++ API Referansı
description: "Birleşik kaynak tanımlayıcı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1392
url: /tr/system/uri/
---
## Uri sınıfı


Birleşik kaynak tanımlayıcısı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class Uri : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Belirtilen ana bilgisayar adının türünü belirler. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Belirtilen şemanın geçerli olup olmadığını belirler. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Belirtilen [Uri](./) nesnelerini belirtilen karşılaştırma kurallarını kullanarak karşılaştırır. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Geçerli ve belirtilen nesneler tarafından temsil edilen URI'lerin eşit olup olmadığını belirler. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Nesneleri C# [Object.Equals](../object/equals/) anlamı ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Bir dizgeyi kaçışlı temsiline dönüştürür. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Bir URI dizgesini kaçışlı temsiline dönüştürür. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Bir onaltılık basamağın ondalık değerini alır. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | URI'nin mutlak yolunu döndürür. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Mutlak URI'yi döndürür. |
| [String](../string/) [get_Authority](./get_authority/)() const | Bir sunucu için ana bilgisayar adını ve bağlantı noktasını döndürür. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Kaçışsız ana bilgisayar adını döndürür. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Kaçışlı URI kesimini döndürür. |
| [String](../string/) [get_Host](./get_host/)() const | Ana bilgisayar adını döndürür. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Ana bilgisayar adı türünü döndürür. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Ana bilgisayarın Uluslararası Alan Adını döndürür. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Geçerli nesne tarafından temsil edilen URI'nin mutlak olup olmadığını belirler. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Geçerli nesne tarafından temsil edilen URI'nin şeması için varsayılan bağlantı noktasına sahip olup olmadığını belirler. |
| **bool** [get_IsFile](./get_isfile/)() const | Geçerli nesne tarafından temsil edilen URI'nin bir dosya olup olmadığını belirler. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Geçerli nesne tarafından temsil edilen URI'nin yerel bir ana bilgisayara işaret edip etmediğini belirler. |
| **bool** [get_IsUnc](./get_isunc/)() const | Geçerli nesne tarafından temsil edilen URI'nin bir UNC yolu olup olmadığını belirler. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Geçerli nesne tarafından temsil edilen URI tarafından referans verilen dosya adının işletim sistemi temsiliğini döndürür. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Geçerli nesne oluşturulduğunda yapıcıya geçirilen URI dizgesini döndürür. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Geçerli nesne tarafından temsil edilen URI'nin mutlak yol ve sorgu bileşenlerini soru işareti (?) ile ayırarak döndürür. |
| **int32_t** [get_Port](./get_port/)() const | Geçerli nesne tarafından temsil edilen URI'nin bağlantı noktasını döndürür. |
| [String](../string/) [get_Query](./get_query/)() const | Geçerli nesne tarafından temsil edilen URI'de bulunan sorgu bilgisini döndürür. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Geçerli nesne tarafından temsil edilen URI'nin şemasını döndürür. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Geçerli nesne tarafından temsil edilen URI'nin yol bölümlerini içeren bir dizi dizge döndürür. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Geçerli nesnenin yapıcısına geçirilen URI dizgesinin tamamen kaçışlı olup olmadığını belirler. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Geçerli nesne tarafından temsil edilen URI ile ilişkili bir kullanıcı adı, parola ve diğer kullanıcı bilgilerini döndürür. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Belirtilen kaçış kullanılarak, geçerli nesne tarafından temsil edilen URI'nin belirtilen bileşenlerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | URI için hash kodunu alır. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Geçerli nesne tarafından temsil edilen URI'nin belirtilen bölümünü döndürür. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının analoğu. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Belirtilen karakterin onaltılık karşılığını döndürür. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Bir karakterin belirtilen onaltılık temsiliğini karaktere dönüştürür. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Geçerli [Uri](./) nesnesi tarafından temsil edilen URI'nin belirtilen [Uri](./) nesnesi tarafından temsil edilen URI'nin temeli olup olmadığını belirler. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Belirtilen karakterin geçerli bir onaltılık basamak olup olmadığını belirler. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Belirtilen dizgede belirtilen konumdaki karakterin onaltılık kodlu olup olmadığını belirler. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Bu [Uri](./)'yi oluşturmak için kullanılan dizgenin düzgün biçimlenmiş olup daha fazla kaçışa gerek duyulmadığını gösterir. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Belirtilen dizgenin düzgün biçimlenmiş bir URI olup olmadığını belirler. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Direkt çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | İki [Uri](./) örneği arasındaki farkı belirler. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Geçerli ve belirtilen [Uri](./) nesneleri tarafından temsil edilen URI'ler arasındaki farkı belirler. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'in dize ve nullptr durumuna özel bir örneği. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'in dize durumuna özel bir örneği. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| [String](../string/) [ToString](./tostring/)() const override | Geçerli nesne tarafından temsil edilen URI'nin dizge temsiliğini döndürür. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Belirtilen URI'yi temsil eden bir [Uri](./) nesnesi oluşturur; bir argüman URI türünü belirtir. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Belirtilen [Uri](./) nesnesinden temel URI'yi temsil eden bir [Uri](./) nesnesi ve göreli URI'nun dizge temsili ile oluşturur. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Belirtilen temel ve göreli URI'lerden bir [Uri](./) nesnesi oluşturur. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Belirtilen kaçışlı dizgeyi kaçışsız hale getirir. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilidini açar. Direkt çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
|  [Uri](./uri/)(const [String](../string/)\&) | Belirtilen URI'yi temsil eden bir [Uri](./) nesnesi oluşturur. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Belirtilen URI'yi temsil eden bir [Uri](./) nesnesi oluşturur; bir argüman URI'nin kaçışlı olup olmayacağını belirtir. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Belirtilen [Uri](./) nesnesinden temel URI'yi temsil eden bir [Uri](./) nesnesi ve göreli URI'nun dizge temsiliyle oluşturur; bir argüman URI'nin kaçışlı olup olmayacağını belirtir. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Belirtilen URI'yi temsil eden bir [Uri](./) nesnesi oluşturur; bir argüman URI türünü belirtir. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Belirtilen temel ve göreli URI'lerden bir [Uri](./) nesnesi oluşturur. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Belirtilen temel ve göreli URI'lerden bir [Uri](./) nesnesi oluşturur. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | İletişim protokolü şemasını [Uri](./)'nin adres bölümünden ayıran karakterleri belirtir. |
| static [UriSchemeFile](./urischemefile/) | [Uri](./)'nin bir dosya işaretçisi olduğunu belirtir. |
| static [UriSchemeFtp](./urischemeftp/) | [Uri](./)'nin Dosya Transfer Protokolü üzerinden erişildiğini belirtir. |
| static [UriSchemeGopher](./urischemegopher/) | [Uri](./)'nin Gopher protokolü üzerinden erişildiğini belirtir. |
| static [UriSchemeHttp](./urischemehttp/) | [Uri](./)'nin Hypertext Transfer Protocol üzerinden erişildiğini belirtir. |
| static [UriSchemeHttps](./urischemehttps/) | [Uri](./)'nin Secure Hypertext Transfer Protocol üzerinden erişildiğini belirtir. |
| static [UriSchemeMailto](./urischememailto/) | [Uri](./)'nin bir e-posta adresi olduğunu ve Simple Mail Transport Protocol üzerinden erişildiğini belirtir. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | [Uri](./)'nin [Windows](../../system.windows/) Communication Foundation tarafından kullanılan NetPipe şeması üzerinden erişildiğini belirtir. |
| static [UriSchemeNetTcp](./urischemenettcp/) | [Uri](./)'nin [Windows](../../system.windows/) Communication Foundation tarafından kullanılan NetTcp şeması üzerinden erişildiğini belirtir. |
| static [UriSchemeNews](./urischemenews/) | [Uri](./)'nin bir Internet haber grubu olduğunu ve Network News Transport Protocol üzerinden erişildiğini belirtir. |
| static [UriSchemeNntp](./urischemenntp/) | [Uri](./)'nin bir Internet haber grubu olduğunu ve Network News Transport Protocol üzerinden erişildiğini belirtir. |

## Açıklamalar



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Ayrıca Bakınız

* Sınıf [Object](../object/)
* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)