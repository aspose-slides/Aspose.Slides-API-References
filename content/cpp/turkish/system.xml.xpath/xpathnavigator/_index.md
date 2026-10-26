---
title: XPathNavigator
second_title: Aspose.Slides for C++ API Referansı
description: XML verilerini gezinmek ve düzenlemek için bir imleç modeli sağlar.
type: docs
weight: 66
url: /tr/system.xml.xpath/xpathnavigator/
---
## XPathNavigator sınıf

XML verilerini gezmek ve düzenlemek için bir imleç modeli sağlar.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | [XmlWriter](../../system.xml/xmlwriter/) nesnesini döndürür; bu nesne, geçerli düğümün çocuk düğüm listesi sonuna bir veya daha fazla yeni çocuk düğüm oluşturmak için kullanılır. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Belirtilen XML veri dizgisini kullanarak geçerli düğümün çocuk düğüm listesi sonuna yeni bir çocuk düğüm oluşturur. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak geçerli düğümün çocuk düğüm listesi sonuna yeni bir çocuk düğüm oluşturur. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Belirtilen [XPathNavigator](./) içindeki düğümleri kullanarak geçerli düğümün çocuk düğüm listesi sonuna yeni bir çocuk düğüm oluşturur. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Belirtilen ad alanı ön eki, yerel ad ve ad alanı URI'si ile belirtilen değeri kullanarak geçerli düğümün çocuk düğüm listesi sonuna yeni bir çocuk element düğümü oluşturur. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | [XPathNavigator](./) içindeki XML verisinin sağlanan XML [Schema](../../system.xml.schema/) tanım dili (XSD) şemasına uyup uymadığını doğrular. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu [XPathNavigator](./) ile aynı düğümde konumlandırılmış yeni bir [XPathNavigator](./) oluşturur. |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Geçerli [XPathNavigator](./) konumunu belirtilen [XPathNavigator](./) konumu ile karşılaştırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | [XPath](../) ifadesini temsil eden bir dizeyi derler ve bir [XPathExpression](../xpathexpression/) nesnesi döndürür. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Belirtilen ad alanı ön eki, yerel ad ve ad alanı URI'si ile verilen değeri kullanarak geçerli element düğümüne bir nitelik düğümü oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Geçerli element üzerinde yeni nitelikler oluşturmak için kullanılan bir [XmlWriter](../../system.xml/xmlwriter/) nesnesi döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | [XPathNavigator](./)'nin bir kopyasını döndürür. |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Geçerli düğümden belirtilen düğüme kadar olan bir dizi kardeş düğümü siler. |
| virtual void [DeleteSelf](./deleteself/)() | Geçerli düğümü ve onun çocuk düğümlerini siler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | İki NaN'ın, IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmamasına rağmen, C# tarzı kayan nokta karşılaştırmasını taklit eder; bu durumda iki NaN eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | İki NaN'ın, IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmamasına rağmen, C# tarzı çift kayan nokta karşılaştırmasını taklit eder; bu durumda iki NaN eşit kabul edilir. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Belirtilen [XPath](../) ifadesini değerlendirir ve tiplenmiş sonucu döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Belirtilen [XPath](../) ifadesini değerlendirir ve tiplenmiş sonucu döndürür; [XPath](../) ifadesindeki ad alanı ön eklerini çözmek için belirtilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesini kullanır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | [XPathExpression](../xpathexpression/) ifadesini değerlendirir ve tiplenmiş sonucu döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Sağlanan bağlamı kullanarak [XPathExpression](../xpathexpression/) ifadesini değerlendirir ve tiplenmiş sonucu döndürür. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün temel URI'sını alır. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | [XPathNavigator](./)'nin temel XML verisini düzenleyip düzenleyemeyeceğini gösteren bir değer döndürür. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Geçerli düğümün herhangi bir niteliği olup olmadığını belirten bir değer döndürür. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Geçerli düğümün herhangi bir çocuk düğümü olup olmadığını belirten bir değer döndürür. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Geçerli düğümün çocuk düğümlerini temsil eden işaretlemeyi döndürür. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün son etiket olmadan boş bir öğe olup olmadığını gösteren bir değer alır. |
| **bool** [get_IsNode](./get_isnode/)() override | Geçerli düğümün bir [XPath](../) düğümü temsil edip etmediğini gösteren bir değer döndürür. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün ad alanı ön eki olmadan [XPathNavigator::get_Name](./get_name/) değerini alır. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün nitelikli adını alır. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün ad alanı URI'sını alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](./)'in [XmlNameTable](../../system.xml/xmlnametable/)'sini alır. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | [XPathNavigator](./) nesnelerinin eşitlik karşılaştırması için kullanılan bir [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) döndürür. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün XPathNodeType'ını alır. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Geçerli düğümün ve onun çocuk düğümlerinin açılış ve kapanış etiketlerini temsil eden işaretlemi döndürür. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümle ilişkili ad alanı ön ekini alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Şema doğrulaması sonucu geçerli düğüme atanan şema bilgilerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Geçerli düğümü en uygun tipte bir kutulanmış nesne olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | [XPathNavigator](./) implementasyonları tarafından, bir depolama üzerinde "sanallaştırılmış" XML görünümü sağlayarak temel nesnelere erişim sunmak için kullanılır. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Türetilmiş bir sınıfta geçersiz kılındığında, öğenin **string** değerini alır. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Geçerli düğümün değerini bir [Boolean](../../system/boolean/) olarak döndürür. |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Geçerli düğümün değerini bir [DateTime](../../system/datetime/) olarak döndürür. |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Geçerli düğümün değerini bir [Double](../../system/double/) olarak döndürür. |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Geçerli düğümün değerini bir [Int32](../../system/int32/) olarak döndürür. |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Geçerli düğümün değerini bir [Int64](../../system/int64/) olarak döndürür. |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Geçerli düğümün tipini döndürür. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Geçerli düğüm için **xml:lang** kapsamını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Geçerli düğüm için XmlSchemaType bilgisini döndürür. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip niteliğin değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Belirtilen yerel ada karşılık gelen ad alanı düğümünün değerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Geçerli düğümün kapsam içindeki ad alanlarını döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Şu an seçili düğümden sonra yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../system.xml/xmlwriter/) nesnesi döndürür. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Belirtilen XML dizesini kullanarak şu an seçili düğümden sonra yeni bir kardeş düğüm oluşturur. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak şu an seçili düğümden sonra yeni bir kardeş düğüm oluşturur. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Belirtilen [XPathNavigator](./) nesnesindeki düğümleri kullanarak şu an seçili düğümden sonra yeni bir kardeş düğüm oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Şu an seçili düğümden önce yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../system.xml/xmlwriter/) nesnesi döndürür. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Belirtilen XML dizesini kullanarak şu an seçili düğümden önce yeni bir kardeş düğüm oluşturur. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak şu an seçili düğümden önce yeni bir kardeş düğüm oluşturur. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Belirtilen [XPathNavigator](./) içindeki düğümleri kullanarak şu an seçili düğümden önce yeni bir kardeş düğüm oluşturur. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Belirtilen ad alanı ön eki, yerel ad ve ad alanı URI'si ve verilen değer ile geçerli düğümden sonra yeni bir kardeş öğe oluşturur. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Belirtilen ad alanı ön eki, yerel ad ve ad alanı URI'si ve verilen değer ile geçerli düğümden önce yeni bir kardeş öğe oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Belirtilen [XPathNavigator](./)'nin geçerli [XPathNavigator](./)'nin bir alt öğesi olup olmadığını belirler. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli [XPathNavigator](./)'nin belirtilen [XPathNavigator](./) ile aynı konumda olup olmadığını belirler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Belirtilen ön ek için ad alanı URI'sını döndürür. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Belirtilen ad alanı URI'si için bildirilen ön eki döndürür. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Geçerli düğümün belirtilen [XPathExpression](../xpathexpression/) ile eşleşip eşleşmediğini belirler. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Geçerli düğümün belirtilen [XPath](../) ifadesiyle eşleşip eşleşmediğini belirler. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi belirtilen [XPathNavigator](./) ile aynı konuma taşır. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)'yi eşleşen yerel ad ve ad alanı URI'sine sahip niteliğe taşır. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)'yi belirtilen yerel ad ve ad alanı URI'sine sahip çocuk düğüme taşır. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)'yi belirtilen XPathNodeType'ın çocuk düğümüne taşır. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | [XPathNavigator](./)'yi geçerli düğümün ilk kardeş düğümüne taşır. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi geçerli düğümün ilk niteliğine taşır. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi geçerli düğümün ilk çocuk düğümüne taşır. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Türetilmiş bir sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi belirtilen XPathNamespaceScope ile eşleşen ilk ad alanı düğümüne taşır. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | [XPathNavigator](./)'yi mevcut düğümün ilk ad alanı düğümüne taşır. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)'yi belge sırasına göre belirtilen yerel ad ve ad alanı URI'sine sahip öğeye taşır. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./)'yi belge sırasına göre belirtilen yerel ad ve ad alanı URI'sine ve belirtilen sınıra sahip öğeye taşır. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)'yi belge sırasına göre belirtilen XPathNodeType'ın sonraki öğesine taşır. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./)'yi belge sırasına göre belirtilen XPathNodeType'ın ve belirtilen sınıra sahip sonraki öğesine taşır. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, değeri belirtilen [String](../../system/string/) ile eşleşen **ID** tipinde bir özniteliğe sahip düğüme taşır. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | [XPathNavigator](./)'yi belirtilen ad alanı önekiyle ad alanı düğümüne taşır. |
| virtual **bool** [MoveToNext](./movetonext/)() | Türev sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi mevcut düğümün bir sonraki kardeş düğümüne taşır. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)'yi belirtilen yerel ad ve ad alanı URI'sine sahip bir sonraki kardeş düğüme taşır. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)'yi mevcut düğümün belirtilen XPathNodeType ile eşleşen bir sonraki kardeş düğümüne taşır. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Türev sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi bir sonraki özniteliğe taşır. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Türev sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi belirtilen XPathNamespaceScope ile eşleşen bir sonraki ad alanı düğümüne taşır. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | [XPathNavigator](./)'yi bir sonraki ad alanı düğümüne taşır. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Türev sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi mevcut düğümün üst düğümüne taşır. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Türev sınıfta geçersiz kılındığında, [XPathNavigator](./)'yi mevcut düğümün önceki kardeş düğümüne taşır. |
| virtual void [MoveToRoot](./movetoroot/)() | [XPathNavigator](./)'yi mevcut düğümün ait olduğu kök düğüme taşır. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Mevcut düğümün alt düğüm listesine baştan yeni bir alt düğüm eklemek için kullanılan bir [XmlWriter](../../system.xml/xmlwriter/) nesnesi döndürür. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Belirtilen XML dizesini kullanarak mevcut düğümün alt düğüm listesine baştan yeni bir alt düğüm oluşturur. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak mevcut düğümün alt düğüm listesine baştan yeni bir alt düğüm oluşturur. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Belirtilen [XPathNavigator](./) nesnesindeki düğümleri kullanarak mevcut düğümün alt düğüm listesine baştan yeni bir alt düğüm oluşturur. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Belirtilen ad alanı öneki, yerel ad ve ad alanı URI'si ile belirtilen değeri kullanarak mevcut düğümün alt düğüm listesine baştan yeni bir alt öğe oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Mevcut düğüm ve alt düğümlerini içeren bir [XmlReader](../../system.xml/xmlreader/) nesnesi döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özgü özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özgü özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mevcut düğümden belirtilen düğüme kadar bir dizi kardeş düğümü değiştirir. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Mevcut düğümü belirtilen dize içeriğiyle değiştirir. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Mevcut düğümü belirtilen [XmlReader](../../system.xml/xmlreader/) nesnesinin içeriğiyle değiştirir. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mevcut düğümü belirtilen [XPathNavigator](./) nesnesinin içeriğiyle değiştirir. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Belirtilen [XPath](../) ifadesini kullanarak bir düğüm kümesi seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Belirtilen [XPath](../) ifadesini ve ad alanı öneklerini çözmek için verilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak bir düğüm kümesi seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Belirtilen [XPathExpression](../xpathexpression/) kullanarak bir düğüm kümesi seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Eşleşen XPathNodeType'a sahip mevcut düğümün tüm üst düğümlerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Belirtilen yerel ad ve ad alanı URI'sine sahip mevcut düğümün tüm üst düğümlerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Eşleşen XPathNodeType'a sahip mevcut düğümün tüm alt düğümlerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip mevcut düğümün tüm alt düğümlerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Eşleşen XPathNodeType'a sahip mevcut düğümün tüm alt nesillerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Belirtilen yerel ad ve ad alanı URI'sine sahip mevcut düğümün tüm alt nesillerini seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Belirtilen [XPath](../) sorgusunu kullanarak [XPathNavigator](./) içinde tek bir düğüm seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Belirtilen [XPath](../) sorgusunu ve ad alanı öneklerini çözmek için verilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak [XPathNavigator](./) nesnesi içinde tek bir düğüm seçer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Belirtilen [XPathExpression](../xpathexpression/) nesnesini kullanarak [XPathNavigator](./) içinde tek bir düğüm seçer. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Mevcut düğümün alt düğümlerini temsil eden işaretlemeyi ayarlar. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Mevcut düğüm ve alt düğümlerinin açılış ve kapanış etiketlerini temsil eden işaretlemeyi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf gösterici (paylaşımlı yerine) ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Mevcut düğümün tipli değerini ayarlar. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Mevcut düğümün değerini ayarlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mevcut düğümün metin değerini döndürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | [System.Object](../../system/object/) için C# typeof() yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Mevcut düğümün değerini belirtilen Tip olarak döndürür, ad alanı öneklerini çözmek için verilen [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) nesnesini kullanarak. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Öğenin değerini belirtilen tipte döndürür. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Mevcut düğüm ve alt düğümleri belirtilen [XmlWriter](../../system.xml/xmlwriter/) nesnesine akıtır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine paylaşılan gösterici için bir takma isim. |

## Bakınız

* Sınıf [XPathItem](../xpathitem/)
* Sınıf [IXPathNavigable](../ixpathnavigable/)
* Sınıf [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Ad Alanı [System::Xml::XPath](../)
* Kütüphane [Aspose.Slides](../../)