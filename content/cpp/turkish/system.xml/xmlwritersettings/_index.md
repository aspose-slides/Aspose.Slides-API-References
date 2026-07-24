---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API Referansı
description: "XmlWriter::Create yöntemi tarafından oluşturulan XmlWriter nesnesi üzerinde desteklenecek bir dizi özelliği belirtir."
type: docs
weight: 586
url: /tr/system.xml/xmlwritersettings/
---
## XmlWriterSettings sınıf

[XmlWriter](../xmlwriter/) nesnesi üzerinde [XmlWriter::Create](../xmlwriter/create/) yöntemi tarafından oluşturulan özelliklerin bir kümesini belirtir.

```cpp
class XmlWriterSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Bir [XmlWriterSettings](./) örneğinin bir kopyasını oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | [Object.Equals](../../system/object/equals/) semantiğini kullanan nesneleri C# dilinde karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | XML yazarının belgedeki tüm karakterlerin W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) "2.2 Characters" bölümüne uygun olup olmadığını kontrol etmesi gerekip gerekmediğini gösteren bir değer döndürür. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında [XmlWriter](../xmlwriter/)'ın temel akışı veya TextWriter'ı da kapatıp kapatmayacağını gösteren bir değer döndürür. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | XML yazarının XML çıktısını kontrol ettiği uygunluk seviyesini döndürür. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | [XmlWriter](../xmlwriter/)'in URI özniteliklerini kaçırmaması gerektiğini gösteren bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Kullanılacak metin kodlaması türünü döndürür. |
| **bool** [get_Indent](./get_indent/)() | Elemanları girintileme gerekip gerekmediğini gösteren bir değer döndürür. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Girintileme sırasında kullanılacak karakter dizisini döndürür. Bu ayar [XmlWriterSettings::set_Indent](./set_indent/) değeri **true** olduğunda kullanılır. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | [XmlWriter](../xmlwriter/)'in XML içeriği yazarken yinelenen ad alanı bildirimlerini kaldırıp kaldırmayacağını gösteren bir değer döndürür. Varsayılan davranış, yazarın ad alanı çözücüsünde mevcut olan tüm ad alanı bildirimlerini çıkarmaktır. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Satır sonları için kullanılacak karakter dizisini döndürür. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Çıktıda satır sonlarını normalleştirip normalleştirmeyeceğini gösteren bir değer döndürür. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Öznitelikleri yeni bir satırda yazıp yazmayacağını gösteren bir değer döndürür. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Bir XML deklarasyonunu atlayıp atlamayacağını gösteren bir değer döndürür. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | [XmlWriter](../xmlwriter/) çıktısını serileştirmek için kullanılan yöntemi döndürür. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında [XmlWriter](../xmlwriter/)'in tüm açık olmayan element etiketlerine kapanış etiketleri ekleyip eklemeyeceğini gösteren bir değer döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [Reset](./reset/)() | Ayarlar sınıfının üyelerini varsayılan değerlerine sıfırlar. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | XML yazarının belgedeki tüm karakterlerin W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) "2.2 Characters" bölümüne uygun olup olmadığını kontrol etmesi gerektiğini belirten bir değeri ayarlar. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında [XmlWriter](../xmlwriter/)'ın temel akışı veya TextWriter'ı da kapatıp kapatmayacağını gösteren bir değeri ayarlar. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | XML yazarının XML çıktısını kontrol ettiği uygunluk seviyesini ayarlar. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | [XmlWriter](../xmlwriter/)'in URI özniteliklerini kaçırmaması gerektiğini gösteren bir değeri ayarlar. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Kullanılacak metin kodlaması türünü ayarlar. |
| void [set_Indent](./set_indent/)(**bool**) | Elemanları girintileme gerekip gerekmediğini gösteren bir değeri ayarlar. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Girintileme sırasında kullanılacak karakter dizisini ayarlar. Bu ayar [XmlWriterSettings::set_Indent](./set_indent/) değeri **true** olduğunda kullanılır. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | [XmlWriter](../xmlwriter/)'in XML içeriği yazarken yinelenen ad alanı bildirimlerini kaldırıp kaldırmayacağını gösteren bir değeri ayarlar. Varsayılan davranış, yazarın ad alanı çözücüsünde mevcut olan tüm ad alanı bildirimlerini çıkarmaktır. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Satır sonları için kullanılacak karakter dizisini ayarlar. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Çıktıda satır sonlarını normalleştirip normalleştirmeyeceğini gösteren bir değeri ayarlar. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Öznitelikleri yeni bir satırda yazıp yazmayacağını gösteren bir değeri ayarlar. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | XML deklarasyonunu atlayıp atlamayacağını gösteren bir değeri ayarlar. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | [XmlWriter::Close](../xmlwriter/close/) yöntemi çağrıldığında [XmlWriter](../xmlwriter/)'in tüm açık olmayan element etiketlerine kapanış etiketleri ekleyip eklemeyeceğini gösteren bir değeri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XmlWriterSettings](./xmlwritersettings/)() | [XmlWriterSettings](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Typedef'ler

| Tip tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak gösterici için bir takma isimdir. |

## Notlar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Yığın (stack) üzerinde ya da new operatörüyle örnek yaratmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman bir [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. 

## İlgili

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)