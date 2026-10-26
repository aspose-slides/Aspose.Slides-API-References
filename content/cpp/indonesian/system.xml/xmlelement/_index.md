---
title: XmlElement
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sebuah elemen.
type: docs
weight: 222
url: /id/system.xml/xmlelement/
---
## XmlElement kelas


Represents an element.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Menambahkan node yang ditentukan ke akhir daftar node anak dari node ini. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Mendapatkan iterator yang menunjuk ke elemen pertama (jika ada) dari koleksi. Iterator ini tidak dapat digunakan untuk mengubah objek yang dirujuk karena [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) mengembalikan objek salinan dari T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Mendapatkan iterator yang menunjuk ke elemen pertama (jika ada) dari instance koleksi yang dikualifikasi const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Mendapatkan iterator yang menunjuk ke elemen pertama yang dikualifikasi const (jika ada) dari koleksi. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir yang dikualifikasi const (jika ada) dari koleksi. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | Membuat duplikat dari node ini. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | Membuat duplikat dari node ini. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | Membuat XPathNavigator untuk menavigasi objek ini. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir (jika ada) dari koleksi. Iterator ini tidak dapat digunakan untuk mengubah objek yang dirujuk karena [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) mengembalikan objek salinan dari T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir (jika ada) dari instance koleksi yang dikualifikasi const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | Mengembalikan [XmlAttributeCollection](../xmlattributecollection/) yang berisi atribut node ini. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | Mengembalikan URI dasar dari node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | Mengembalikan semua node anak dari node. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | Mengembalikan anak pertama dari node. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Mengembalikan nilai **bool** yang menunjukkan apakah node saat ini memiliki atribut apa pun. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | Mengembalikan nilai yang menunjukkan apakah node ini memiliki node anak apa pun. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | Mengembalikan nilai yang digabungkan dari node dan semua anaknya. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | Mengembalikan markup yang mewakili hanya anak-anak node ini. |
| **bool** [get_IsEmpty](./get_isempty/)() | Mengembalikan format tag dari elemen. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | Mengembalikan nilai yang menunjukkan apakah node hanya-baca. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | Mengembalikan anak terakhir dari node. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Mengembalikan nama lokal dari node saat ini. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mengembalikan nama yang memenuhi syarat dari node. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Mengembalikan namespace URI dari node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | Mengembalikan node yang langsung mengikuti node ini. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Mengembalikan tipe dari node saat ini. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | Mengembalikan markup yang berisi node ini dan semua node anaknya. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | Mengembalikan [XmlDocument](../xmldocument/) tempat node ini berada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | Mengembalikan induk dari node ini (untuk node yang dapat memiliki induk). |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Mengembalikan prefiks namespace dari node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | Mengembalikan node yang langsung mendahului node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | Mengembalikan node teks yang langsung mendahului node ini. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Mengembalikan infoset validasi skema pasca yang telah diterapkan pada node ini sebagai hasil dari validasi skema. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | Mengembalikan nilai dari node. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Mengembalikan nilai untuk atribut dengan nama yang ditentukan. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan nilai untuk atribut dengan nama lokal dan namespace URI yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | Mengembalikan [XmlAttribute](../xmlattribute/) dengan nama yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan [XmlAttribute](../xmlattribute/) dengan nama lokal dan namespace URI yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | Mengembalikan [XmlNodeList](../xmlnodelist/) yang berisi daftar semua elemen keturunan yang cocok dengan [XmlElement::get_Name](./get_name/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan [XmlNodeList](../xmlnodelist/) yang berisi daftar semua elemen keturunan yang cocok dengan nilai [XmlElement::get_LocalName](./get_localname/) dan [XmlElement::get_NamespaceURI](./get_namespaceuri/) yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | Mengembalikan enumerator yang mengiterasi node anak dalam node saat ini. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | Mencari deklarasi **xmlns** terdekat untuk prefiks yang diberikan yang berada dalam lingkup node saat ini dan mengembalikan namespace URI dalam deklarasi tersebut. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | Mencari deklarasi **xmlns** terdekat untuk namespace URI yang diberikan yang berada dalam lingkup node saat ini dan mengembalikan prefiks yang didefinisikan dalam deklarasi tersebut. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | Menentukan apakah node saat ini memiliki atribut dengan nama yang ditentukan. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | Menentukan apakah node saat ini memiliki atribut dengan nama lokal dan namespace URI yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | Mengembalikan elemen anak pertama dengan [XmlNode::get_Name](../xmlnode/get_name/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan elemen anak pertama dengan nilai [XmlNode::get_LocalName](../xmlnode/get_localname/) dan [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Menyisipkan node yang ditentukan tepat setelah node referensi yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Menyisipkan node yang ditentukan tepat sebelum node referensi yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Menerapkan fungsi akumulator pada sebuah urutan. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Menentukan apakah semua elemen dalam urutan memenuhi kondisi. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Menentukan apakah sebuah urutan berisi elemen apa pun. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Menentukan apakah ada elemen dalam urutan yang ada atau memenuhi suatu kondisi. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Menghitung rata-rata dari urutan nilai numerik. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Menghitung rata-rata dari urutan nilai yang diperoleh dengan memanggil fungsi transform pada setiap elemen dari urutan masukan. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Mencast elemen ke tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Menggabungkan dua urutan. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Menentukan apakah urutan berisi nilai yang ditentukan. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Mengembalikan jumlah elemen dalam urutan (dihitung via penghitungan langsung). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan jumlah elemen dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Mengembalikan elemen pertama dari urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Mengembalikan elemen pertama dari urutan, atau nilai default jika urutan kosong. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi atau nilai default jika tidak ada elemen tersebut. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Mengelompokkan elemen-elemen dari sebuah urutan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Mengelompokkan elemen-elemen dari sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Mengembalikan elemen terakhir dari urutan. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Mengembalikan elemen terakhir dari urutan, atau nilai default jika urutan kosong. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transform pada setiap elemen dari urutan generik dan mengembalikan nilai maksimum yang dihasilkan. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Memanggil fungsi transform pada setiap elemen dari urutan generik dan mengembalikan nilai minimum yang dihasilkan. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Menyaring elemen urutan berdasarkan tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara naik menurut nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen urutan secara turun menurut nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Membalik urutan elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Mengubah elemen-elemen dalam urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Mengubah setiap elemen dalam urutan menjadi bentuk baru dengan memasukkan indeks elemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\&) | Menerapkan setiap elemen dari urutan dan menggabungkan urutan yang dihasilkan menjadi satu urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Lewati sejumlah elemen berurutan yang ditentukan dari awal urutan dan kembalikan sisanya. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Mengembalikan sejumlah elemen berurutan yang ditentukan dari awal urutan. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Membuat array dari sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Membuat List<T> dari sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Menyaring urutan berdasarkan predikat yang ditentukan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan cloning tipe khusus. |
| virtual void [Normalize](../xmlnode/normalize/)() | Menempatkan semua node [XmlText](../xmltext/) pada kedalaman penuh dari sub-tree di bawah [XmlNode](../xmlnode/) ini ke dalam bentuk \"normal\" di mana hanya markup (yaitu tag, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas) yang memisahkan node [XmlText](../xmltext/), yaitu tidak ada node [XmlText](../xmltext/) yang bersebelahan. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor penyalin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor penyalin pada subclass. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Menambahkan node yang ditentukan ke awal daftar node anak untuk node ini. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| void [RemoveAll](./removeall/)() override | Menghapus semua atribut dan anak yang ditentukan dari node saat ini. Atribut default tidak dihapus. |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | Menghapus semua atribut yang ditentukan dari elemen. Atribut default tidak dihapus. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | Menghapus atribut berdasarkan nama. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | Menghapus atribut dengan nama lokal dan URI namespace yang ditentukan. (Jika atribut yang dihapus memiliki nilai default, nilai tersebut langsung diganti). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | Menghapus node atribut dengan indeks yang ditentukan dari elemen. (Jika atribut yang dihapus memiliki nilai default, nilai tersebut langsung diganti). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Menghapus [XmlAttribute](../xmlattribute/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | Menghapus [XmlAttribute](../xmlattribute/) yang ditentukan oleh nama lokal dan URI namespace. (Jika atribut yang dihapus memiliki nilai default, nilai tersebut langsung diganti). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Menghapus node anak yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | Mengganti node anak **oldChild** dengan node **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | Memilih daftar node yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Memilih daftar node yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). Setiap prefiks yang ditemukan dalam ekspresi [XPath](../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../xmlnamespacemanager/) yang diberikan. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | Memilih [XmlNode](../xmlnode/) pertama yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Memilih [XmlNode](../xmlnode/) pertama yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). Setiap prefiks yang ditemukan dalam ekspresi [XPath](../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../xmlnamespacemanager/) yang diberikan. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | Mengatur nilai gabungan node dan semua anaknya. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | Mengatur markup yang mewakili hanya anak node ini. |
| void [set_IsEmpty](./set_isempty/)(**bool**) | Mengatur format tag elemen. |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | Mengatur prefiks namespace node ini. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | Mengatur nilai node. |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | Mengatur nilai atribut dengan nama yang ditentukan. |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Mengatur nilai atribut dengan nama lokal dan URI namespace yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | Menambahkan [XmlAttribute](../xmlattribute/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | Menambahkan [XmlAttribute](../xmlattribute/) yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | Menguji apakah implementasi DOM mendukung fitur khusus. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk [System.Object](../../system/object/) dalam C# typeof(). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Mendapatkan implementasi iterator const begin untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Mendapatkan implementasi iterator begin untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Mendapatkan implementasi iterator const end untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Mendapatkan implementasi iterator end untuk kontainer saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Menyimpan semua anak node ke [XmlWriter](../xmlwriter/) yang ditentukan. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | Menyimpan node saat ini ke [XmlWriter](../xmlwriter/) yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## TipeDef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke suatu instance kelas ini. |
## Catatan

Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan assert. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Pustaka [Aspose.Slides](../../)