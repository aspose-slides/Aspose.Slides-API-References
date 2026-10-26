---
title: XmlDocument
second_title: Aspose.Slides for C++ API Referansı
description: Bir XML belgesini temsil eder. Bu sınıfı bir belgede XML'yi yüklemek, doğrulamak, düzenlemek, eklemek ve konumlandırmak için kullanabilirsiniz.
type: docs
weight: 183
url: /tr/system.xml/xmldocument/
---
## XmlDocument sınıfı

Bir XML belgesini temsil eder. Bu sınıfı bir belgede XML'i yüklemek, doğrulamak, düzenlemek, eklemek ve konumlandırmak için kullanabilirsiniz.

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü, bu düğümün alt düğüm listesine, listenin sonuna ekler. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Koleksiyonun (varsa) ilk öğesine işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin kopya nesnesini döndürdüğü için başvurulan nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinin (varsa) ilk öğesine işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Koleksiyonun (varsa) ilk const nitelikli öğesine işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Koleksiyonun (varsa) son const nitelikli öğesinden hemen sonra işaret eden yineleyiciyi alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Bu düğümün bir kopyasını oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Bu düğümün bir kopyasını oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&) | Belirtilen adla bir [XmlAttribute](../xmlattribute/) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen nitelikli ad ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../xmlattribute/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../xmlattribute/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlCDataSection](../xmlcdatasection/)\> [CreateCDataSection](./createcdatasection/)(const [String](../../system/string/)\&) | Belirtilen veriyi içeren bir [XmlCDataSection](../xmlcdatasection/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlComment](../xmlcomment/)\> [CreateComment](./createcomment/)(const [String](../../system/string/)\&) | Belirtilen veriyi içeren bir [XmlComment](../xmlcomment/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentFragment](../xmldocumentfragment/)\> [CreateDocumentFragment](./createdocumentfragment/)() | Bir [XmlDocumentFragment](../xmldocumentfragment/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [CreateDocumentType](./createdocumenttype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Yeni bir [XmlDocumentType](../xmldocumenttype/) nesnesi döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&) | Belirtilen adla bir öğe oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Nitelikli ad ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlElement](../xmlelement/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_LocalName](./get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir öğe oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlEntityReference](../xmlentityreference/)\> [CreateEntityReference](./createentityreference/)(const [String](../../system/string/)\&) | Belirtilen adla bir [XmlEntityReference](../xmlentityreference/) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | Bu belgeyi gezmek için yeni bir XPathNavigator nesnesi oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen XmlNodeType, [XmlNode::get_Prefix](../xmlnode/get_prefix/), [XmlDocument::get_Name](./get_name/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlNode](../xmlnode/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen düğüm türü, [XmlDocument::get_Name](./get_name/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlNode](../xmlnode/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen XmlNodeType, [XmlDocument::get_Name](./get_name/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile bir [XmlNode](../xmlnode/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlProcessingInstruction](../xmlprocessinginstruction/)\> [CreateProcessingInstruction](./createprocessinginstruction/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen ad ve veri ile bir [XmlProcessingInstruction](../xmlprocessinginstruction/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlSignificantWhitespace](../xmlsignificantwhitespace/)\> [CreateSignificantWhitespace](./createsignificantwhitespace/)(const [String](../../system/string/)\&) | Bir [XmlSignificantWhitespace](../xmlsignificantwhitespace/) düğümü oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](../xmltext/)\> [CreateTextNode](./createtextnode/)(const [String](../../system/string/)\&) | Belirtilen metinle bir [XmlText](../xmltext/) oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWhitespace](../xmlwhitespace/)\> [CreateWhitespace](./createwhitespace/)(const [String](../../system/string/)\&) | Bir [XmlWhitespace](../xmlwhitespace/) düğümü oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDeclaration](../xmldeclaration/)\> [CreateXmlDeclaration](./createxmldeclaration/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen değerlerle bir [XmlDeclaration](../xmldeclaration/) düğümü oluşturur. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Koleksiyonun (varsa) son öğesinden hemen sonra işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin kopya nesnesini döndürdüğü için başvurulan nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinin (varsa) son öğesinden hemen sonra işaret eden yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmayan bir durum olmasına rağmen, iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmayan bir durum olmasına rağmen, iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Bu düğümün özniteliklerini içeren bir [XmlAttributeCollection](../xmlattributecollection/) döndürür. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Geçerli düğümün temel URI'sını döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Düğümün tüm alt düğümlerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [get_DocumentElement](./get_documentelement/)() | Belge için kök [XmlElement](../xmlelement/) döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [get_DocumentType](./get_documenttype/)() | DOCTYPE bildirimi içeren düğümü döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Düğümün ilk çocuğunu döndürür. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Bu düğümün herhangi bir alt düğümü olup olmadığını gösteren bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlImplementation](../xmlimplementation/)\> [get_Implementation](./get_implementation/)() | Geçerli belge için [XmlImplementation](../xmlimplementation/) nesnesini döndürür. |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | Düğümün ve tüm alt düğümlerinin birleştirilmiş değerlerini döndürür. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Geçerli düğümün çocuklarını temsil eden işaretlemeyi döndürür. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | Geçerli düğümün yalnızca okunur olup olmadığını gösteren bir değer döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Düğümün son çocuğunu döndürür. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Düğümün yerel adını döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Bu düğümün ad alanı URI'sını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Bu uygulama ile ilişkili [XmlNameTable](../xmlnametable/)'u döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Bu düğümün hemen sonrasındaki düğümü döndürür. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Geçerli düğümün tipini döndürür. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Bu düğümü ve tüm alt düğümlerini içeren işaretlemeyi döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](./)\> [get_OwnerDocument](./get_ownerdocument/)() override | Geçerli düğümün ait olduğu [XmlDocument](./)'yi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Bu düğümün üst düğümünü döndürür (üst düğüm alabilen düğüler için). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Bu düğümün ad alanı önekini döndürür. |
| **bool** [get_PreserveWhitespace](./get_preservewhitespace/)() | Öğe içeriğinde boşlukların korunup korunmayacağını belirten bir değer döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Bu düğümden hemen önceki düğümü döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Bu düğümden hemen önceki metin düğümünü döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Düğümün Şema Sonrası Doğrulama Bilgi Kümesini (PSVI) döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Bu [XmlDocument](./) ile ilişkili XmlSchemaSet nesnesini döndürür. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Düğümün değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [GetElementById](./getelementbyid/)([String](../../system/string/)) | Belirtilen ID'ye sahip [XmlElement](../xmlelement/)'yi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | Belirtilen adla eşleşen tüm alt öğeleri içeren bir [XmlNodeList](../xmlnodelist/) döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen [XmlDocument::get_LocalName](./get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) ile eşleşen tüm alt öğeleri içeren bir [XmlNodeList](../xmlnodelist/) döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Geçerli düğümdeki alt düğümler üzerinde yineleme yapan bir enumeratör döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Geçerli düğüm için kapsam içinde olan verilen önek için en yakın **xmlns** bildirimini bulur ve bildirideki ad alanı URI'sını döndürür. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Geçerli düğüm için kapsam içinde olan verilen ad alanı URI'si için en yakın **xmlns** bildirimini bulur ve bu bildirimde tanımlı öneki döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Belirtilen [XmlNode::get_Name](../xmlnode/get_name/)'ye sahip ilk alt öğeyi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen [XmlNode::get_LocalName](../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) değerlerine sahip ilk alt öğeyi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ImportNode](./importnode/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, **bool**) | Başka bir belgeden bir düğümü geçerli belgeye içe aktarır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü belirtilen referans düğümünün hemen sonrasına ekler. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü belirtilen referans düğümünün hemen öncesine ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizideki herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisinin her öğesine bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Öğeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizi içindeki öğe sayısını döndürür (doğrudan sayma ile hesaplanır). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Bir dizideki belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Bir dizideki belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Dizinin ilk öğesini, dizi boş ise varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Koşulu sağlayan dizinin ilk elemanını, bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin elemanlarını gruplar. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin elemanlarını gruplar. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son elemanını döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son elemanını döndürür, dizin boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her eleman üzerinde bir dönüşüm işlevi çağırır ve elde edilen en büyük değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her eleman üzerinde bir dönüşüm işlevi çağırır ve elde edilen en küçük değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin elemanlarını belirtilen tipe göre süzer. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin elemanlarını artan sırada sıpar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector tarafından seçilen anahtar değerlerine göre bir dizinin elemanlarını azalan sırada sıpar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizinin elemanlarının sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bir dizinin elemanlarını dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her elemanını, elemanın indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her elemanını projeler ve elde edilen dizileri tek bir dizi içinde birleştirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık elemanı atlar ve geri kalanları döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirtilen sayıda ardışık elemanı döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden bir List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Belirtilen koşula göre bir diziyi süzer. |
| virtual void [Load](./load/)([String](../../system/string/)) | Belirtilen URL'den XML belgesini yükler. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Belirtilen akıştan XML belgesini yükler. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | Belirtilen TextReader'dan XML belgesini yükler. |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | Belirtilen [XmlReader](../xmlreader/)'den XML belgesini yükler. |
| virtual void [LoadXml](./loadxml/)([String](../../system/string/)) | Belirtilen dizeden XML belgesini yükler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
| virtual void [Normalize](../xmlnode/normalize/)() | [XmlText](../xmltext/) düğümlerinin bu [XmlNode](../xmlnode/) altındaki alt ağaçta tam derinlikteki tümünü, yalnızca işaretleme (etiketler, yorumlar, işleme talimatları, CDATA bölümleri ve varlık referansları) [XmlText](../xmltext/) düğümlerini ayırdığı bir "normal" forma getirir; yani yan yana [XmlText](../xmltext/) düğümleri bulunmaz. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü bu düğümün çocuk düğüm listesine başa ekler. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReadNode](./readnode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | [XmlReader](../xmlreader/) içindeki bilgilere dayanarak bir [XmlNode](../xmlnode/) nesnesi oluşturur. Okuyucu bir düğüm veya öznitelik üzerinde konumlandırılmış olmalıdır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nun string durumları için özelleştirmesi. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Mevcut düğümün tüm çocuk düğümlerini ve/veya özniteliklerini kaldırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen çocuk düğümünü kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Çocuk düğüm **oldChild**'ı **newChild** düğümüyle değiştirir. |
| virtual void [Save](./save/)([String](../../system/string/)) | XML belgesini belirtilen dosyaya kaydeder. Belirtilen dosya mevcutsa, bu yöntem üzerine yazar. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | XML belgesini belirtilen akışa kaydeder. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>) | XML belgesini belirtilen TextWriter'a kaydeder. |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>) | XML belgesini belirtilen [XmlWriter](../xmlwriter/)'e kaydeder. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen düğüm listesini seçer. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesini seçer. [XPath](../../system.xml.xpath/) ifadesinde bulunan tüm önekler sağlanan [XmlNamespaceManager](../xmlnamespacemanager/) kullanılarak çözülür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen ilk [XmlNode](../xmlnode/)'yi seçer. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen ilk [XmlNode](../xmlnode/)'yi seçer. [XPath](../../system.xml.xpath/) ifadesinde bulunan tüm önekler sağlanan [XmlNamespaceManager](../xmlnamespacemanager/) ile çözülür. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Tüm durumlarda InvalidOperationException fırlatır. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Mevcut düğümün çocuklarını temsil eden işaretlemeyi ayarlar. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Bu düğümün ad alanı önekini ayarlar. |
| void [set_PreserveWhitespace](./set_preservewhitespace/)(**bool**) | Eleman içeriğinde boşlukların korunup korunmayacağını belirten bir değer ayarlar. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Bu [XmlDocument](./) ile ilişkili XmlSchemaSet nesnesini ayarlar. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Düğümün değerini ayarlar. |
| virtual void [set_XmlResolver](./set_xmlresolver/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>) | Harici kaynakları çözmek için kullanılacak [XmlResolver](../xmlresolver/)'yi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | DOM uygulamasının belirli bir özelliği uygulayıp uygulamadığını test eder. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | [XmlDocument](./)'i [XmlDocument::get_Schemas](./get_schemas/) listesinde bulunan XML [Schema](../../system.xml.schema/) Tanım Dili (XSD) şemalarına karşı doğrular. |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | Belirtilen [XmlNode](../xmlnode/) nesnesini [XmlDocument::get_Schemas](./get_schemas/) listesinde bulunan XML [Schema](../../system.xml.schema/) Tanım Dili (XSD) şemalarına karşı doğrular. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Mevcut kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Mevcut kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Mevcut kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Mevcut kapsayıcı için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | [XmlDocument](./) düğümünün tüm çocuklarını belirtilen [XmlWriter](../xmlwriter/)'e kaydeder. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | [XmlDocument](./) düğümünü belirtilen [XmlWriter](../xmlwriter/)'e kaydeder. |
|  [XmlDocument](./xmldocument/)() | [XmlDocument](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlDocument](./xmldocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlNameTable](../xmlnametable/) ile belirtilen [XmlDocument](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak işaretçi için bir takma addır. |
## Açıklamalar



Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türden örnekler yığına ya da new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. 

## Bakınız

* Sınıf [XmlNode](../xmlnode/)
* İsim alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)