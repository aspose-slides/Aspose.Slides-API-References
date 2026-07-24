---
title: XmlWriter
second_title: Aspose.Slides for C++ API Referansı
description: XML verileri içeren akışları veya dosyaları hızlı, önbelleğe alınmamış, yalnızca ileri yönlü bir şekilde oluşturmayı sağlayan bir yazar temsil eder.
type: docs
weight: 573
url: /tr/system.xml/xmlwriter/
---
## XmlWriter sınıfı

XML verileri içeren akışları veya dosyaları oluşturmak için hızlı, önbelleğe alınmamış, yalnızca ileri yönlü bir yol sağlayan bir yazar temsil eder.

```cpp
class XmlWriter : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Close](./close/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu akışı ve temel akışı kapatır. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Belirtilen dosya adını kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Dosya adını ve [XmlWriterSettings](../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akışı kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Akışı ve [XmlWriterSettings](../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Belirtilen TextWriter'ı kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Belirtilen [Text::StringBuilder](../../system.text/stringbuilder/)'i kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | Belirtilen [XmlWriter](./) nesnesini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Belirtilen [XmlWriter](./) ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](./) örneği oluşturur. |
| void [Dispose](./dispose/)() override | Mevcut [XmlWriter](./) sınıfının örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesnelerini C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere (NaN dahil) eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere (NaN dahil) eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [Flush](./flush/)() | Türetilmiş bir sınıfta geçersiz kılındığında, tampondaki tüm veriyi temel akışlara gönderir ve ayrıca temel akışı da temizler. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | Bu [XmlWriter](./) örneğini oluşturmak için kullanılan [XmlWriterSettings](../xmlwritersettings/) nesnesini döndürür. |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | Türetilmiş bir sınıfta geçersiz kılındığında, yazarın durumunu alır. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut **xml:lang** kapsamını alır. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut **xml:space** kapsamını temsil eden bir XmlSpace alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, namespace URI için mevcut namespace kapsamında tanımlı en yakın öneki döndürür. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını ilklendirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi ilklendirir ve alt sınıfların kopya yapılandırılmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özgü özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özgü özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Türetilmiş bir sınıfta geçersiz kılındığında, [XmlReader](../xmlreader/) içindeki mevcut konumda bulunan tüm öznitelikleri yazar. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad, namespace URI ve değere sahip bir öznitelik yazar. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad ve değere sahip özniteliği yazar. |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen önek, yerel ad, namespace URI ve değere sahip özniteliği yazar. |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen ikili baytları Base64 olarak kodlar ve ortaya çıkan metni yazar. |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen ikili baytları **BinHex** olarak kodlar ve ortaya çıkan metni yazar. |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen metni içeren bir **...** bloğu yazar. |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen Unicode karakter değeri için bir karakter varlığı oluşturulmasını zorlar. |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Türetilmiş bir sınıfta geçersiz kılındığında, metni bir seferde bir tampon olarak yazar. |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen metni içeren bir **** yorum yazar. |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad ve değere sahip bir öğe yazar. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad, namespace URI ve değere sahip bir öğe yazar. |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen önek, yerel ad, namespace URI ve değere sahip bir öğe yazar. |
| virtual void [WriteEndAttribute](./writeendattribute/)() | Türetilmiş bir sınıfta geçersiz kılındığında, önceki XmlWriter::WriteStartAttribute(String,String) çağrısını kapatır. |
| virtual void [WriteEndDocument](./writeenddocument/)() | Türetilmiş bir sınıfta geçersiz kılındığında, açık tüm öğeleri veya öznitelikleri kapatır ve yazarı Başlangıç durumuna geri getirir. |
| virtual void [WriteEndElement](./writeendelement/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bir öğeyi kapatır ve ilişkili namespace kapsamını çıkarır. |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, bir varlık referansını **&name**; olarak yazar. |
| virtual void [WriteFullEndElement](./writefullendelement/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bir öğeyi kapatır ve ilişkili namespace kapsamını çıkarır. |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen adı yazar ve W3C XML 1.0 önerisine ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) göre geçerli bir ad olduğundan emin olur. |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen adı yazar ve W3C XML 1.0 önerisine ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)) göre geçerli bir NmToken olduğundan emin olur. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Türetilmiş bir sınıfta geçersiz kılındığında, okuyucudan yazıcıya her şeyi kopyalar ve okuyucuyu bir sonraki kardeşin başlangıcına taşır. |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator nesnesinden yazıcıya her şeyi kopyalar. XPathNavigator konumu değişmeden kalır. |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, isim ve metin arasında boşluk bulunan bir işleme talimatı yazar: **<?name text?>**. |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, namespace nitelikli adı yazar. Bu metod, verilen namespace için kapsamda olan önek'i bulur. |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Türetilmiş bir sınıfta geçersiz kılındığında, karakter tamponundan ham markup'u manuel olarak yazar. |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, bir dizeden ham markup'u manuel olarak yazar. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad ve namespace URI ile bir öznitelik başlangıcı yazar. |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen önek, yerel ad ve namespace URI ile bir öznitelik başlangıcı yazar. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | Belirtilen yerel ad ile bir öznitelik başlangıcı yazar. |
| virtual void [WriteStartDocument](./writestartdocument/)() | Türetilmiş bir sınıfta geçersiz kılındığında, "1.0" sürümüyle XML deklarasyonu yazar. |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | Türetilmiş bir sınıfta geçersiz kılındığında, "1.0" sürümü ve standalone özniteliğiyle XML deklarasyonu yazar. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen namespace ile ilişkilendirir. |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen namespace ve önek ile ilişkilendirir. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad ile bir başlangıç etiketi yazar. |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, verilen metin içeriğini yazar. |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | Türetilmiş bir sınıfta geçersiz kılındığında, surrogate karakter çiftinin surrogate karakter varlığını üretir ve yazar. |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Nesne değerini yazar. |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | Bir [String](../../system/string/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)(**bool**) | Bir [Boolean](../../system/boolean/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | Bir [DateTime](../../system/datetime/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | Bir [DateTimeOffset](../../system/datetimeoffset/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)(**double**) | Bir [Double](../../system/double/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)(**float**) | Tek duyarlıklı bir kayan nokta sayısı yazar. |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | Bir [Decimal](../../system/decimal/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | Bir [Int32](../../system/int32/) değeri yazar. |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | Bir [Int64](../../system/int64/) değeri yazar. |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, verilen boşluk karakterini yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı işaretçi için bir takma addır. |

## Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)