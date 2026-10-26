---
title: XmlTextWriter
second_title: Aspose.Slides for C++ API Referansı
description: W3C Extensible Markup Language (XML) 1.0 ve Namespaces in XML önerilerine uygun XML verisi içeren akışlar veya dosyalar üretmek için hızlı, önbelleğe alınmayan, yalnızca ileri yönde çalışan bir yazarı temsil eder.
type: docs
weight: 521
url: /tr/system.xml/xmltextwriter/
---
## XmlTextWriter sınıfı

W3C Extensible Markup Language (XML) 1.0 ve Namespaces in XML önerilerine uygun XML verilerini üreten, hızlı, önbellek kullanılmayan, yalnızca ileri yönde çalışan bir yazar temsil eder.

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Close](./close/)() override | Bu akışı ve alt akışı kapatır. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | Belirtilen dosya adını kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Dosya adını ve [XmlWriterSettings](../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akışı kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Akışı ve [XmlWriterSettings](../xmlwritersettings/) nesnesini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Belirtilen TextWriter'ı kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | TextWriter ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Belirtilen [Text::StringBuilder](../../system.text/stringbuilder/)'ı kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | [Text::StringBuilder](../../system.text/stringbuilder/) ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Belirtilen [XmlWriter](../xmlwriter/) nesnesini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | Belirtilen [XmlWriter](../xmlwriter/) ve [XmlWriterSettings](../xmlwritersettings/) nesnelerini kullanarak yeni bir [XmlWriter](../xmlwriter/) örneği oluşturur. |
| void [Dispose](../xmlwriter/dispose/)() override | [XmlWriter](../xmlwriter/) sınıfının geçerli örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamı ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Arabellekteki tüm veriyi alt akışlara boşaltır ve ayrıca alt akışı da boşaltır. |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | Alt akış nesnesini döndürür. |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | Çıktının nasıl biçimlendirildiğini gösterir. |
| **int32_t** [get_Indentation](./get_indentation/)() | [XmlTextWriter::set_Formatting](./set_formatting/) [Formatting::Indented](../formatting/) olarak ayarlandığında hiyerarşideki her seviye için kaç IndentChars yazılacağını döndürür. |
| char16_t [get_IndentChar](./get_indentchar/)() | [XmlTextWriter::set_Formatting](./set_formatting/) [Formatting::Indented](../formatting/) olarak ayarlandığında girinti için hangi karakterin kullanılacağını döndürür. |
| **bool** [get_Namespaces](./get_namespaces/)() | Ad alanı desteği yapılması gerekip gerekmediğini gösteren bir değer döndürür. |
| char16_t [get_QuoteChar](./get_quotechar/)() | Özellik değerlerini tırnaklamak için kullanılacak karakteri döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | Bu [XmlWriter](../xmlwriter/) örneğini oluşturmak için kullanılan [XmlWriterSettings](../xmlwritersettings/) nesnesini döndürür. |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | Yazıcının durumunu döndürür. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Geçerli **xml:lang** kapsamını döndürür. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Geçerli **xml:space** kapsamını temsil eden bir XmlSpace döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | Ad alanı URI'si için geçerli ad alanı kapsamında tanımlı en yakın öneki döndürür. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) nin dize ve nullptr durumuna özel bir türevi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) nin dizeler durumuna özel bir türevi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | Çıktının nasıl biçimlendirildiğini gösterir. |
| void [set_Indentation](./set_indentation/)(**int32_t**) | [XmlTextWriter::set_Formatting](./set_formatting/) [Formatting::Indented](../formatting/) olarak ayarlandığında hiyerarşideki her seviye için kaç IndentChars yazılacağını ayarlar. |
| void [set_IndentChar](./set_indentchar/)(char16_t) | [XmlTextWriter::set_Formatting](./set_formatting/) [Formatting::Indented](../formatting/) olarak ayarlandığında girinti için kullanılacak karakteri ayarlar. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ad alanı desteği yapılması gerekip gerekmediğini gösteren bir değeri ayarlar. |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | Özellik değerlerini tırnaklamak için kullanılacak karakteri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını paylaşılan yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının şu anki değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Türetilmiş bir sınıfta geçersiz kılındığında, [XmlReader](../xmlreader/) içinde geçerli konumda bulunan tüm öznitelikleri yazar. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad, ad alanı URI'si ve değer ile bir öznitelik yazar. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirli yerel ad ve değer ile bir öznitelik yazar. |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen önek, yerel ad, ad alanı URI'si ve değer ile bir öznitelik yazar. |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Belirtilen ikili baytları base64 olarak kodlar ve ortaya çıkan metni yazar. |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Belirtilen ikili baytları binhex olarak kodlar ve ortaya çıkan metni yazar. |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | Belirtilen metni içeren bir **...** bloğu yazar. |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | Belirtilen Unicode karakter değeri için bir karakter varlığı oluşturulmasını zorlar. |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Metni bir tampon olarak yazar. |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | Belirtilen metni içeren bir **** yorum yazar. |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE deklarasyonunu yazar. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad ve değerle bir öğe yazar. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad, ad alanı URI'si ve değerle bir öğe yazar. |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen önek, yerel ad, ad alanı URI'si ve değerle bir öğe yazar. |
| void [WriteEndAttribute](./writeendattribute/)() override | Önceki [XmlTextWriter::WriteStartAttribute](./writestartattribute/) çağrısını kapatır. |
| void [WriteEndDocument](./writeenddocument/)() override | Açık olan tüm öğeleri veya öznitelikleri kapatır ve yazıcıyı Başlangıç durumuna getirir. |
| void [WriteEndElement](./writeendelement/)() override | Bir öğeyi kapatır ve ilgili ad alanı kapsamını çıkarır. |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | Bir varlık referansını **&name**; şeklinde yazar. |
| void [WriteFullEndElement](./writefullendelement/)() override | Bir öğeyi kapatır ve ilgili ad alanı kapsamını çıkarır. |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | Belirtilen adı, [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)'a göre geçerli bir ad olduğunu doğrulayarak yazar. |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | Belirtilen adı, [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name)'a göre geçerli bir **NmToken** olduğunu doğrulayarak yazar. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | Türetilmiş bir sınıfta geçersiz kılındığında, okuyucudan yazıcıya her şeyi kopyalar ve okuyucuyu bir sonraki kardeşin başına taşır. |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | XPathNavigator nesnesinden yazıcıya her şeyi kopyalar. XPathNavigator konumu değişmez. |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | İsim ve metin arasında bir boşluk bırakarak aşağıdaki gibi bir işleme talimatı yazar: **<?name text?>**. |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Belirtilen ad alanı nitelikli adı yazar. Bu yöntem verilen ad alanı için kapsamda olan öneki bulur. |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | Bir karakter tamponundan ham işaretlemeyi elle yazar. |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | Bir dizeden ham işaretlemeyi elle yazar. |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Bir öznitelik başlangıcını yazar. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen yerel ad ve ad alanı URI'si ile bir öznitelik başlangıcını yazar. |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | Belirtilen yerel ad ile bir öznitelik başlangıcını yazar. |
| void [WriteStartDocument](./writestartdocument/)() override | Versiyon "1.0" ile XML deklarasyonunu yazar. |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | Versiyon "1.0" ve standalone özniteliği ile XML deklarasyonunu yazar. |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | Belirtilen başlangıç etiketini yazar ve verilen ad alanı ve önek ile ilişkilendirir. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen başlangıç etiketini yazar ve verilen ad alanı ile ilişkilendirir. |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen yerel ad ile bir başlangıç etiketi yazar. |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | Verilen metin içeriğini yazar. |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | Surrogaat karakter çifti için surrogaat karakter varlığını oluşturur ve yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Nesne değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | [String](../../system/string/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | [Boolean](../../system/boolean/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | [DateTime](../../system/datetime/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | [DateTimeOffset](../../system/datetimeoffset/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | [Double](../../system/double/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | Tek duyarlıklı kayan nokta sayısını yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | [Decimal](../../system/decimal/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | [Int32](../../system/int32/) değerini yazar. |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | [Int64](../../system/int64/) değerini yazar. |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override | Verilen beyaz boşluğu yazar. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Belirtilen akış ve kodlamayı kullanarak [XmlTextWriter](./) sınıfının bir örneğini oluşturur. |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Belirtilen dosyayı kullanarak [XmlTextWriter](./) sınıfının bir örneğini oluşturur. |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Belirtilen TextWriter'ı kullanarak [XmlTextWriter](./) sınıfının bir örneğini oluşturur. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak işaretçi için bir takma isim. |
## Açıklamalar

Bunun yerine [XmlWriter](../xmlwriter/) sınıfının kullanılması önerilir.

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneklerini yığıt üzerinde ya da new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman bir [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

## Ayrıca Bakınız

* Sınıf [XmlWriter](../xmlwriter/)
* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)