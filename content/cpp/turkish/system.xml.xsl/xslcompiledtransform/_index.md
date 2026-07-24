---
title: XslCompiledTransform
second_title: Aspose.Slides C++ için API Referansı
description: XML verilerini bir XSLT stil sayfası kullanarak dönüştürür.
type: docs
weight: 53
url: /tr/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform sınıfı

Bir XSLT stil sayfası kullanarak XML verilerini dönüştürür.

```cpp
class XslCompiledTransform : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir ancak iki NaN eşit kabul edilir; C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir ancak iki NaN eşit kabul edilir; C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../../system.xml/xmlwritersettings/)\> [get_OutputSettings](./get_outputsettings/)() | [XmlWriterSettings](../../system.xml/xmlwritersettings/) nesnesi döndürür; bu nesne stil sayfasının **xsl:output** öğesinden türetilen çıktı bilgisini içerir. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeridir. Özelleştirilmiş nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeridir. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeridir. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | [XmlReader](../../system.xml/xmlreader/) içinde bulunan stil sayfasını derler. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlReader](../../system.xml/xmlreader/) içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../system.xml/xmlresolver/) tüm XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler. |
| void [Load](./load/)(const [String](../../system/string/)\&) | Belirtilen URI'de bulunan stil sayfasını yükler ve derler. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | URI tarafından belirtilen XSLT stil sayfasını yükler ve derler. [XmlResolver](../../system.xml/xmlresolver/) tüm XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | IXPathNavigable nesnesinde bulunan stil sayfasını derler. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XsltSettings](../xsltsettings/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>) | IXPathNavigable içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../system.xml/xmlresolver/) tüm XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeridir. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarının başlatılmasını yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel bir türevidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel bir türevidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeridir. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | IXPathNavigable nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | IXPathNavigable nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | IXPathNavigable nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | IXPathNavigable nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa (stream) çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa (stream) çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | URI ile belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | URI ile belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | URI ile belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir TextWriter'a çıkarır. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | URI ile belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir akışa (stream) çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | URI ile belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir dosyaya çıkarır. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlReader](../../system.xml/xmlreader/) nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../system.xml/xmlresolver/) XSLT **document()** fonksiyonunu çözer. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | IXPathNavigable nesnesiyle belirtilen giriş belgesini kullanarak dönüşümü yürütür ve sonuçları bir [XmlWriter](../../system.xml/xmlwriter/)'ye çıkarır. [XsltArgumentList](../xsltargumentlist/) ek çalışma zamanı argümanları sağlar ve [XmlResolver](../../system.xml/xmlresolver/) XSLT **document()** fonksiyonunu çözer. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XslCompiledTransform](./xslcompiledtransform/)() | [XslCompiledTransform](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak işaretçi için bir takma addır. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini hiçbir zaman yığında (stack) veya new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assert hataları ortaya çıkar. Her zaman bu sınıfı bir [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. 

## İlgili

* Sınıf [Object](../../system/object/)
* AdAlanı [System::Xml::Xsl](../)
* Kütüphane [Aspose.Slides](../../)