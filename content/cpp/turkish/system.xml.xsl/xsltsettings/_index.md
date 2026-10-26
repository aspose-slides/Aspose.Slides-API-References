---
title: XsltSettings
second_title: Aspose.Slides for C++ API Referansı
description: XSLT stil sayfasının çalıştırılması sırasında desteklenecek XSLT özelliklerini belirtir.
type: docs
weight: 118
url: /tr/system.xml.xsl/xsltsettings/
---
## XsltSettings sınıfı


XSLT stil sayfasının çalıştırılması sırasında desteklenecek XSLT özelliklerini belirtir.

```cpp
class XsltSettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırması yapar. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C#-tarzı kayan nokta karşılaştırması yapar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [SharedPtr](../../system/sharedptr/)\<[XsltSettings](./)\> [get_Default](./get_default/)() | Varsayılan ayarlarla bir [XsltSettings](./) nesnesi döndürür. XSLT **document()** işlevi ve gömülü betik blokları desteği devre dışıdır. |
| **bool** [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | XSLT **document()** işlevi desteğinin etkinleştirilip etkinleştirilmeyeceğini belirten bir değer döndürür. |
| **bool** [get_EnableScript](./get_enablescript/)() | Gömülü betik blokları desteğinin etkinleştirilip etkinleştirilmeyeceğini belirten bir değer döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[XsltSettings](./)\> [get_TrustedXslt](./get_trustedxslt/)() | XSLT **document()** işlevi ve gömülü betik blokları desteğini etkinleştiren bir [XsltSettings](./) nesnesi döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin karşılığı. Özel nesnelerin karma (hash) değerini oluşturmayı etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının karşılığı. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTür tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün karşılığı. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) denetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin karşılığı. Özel türlerin klonlanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Dize ve nullptr durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) özel uygulaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Dizi durumunda [Object::ReferenceEquals](../../system/object/referenceequals/) özel uygulaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_EnableDocumentFunction](./set_enabledocumentfunction/)(**bool**) | XSLT **document()** işlevi desteğinin etkinleştirilip etkinleştirilmeyeceğini belirten bir değer ayarlar. |
| void [set_EnableScript](./set_enablescript/)(**bool**) | Gömülü betik blokları desteğinin etkinleştirilip etkinleştirilmeyeceğini belirten bir değer ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n. şablon bağımsız değişkenini zayıf bir işaretçi olarak ayarlar (paylaşılan yerine). İşaretçileri konteynerlerde zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mevcut paylaşılan referans sayacı değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin karşılığı. Özel nesnelerin dizeye dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesinin uygulanmasıdır. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) denetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XsltSettings](./xsltsettings/)() | [XsltSettings](./) sınıfının yeni bir örneğini varsayılan ayarlarla başlatır. |
|  [XsltSettings](./xsltsettings/)(**bool**, **bool**) | [XsltSettings](./) sınıfının yeni bir örneğini belirtilen ayarlarla başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak işaretçi için bir takma addır. |

## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tür örnekler yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Her zaman bu sınıfı bir [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçin. 

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Xml::Xsl](../)
* Library [Aspose.Slides](../../)