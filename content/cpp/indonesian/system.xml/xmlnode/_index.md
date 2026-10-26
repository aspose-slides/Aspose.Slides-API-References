---
title: XmlNode
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili satu node tunggal dalam dokumen XML.
type: docs
weight: 326
url: /id/system.xml/xmlnode/
---
## XmlNode kelas

Mewakili satu node tunggal dalam dokumen XML.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Menambahkan node yang ditentukan ke akhir daftar node anak dari node ini. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Mendapatkan iterator yang menunjuk ke elemen pertama (jika ada) dari koleksi. Iterator ini tidak dapat digunakan untuk mengubah objek yang direferensikan karena [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) mengembalikan objek salinan dari T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Mendapatkan iterator yang menunjuk ke elemen pertama (jika ada) dari instance koleksi yang bersifat const. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Mendapatkan iterator yang menunjuk ke elemen pertama yang bersifat const (jika ada) dari koleksi. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir yang bersifat const (jika ada) dari koleksi. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [Clone](./clone/)() | Membuat duplikat dari node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [CloneNode](./clonenode/)(**bool**) | Membuat duplikat dari node, ketika dioverride dalam kelas turunan. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | Membuat XPathNavigator untuk menavigasi objek ini. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir (jika ada) dari koleksi. Iterator ini tidak dapat digunakan untuk mengubah objek yang direferensikan karena [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) mengembalikan objek salinan dari T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Mendapatkan iterator yang menunjuk tepat setelah elemen terakhir (jika ada) dari instance koleksi yang bersifat const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](./get_attributes/)() | Mengembalikan sebuah [XmlAttributeCollection](../xmlattributecollection/) yang berisi atribut-atribut node ini. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Mengembalikan URI dasar dari node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](./get_childnodes/)() | Mengembalikan semua node anak dari node. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_FirstChild](./get_firstchild/)() | Mengembalikan anak pertama dari node. |
| virtual **bool** [get_HasChildNodes](./get_haschildnodes/)() | Mengembalikan nilai yang menunjukkan apakah node ini memiliki node anak. |
| virtual [String](../../system/string/) [get_InnerText](./get_innertext/)() | Mengembalikan nilai yang digabungkan dari node dan semua node anaknya. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Mengembalikan markup yang hanya mewakili node anak dari node ini. |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() | Mengembalikan nilai yang menunjukkan apakah node bersifat read-only. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_LastChild](./get_lastchild/)() | Mengembalikan anak terakhir dari node. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Mengembalikan nama lokal node, ketika dioverride dalam kelas turunan. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Mengembalikan nama lengkap node, ketika dioverride dalam kelas turunan. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Mengembalikan namespace URI dari node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_NextSibling](./get_nextsibling/)() | Mengembalikan node yang langsung mengikuti node ini. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Mengembalikan tipe node saat ini, ketika dioverride dalam kelas turunan. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Mengembalikan markup yang berisi node ini dan semua node anaknya. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() | Mengembalikan [XmlDocument](../xmldocument/) yang menjadi milik node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_ParentNode](./get_parentnode/)() | Mengembalikan induk dari node ini (untuk node yang dapat memiliki induk). |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Mengembalikan prefiks namespace dari node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousSibling](./get_previoussibling/)() | Mengembalikan node yang langsung mendahului node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousText](./get_previoustext/)() | Mengembalikan node teks yang langsung mendahului node ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Mengembalikan infoset pasca validasi skema yang telah ditetapkan pada node ini sebagai hasil dari validasi skema. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Mengembalikan nilai node. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>\>\> [GetEnumerator](./getenumerator/)() override | Mengembalikan enumerator yang mengiterasi node anak dalam node saat ini. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](./getnamespaceofprefix/)([String](../../system/string/)) | Mencari deklarasi **xmlns** terdekat untuk prefiks yang diberikan yang berada dalam lingkup node saat ini dan mengembalikan namespace URI dalam deklarasi. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](./getprefixofnamespace/)([String](../../system/string/)) | Mencari deklarasi **xmlns** terdekat untuk namespace URI yang diberikan yang berada dalam lingkup node saat ini dan mengembalikan prefiks yang didefinisikan dalam deklarasi tersebut. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/)) | Mengembalikan elemen anak pertama dengan [XmlNode::get_Name](./get_name/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan elemen anak pertama dengan nilai [XmlNode::get_LocalName](./get_localname/) dan [XmlNode::get_NamespaceURI](./get_namespaceuri/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Menyisipkan node yang ditentukan tepat setelah node referensi yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Menyisipkan node yang ditentukan tepat sebelum node referensi yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Menerapkan fungsi akumulator pada sebuah urutan. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Menentukan apakah semua elemen urutan memenuhi suatu kondisi. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Menentukan apakah urutan berisi elemen apa pun. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Menentukan apakah ada elemen dalam urutan atau apakah elemen tersebut memenuhi suatu kondisi. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Menghitung rata-rata dari urutan nilai numerik. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Menghitung rata-rata dari urutan nilai yang diperoleh dengan memanggil fungsi transform pada setiap elemen urutan masukan. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Mengubah tipe elemen menjadi tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Menggabungkan dua urutan. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Menentukan apakah urutan berisi nilai yang ditentukan. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Mengembalikan jumlah elemen dalam urutan (dihitung melalui penghitungan langsung). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan jumlah elemen dalam urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Mengembalikan elemen pada indeks yang ditentukan dalam urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Mengembalikan elemen pertama dari urutan. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi yang ditentukan. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Mengembalikan elemen pertama dari urutan, atau nilai default jika urutan kosong. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Mengembalikan elemen pertama dari urutan yang memenuhi kondisi atau nilai default jika tidak ada elemen seperti itu. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Menyaring elemen-elemen urutan berdasarkan tipe yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen-elemen urutan secara naik berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Mengurutkan elemen-elemen urutan secara menurun berdasarkan nilai kunci yang dipilih oleh keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Membalik urutan elemen dalam sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Mengubah elemen-elemen sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Mengubah setiap elemen urutan menjadi bentuk baru dengan memasukkan indeks elemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Memplot setiap elemen urutan dan menggabungkan urutan-urutan hasil menjadi satu urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Melewatkan sejumlah elemen berurutan yang ditentukan dari awal urutan dan mengembalikan sisanya. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Mengembalikan sejumlah elemen berurutan yang ditentukan dari awal urutan. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Membuat array dari sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Membuat List<T> dari sebuah urutan. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Menyaring urutan berdasarkan predikat yang ditentukan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
| virtual void [Normalize](./normalize/)() | Menempatkan semua node [XmlText](../xmltext/) pada kedalaman penuh sub-pohon di bawah [XmlNode](./) ini ke dalam bentuk "normal" dimana hanya markup (yaitu tag, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas) yang memisahkan node [XmlText](../xmltext/), sehingga tidak ada node [XmlText](../xmltext/) yang bersebelahan. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Menambahkan node yang ditentukan ke awal daftar node anak untuk node ini. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| virtual void [RemoveAll](./removeall/)() | Menghapus semua node anak dan/atau atribut dari node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [RemoveChild](./removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Menghapus node anak yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [ReplaceChild](./replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | Mengganti node anak **oldChild** dengan node **newChild**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&) | Memilih daftar node yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Memilih daftar node yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). Semua prefiks yang ditemukan dalam ekspresi [XPath](../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../xmlnamespacemanager/) yang disediakan. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&) | Memilih [XmlNode](./) pertama yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Memilih [XmlNode](./) pertama yang cocok dengan ekspresi [XPath](../../system.xml.xpath/). Semua prefiks yang ditemukan dalam ekspresi [XPath](../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../xmlnamespacemanager/) yang diberikan. |
| virtual void [set_InnerText](./set_innertext/)([String](../../system/string/)) | Menetapkan nilai yang digabungkan dari node dan semua node anaknya. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Menetapkan markup yang hanya mewakili node anak dari node ini. |
| virtual void [set_Prefix](./set_prefix/)([String](../../system/string/)) | Menetapkan prefiks namespace dari node ini. |
| virtual void [set_Value](./set_value/)([String](../../system/string/)) | Menetapkan nilai node. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual **bool** [Supports](./supports/)([String](../../system/string/), [String](../../system/string/)) | Menguji apakah implementasi DOM mendukung fitur spesifik. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Mendapatkan implementasi begin const iterator untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Mendapatkan implementasi begin iterator untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Mendapatkan implementasi end const iterator untuk kontainer saat ini. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Mendapatkan implementasi end iterator untuk kontainer saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Menyimpan semua node anak ke [XmlWriter](../xmlwriter/) yang ditentukan, ketika dioverride dalam kelas turunan. |
| virtual void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | Menyimpan node saat ini ke [XmlWriter](../xmlwriter/) yang ditentukan, ketika dioverride dalam kelas turunan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## TipeDef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance dari kelas ini. |

## Lihat Juga

* Kelas [IEnumerable](../../system.collections.generic/ienumerable/)
* Kelas [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)