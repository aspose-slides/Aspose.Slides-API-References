---
title: XmlText
second_title: Aspose.Slides for C++ API Referansı
description: Bir öğenin veya özniteliğin metin içeriğini temsil eder.
type: docs
weight: 495
url: /tr/system.xml/xmltext/
---
## XmlText sınıf

Bir öğenin veya özniteliğin metin içeriğini temsil eder.

```cpp
class XmlText : public System::Xml::XmlCharacterData
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü, bu düğümün alt düğüm listesinin sonuna ekler. |
| virtual void [AppendData](../xmlcharacterdata/appenddata/)([String](../../system/string/)) | Belirtilen dizeyi, düğümün karakter verisinin sonuna ekler. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Koleksiyonun (varsa) ilk öğesine işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin bir kopya nesnesini döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Koleksiyonun const nitelikli örneğinin (varsa) ilk öğesine işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Koleksiyonun (varsa) ilk const nitelikli öğesine işaret eden yineleyiciyi alır. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Koleksiyonun (varsa) son const nitelikli öğesinden hemen sonrasına işaret eden yineleyiciyi alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Bu düğümün bir kopyasını oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Bu düğümün bir kopyasını oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Bu nesneyi gezmek için bir XPathNavigator oluşturur. |
| virtual void [DeleteData](../xmlcharacterdata/deletedata/)(**int32_t**, **int32_t**) | Düğümden bir karakter aralığını kaldırır. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Koleksiyonun (varsa) son öğesinden hemen sonrasına işaret eden yineleyiciyi alır. Bu yineleyici, [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) T'nin bir kopya nesnesini döndürdüğü için referans verilen nesneyi değiştirmek için kullanılamaz. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Koleksiyonun const nitelikli örneğinin (varsa) son öğesinden hemen sonrasına işaret eden yineleyiciyi alır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'ın eşit kabul edildiği C# tarzı çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | [XmlAttributeCollection](../xmlattributecollection/) döndürür; bu düğümün özniteliklerini içerir. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Geçerli düğümün temel URI'sını döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Düğümün tüm alt düğümlerini döndürür. |
| virtual [String](../../system/string/) [get_Data](../xmlcharacterdata/get_data/)() | Düğümün verisini döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Düğümün ilk alt düğümünü döndürür. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Bu düğümün herhangi bir alt düğümü olup olmadığını gösteren bir değer döndürür. |
| [String](../../system/string/) [get_InnerText](../xmlcharacterdata/get_innertext/)() override | Düğümün ve tüm alt düğümlerinin birleştirilmiş değerlerini döndürür. |
| virtual [String](../../system/string/) [get_InnerXml](../xmlnode/get_innerxml/)() | Bu düğümün yalnızca alt düğümlerini temsil eden işaretlemeyi döndürür. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Düğümün yalnızca okunur olup olmadığını gösteren bir değer döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Düğümün son alt düğümünü döndürür. |
| virtual **int32_t** [get_Length](../xmlcharacterdata/get_length/)() | Verinin uzunluğunu, karakter cinsinden döndürür. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Düğümün yerel adını döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Düğümün nitelikli adını döndürür. |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | Bu düğümün ad alanı URI'sını döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Bu düğümden hemen sonrasındaki düğümü döndürür. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Geçerli düğümün tipini döndürür. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Bu düğümü ve tüm alt düğümlerini içeren işaretlemeyi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](../xmlnode/get_ownerdocument/)() | Bu düğümün ait olduğu [XmlDocument](../xmldocument/) döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Bu düğümün ebeveynini döndürür (ebeveyni olabilen düğümler için). |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | Bu düğümün ad alanı ön ekini döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Bu düğümden hemen önceki düğümü döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](./get_previoustext/)() override | Bu düğümden hemen önce gelen metin düğümünü döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlnode/get_schemainfo/)() | Şema doğrulamasının bir sonucu olarak bu düğüme atanan post şema doğrulama bilgi kümesini döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Düğümün değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Geçerli düğümdeki alt düğümler arasında yineleme yapan bir döngücü döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Geçerli düğüm için kapsamda olan verilen önek için en yakın **xmlns** bildirimini bulur ve bildirideki ad alanı URI'sını döndürür. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Geçerli düğüm için kapsamda olan verilen ad alanı URI'si için en yakın **xmlns** bildirimini bulur ve o bildiride tanımlı önek'i döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Belirtilen [XmlNode::get_Name](../xmlnode/get_name/)'a sahip ilk alt öğeyi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen [XmlNode::get_LocalName](../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) değerlerine sahip ilk alt öğeyi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü, belirtilen referans düğümünden hemen sonra ekler. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü, belirtilen referans düğümünden hemen önce ekler. |
| virtual void [InsertData](../xmlcharacterdata/insertdata/)(**int32_t**, [String](../../system/string/)) | Belirtilen dizeyi, belirtilen karakter konumunda ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Bir dizi üzerinde bir biriktirici fonksiyon uygular. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bir dizideki tüm öğelerin bir koşulu sağlayıp sağlamadığını belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bir dizinin herhangi bir öğe içerip içermediğini belirler. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bir dizide herhangi bir öğenin var olup olmadığını veya bir koşulu sağlayıp sağlamadığını belirler. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Sayısal değerlerden oluşan bir dizinin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Girdi dizisindeki her öğeye bir dönüşüm fonksiyonu uygulayarak elde edilen değerlerin ortalamasını hesaplar. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Öğeleri belirtilen tipe dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | İki diziyi birleştirir. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bir dizinin belirtilen bir değeri içerip içermediğini belirler. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Dizideki öğe sayısını döndürür (doğrudan sayma ile hesaplanır). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan dizideki öğe sayısını döndürür. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Bir dizide belirtilen indeksteki öğeyi döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Bir dizinin ilk öğesini döndürür. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Belirtilen koşulu sağlayan bir dizinin ilk öğesini döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Bir dizinin ilk öğesini, dizi boşsa varsayılan bir değer döndürür. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Bir koşulu sağlayan dizinin ilk öğesini, böyle bir öğe bulunamazsa varsayılan bir değer döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Bir dizinin öğelerini gruplayarak döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Bir dizinin öğelerini gruplayarak döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Bir dizinin son öğesini döndürür. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Bir dizinin son öğesini, dizi boşsa varsayılan bir değer döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her öğeye bir dönüşüm fonksiyonu uygulayarak elde edilen maksimum değeri döndürür. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Genel bir dizideki her öğeye bir dönüşüm fonksiyonu uygulayarak elde edilen minimum değeri döndürür. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Dizinin öğelerini belirtilen tipe göre süzer. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini keySelector tarafından seçilen anahtar değerlerine göre artan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Bir dizinin öğelerini keySelector tarafından seçilen anahtar değerlerine göre azalan sırada sıralar. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Bir dizinin öğelerinin sırasını tersine çevirir. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Dizinin öğelerini dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Bir dizinin her öğesini, öğenin indeksini dahil ederek yeni bir forma dönüştürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda art arda öğeyi atlar ve geri kalanını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Bir dizinin başlangıcından belirli sayıda art arda öğeyi döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Bir diziden bir dizi (array) oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Bir diziden List<T> oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Belirtilen koşula göre bir diziyi süzer. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
| virtual void [Normalize](../xmlnode/normalize/)() | [XmlNode](../xmlnode/) altındaki alt ağacın tamamen derinliğindeki tüm [XmlText](./) düğümlerini, yalnızca işaretleme (yani etiketler, yorumlar, işlem talimatları, CDATA bölümleri ve varlık referansları) [XmlText](./) düğümlerini ayıran bir "normal" forma getirir; yani birbirine bitişik [XmlText](./) düğümleri bulunmaz. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya oluşturucu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını sağlar. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen düğümü, bu düğümün alt düğüm listesine başa ekler. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özgü bir türevi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumuna özgü bir türevi. |
| virtual void [RemoveAll](../xmlnode/removeall/)() | Geçerli düğümün tüm alt düğümlerini ve/veya özniteliklerini kaldırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Belirtilen alt düğümü kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | **oldChild** alt düğümünü **newChild** düğümüyle değiştirir. |
| virtual void [ReplaceData](../xmlcharacterdata/replacedata/)(**int32_t**, **int32_t**, [String](../../system/string/)) | Belirtilen konumdan başlayan belirtilen sayıda karakteri, belirtilen dizeyle değiştirir. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen bir düğüm listesi seçer. [XPath](../../system.xml.xpath/) ifadesinde bulunan tüm önekler, sağlanan [XmlNamespaceManager](../xmlnamespacemanager/) kullanılarak çözülür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen ilk [XmlNode](../xmlnode/)'yi seçer. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) ifadesiyle eşleşen ilk [XmlNode](../xmlnode/)'yi seçer. [XPath](../../system.xml.xpath/) ifadesinde bulunan tüm önekler, sağlanan [XmlNamespaceManager](../xmlnamespacemanager/) kullanılarak çözülür. |
| virtual void [set_Data](../xmlcharacterdata/set_data/)([String](../../system/string/)) | Düğümün verisini ayarlar. |
| void [set_InnerText](../xmlcharacterdata/set_innertext/)([String](../../system/string/)) override | Düğümün ve tüm alt düğümlerinin birleştirilmiş değerlerini ayarlar. |
| virtual void [set_InnerXml](../xmlnode/set_innerxml/)([String](../../system/string/)) | Bu düğümün yalnızca alt düğümlerini temsil eden işaretlemeyi ayarlar. |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | Bu düğümün ad alanı ön ekini ayarlar. |
| void [set_Value](./set_value/)([String](../../system/string/)) override | Düğümün değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](./)\> [SplitText](./splittext/)(**int32_t**) | Düğümü belirtilen konumda iki düğüme ayırır, ikisini de ağaçta kardeş olarak tutar. |
| virtual [String](../../system/string/) [Substring](../xmlcharacterdata/substring/)(**int32_t**, **int32_t**) | Belirtilen aralıktaki tam dizeden bir alt dize alır. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | DOM uygulamasının belirli bir özelliği destekleyip desteklemediğini test eder. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesneleri stringe dönüştürmeyi sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Geçerli kapsayıcı için begin const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Geçerli kapsayıcı için begin yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Geçerli kapsayıcı için end const yineleyicisinin uygulamasını alır. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Geçerli kapsayıcı için end yineleyicisinin uygulamasını alır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Düğümün tüm alt düğümlerini belirtilen [XmlWriter](../xmlwriter/)'ye kaydeder. [XmlText](./) düğümlerinin alt düğümü olmadığından bu yöntemin etkisi yoktur. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Düğümü belirtilen [XmlWriter](../xmlwriter/)'ye kaydeder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak gösterici için bir takma addır. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini yığıt (stack) üzerinde ya da new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

## Diğer

* Sınıf [XmlCharacterData](../xmlcharacterdata/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)