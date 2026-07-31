---
title: XPathNavigator
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan model kursor untuk menavigasi dan mengedit data XML.
type: docs
weight: 66
url: /id/system.xml.xpath/xpathnavigator/
---
## XPathNavigator class

Menyediakan model kursor untuk menavigasi dan mengedit data XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Deskripsi |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Mengembalikan sebuah objek [XmlWriter](../../system.xml/xmlwriter/) yang digunakan untuk membuat satu atau lebih node anak baru di akhir daftar node anak dari node saat ini. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan string data XML yang ditentukan. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan konten XML dari objek [XmlReader](../../system.xml/xmlreader/) yang ditentukan. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Membuat node anak baru di akhir daftar node anak dari node saat ini menggunakan node-node dalam [XPathNavigator](./) yang ditentukan. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat node elemen anak baru di akhir daftar node anak dari node saat ini menggunakan prefiks namespace, nama lokal, dan URI namespace yang ditentukan bersama nilai yang ditentukan. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Memverifikasi bahwa data XML dalam [XPathNavigator](./) sesuai dengan skema bahasa definisi XML [Schema](../../system.xml.schema/) (XSD) yang disediakan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Ketika di-override dalam kelas turunan, membuat sebuah [XPathNavigator](./) baru yang diposisikan pada node yang sama dengan [XPathNavigator](./) ini. |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Membandingkan posisi [XPathNavigator](./) saat ini dengan posisi [XPathNavigator](./) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Mengkombinasikan sebuah string yang merepresentasikan ekspresi [XPath](../) dan mengembalikan sebuah objek [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat node atribut pada node elemen saat ini menggunakan prefiks namespace, nama lokal, dan URI namespace yang ditentukan bersama nilai yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Mengembalikan sebuah objek [XmlWriter](../../system.xml/xmlwriter/) yang digunakan untuk membuat atribut baru pada elemen saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Mengembalikan salinan dari [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Menghapus rentang node saudara dari node saat ini hingga node yang ditentukan. |
| virtual void [DeleteSelf](./deleteself/)() | Menghapus node saat ini beserta node anaknya. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Mengevaluasi ekspresi [XPath](../) yang ditentukan dan mengembalikan hasil bertipe. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Mengevaluasi ekspresi [XPath](../) yang ditentukan dan mengembalikan hasil bertipe, menggunakan objek [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace dalam ekspresi [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Mengevaluasi [XPathExpression](../xpathexpression/) dan mengembalikan hasil bertipe. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Menggunakan konteks yang diberikan untuk mengevaluasi [XPathExpression](../xpathexpression/), dan mengembalikan hasil bertipe. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Ketika di-override dalam kelas turunan, mendapatkan URI dasar untuk node saat ini. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Mengembalikan nilai yang menunjukkan apakah [XPathNavigator](./) dapat mengedit data XML yang mendasarinya. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki atribut apa pun. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Mengembalikan nilai yang menunjukkan apakah node saat ini memiliki node anak apa pun. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Mengembalikan markup yang merepresentasikan node anak dari node saat ini. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Ketika di-override dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah node saat ini adalah elemen kosong tanpa tag elemen penutup. |
| **bool** [get_IsNode](./get_isnode/)() override | Mengembalikan nilai yang menunjukkan apakah node saat ini mewakili node [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Ketika di-override dalam kelas turunan, mendapatkan [XPathNavigator::get_Name](./get_name/) dari node saat ini tanpa prefiks namespace apa pun. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Ketika di-override dalam kelas turunan, mendapatkan nama lengkap (qualified name) dari node saat ini. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Ketika di-override dalam kelas turunan, mendapatkan URI namespace dari node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Ketika di-override dalam kelas turunan, mendapatkan [XmlNameTable](../../system.xml/xmlnametable/) dari [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Mengembalikan sebuah [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) yang digunakan untuk perbandingan kesetaraan objek [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Ketika di-override dalam kelas turunan, mendapatkan XPathNodeType dari node saat ini. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Mengembalikan markup yang merepresentasikan tag pembuka dan penutup dari node saat ini serta node anaknya. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Ketika di-override dalam kelas turunan, mendapatkan prefiks namespace yang terkait dengan node saat ini. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Mengembalikan informasi skema yang telah diberikan ke node saat ini sebagai hasil validasi skema. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Mengembalikan node saat ini sebagai objek boxing dengan tipe yang paling sesuai. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Digunakan oleh implementasi [XPathNavigator](./) yang menyediakan tampilan XML "virtualized" di atas penyimpanan, untuk memberikan akses ke objek-objek yang mendasarinya. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Ketika di-override dalam kelas turunan, mendapatkan nilai **string** dari item. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Mengembalikan nilai node saat ini sebagai [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Mengembalikan nilai node saat ini sebagai [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Mengembalikan nilai node saat ini sebagai [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Mengembalikan nilai node saat ini sebagai [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Mengembalikan nilai node saat ini sebagai [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Mengembalikan tipe dari node saat ini. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Mengembalikan ruang lingkup **xml:lang** untuk node saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Mengembalikan informasi XmlSchemaType untuk node saat ini. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Mengembalikan nilai atribut dengan nama lokal dan URI namespace yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Mengembalikan nilai node namespace yang sesuai dengan nama lokal yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Mengembalikan namespace yang dalam lingkup saat ini dari node saat ini. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Mengembalikan sebuah objek [XmlWriter](../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru setelah node yang dipilih saat ini. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Membuat node saudara baru setelah node yang dipilih saat ini menggunakan string XML yang ditentukan. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Membuat node saudara baru setelah node yang dipilih saat ini menggunakan konten XML dari objek [XmlReader](../../system.xml/xmlreader/) yang ditentukan. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Membuat node saudara baru setelah node yang dipilih saat ini menggunakan node-node dalam objek [XPathNavigator](./) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Mengembalikan sebuah objek [XmlWriter](../../system.xml/xmlwriter/) yang digunakan untuk membuat node saudara baru sebelum node yang dipilih saat ini. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Membuat node saudara baru sebelum node yang dipilih saat ini menggunakan string XML yang ditentukan. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Membuat node saudara baru sebelum node yang dipilih saat ini menggunakan konten XML dari objek [XmlReader](../../system.xml/xmlreader/) yang ditentukan. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Membuat node saudara baru sebelum node yang dipilih saat ini menggunakan node-node dalam [XPathNavigator](./) yang ditentukan. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat elemen saudara baru setelah node saat ini menggunakan prefiks namespace, nama lokal, dan URI namespace yang ditentukan, dengan nilai yang ditentukan. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat elemen saudara baru sebelum node saat ini menggunakan prefiks namespace, nama lokal, dan URI namespace yang ditentukan, dengan nilai yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Menentukan apakah [XPathNavigator](./) yang ditentukan adalah keturunan dari [XPathNavigator](./) saat ini. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ketika di-override dalam kelas turunan, menentukan apakah [XPathNavigator](./) saat ini berada pada posisi yang sama dengan [XPathNavigator](./) yang ditentukan. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Mengembalikan URI namespace untuk prefiks yang ditentukan. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Mengembalikan prefiks yang dideklarasikan untuk URI namespace yang ditentukan. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Menentukan apakah node saat ini cocok dengan [XPathExpression](../xpathexpression/) yang ditentukan. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Menentukan apakah node saat ini cocok dengan ekspresi [XPath](../) yang ditentukan. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan cloning tipe kustom. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Ketika di-override dalam kelas turunan, memindahkan [XPathNavigator](./) ke posisi yang sama dengan [XPathNavigator](./) yang ditentukan. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Memindahkan [XPathNavigator](./) ke atribut dengan nama lokal dan URI namespace yang cocok. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Memindahkan [XPathNavigator](./) ke node anak dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Memindahkan [XPathNavigator](./) ke node anak dari XPathNodeType yang ditentukan. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Memindahkan [XPathNavigator](./) ke node saudara pertama dari node saat ini. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Ketika di-override dalam kelas turunan, memindahkan [XPathNavigator](./) ke atribut pertama dari node saat ini. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Ketika di-override dalam kelas turunan, memindahkan [XPathNavigator](./) ke node anak pertama dari node saat ini. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Ketika di-override dalam kelas turunan, memindahkan [XPathNavigator](./) ke node namespace pertama yang cocok dengan XPathNamespaceScope yang ditentukan. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Memindahkan [XPathNavigator](./) ke node namespace pertama dari node saat ini. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Memindahkan [XPathNavigator](./) ke elemen dengan nama lokal dan URI namespace yang ditentukan dalam urutan dokumen. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Memindahkan [XPathNavigator](./) ke elemen dengan nama lokal dan URI namespace yang ditentukan, ke batas yang ditentukan, dalam urutan dokumen. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Memindahkan [XPathNavigator](./) ke elemen berikutnya dengan XPathNodeType yang ditentukan dalam urutan dokumen. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Memindahkan [XPathNavigator](./) ke elemen berikutnya dengan XPathNodeType yang ditentukan, ke batas yang ditentukan, dalam urutan dokumen. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Ketika ditimpa dalam kelas turunan, memindahkan ke node yang memiliki atribut berjenis **ID** yang nilainya cocok dengan [String](../../system/string/) yang ditentukan. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Memindahkan [XPathNavigator](./) ke node namespace dengan prefiks namespace yang ditentukan. |
| virtual **bool** [MoveToNext](./movetonext/)() | Ketika ditimpa dalam kelas turunan, memindahkan [XPathNavigator](./) ke node saudara berikutnya dari node saat ini. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Memindahkan [XPathNavigator](./) ke node saudara berikutnya dengan nama lokal dan URI namespace yang ditentukan. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Memindahkan [XPathNavigator](./) ke node saudara berikutnya dari node saat ini yang cocok dengan XPathNodeType yang ditentukan. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Ketika ditimpa dalam kelas turunan, memindahkan [XPathNavigator](./) ke atribut berikutnya. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Ketika ditimpa dalam kelas turunan, memindahkan [XPathNavigator](./) ke node namespace berikutnya yang cocok dengan XPathNamespaceScope yang ditentukan. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Memindahkan [XPathNavigator](./) ke node namespace berikutnya. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Ketika ditimpa dalam kelas turunan, memindahkan [XPathNavigator](./) ke node induk dari node saat ini. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Ketika ditimpa dalam kelas turunan, memindahkan [XPathNavigator](./) ke node saudara sebelumnya dari node saat ini. |
| virtual void [MoveToRoot](./movetoroot/)() | Memindahkan [XPathNavigator](./) ke node akar yang menjadi milik node saat ini. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk penyalinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk penyalinan pada subclass. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Mengembalikan objek [XmlWriter](../../system.xml/xmlwriter/) yang digunakan untuk membuat node anak baru di awal daftar node anak dari node saat ini. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan string XML yang ditentukan. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan konten XML dari objek [XmlReader](../../system.xml/xmlreader/) yang ditentukan. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Membuat node anak baru di awal daftar node anak dari node saat ini menggunakan node dalam objek [XPathNavigator](./) yang ditentukan. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Membuat elemen anak baru di awal daftar node anak dari node saat ini menggunakan prefiks namespace, nama lokal, dan URI namespace yang ditentukan dengan nilai yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Mengembalikan objek [XmlReader](../../system.xml/xmlreader/) yang berisi node saat ini dan node anaknya. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama dengan nilai yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mengganti rentang node saudara dari node saat ini hingga node yang ditentukan. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Mengganti node saat ini dengan konten string yang ditentukan. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Mengganti node saat ini dengan konten objek [XmlReader](../../system.xml/xmlreader/) yang ditentukan. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mengganti node saat ini dengan konten objek [XPathNavigator](./) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Memilih sekumpulan node, menggunakan ekspresi [XPath](../) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Memilih sekumpulan node menggunakan ekspresi [XPath](../) yang ditentukan dengan objek [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Memilih sekumpulan node menggunakan [XPathExpression](../xpathexpression/) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Memilih semua node leluhur dari node saat ini yang memiliki XPathNodeType yang cocok. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Memilih semua node leluhur dari node saat ini yang memiliki nama lokal dan URI namespace yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Memilih semua node anak dari node saat ini yang memiliki XPathNodeType yang cocok. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Memilih semua node anak dari node saat ini yang memiliki nama lokal dan URI namespace yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Memilih semua node keturunan dari node saat ini yang memiliki XPathNodeType yang cocok. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Memilih semua node keturunan dari node saat ini dengan nama lokal dan URI namespace yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Memilih satu node dalam [XPathNavigator](./) menggunakan query [XPath](../) yang ditentukan. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Memilih satu node dalam objek [XPathNavigator](./) menggunakan query [XPath](../) yang ditentukan dengan objek [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Memilih satu node dalam [XPathNavigator](./) menggunakan objek [XPathExpression](../xpathexpression/) yang ditentukan. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Menetapkan markup yang merepresentasikan node anak dari node saat ini. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Menetapkan markup yang merepresentasikan tag pembuka dan penutup dari node saat ini dan node anaknya. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Menetapkan nilai bertipe dari node saat ini. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Menetapkan nilai node saat ini. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Jangan dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Jangan dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Mengembalikan nilai teks dari node saat ini. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan C# lock() untuk membuka kunci. Panggil langsung atau gunakan objek [LockContext](../../system/lockcontext/) sentry. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Mengembalikan nilai node saat ini sebagai Tipe yang ditentukan, menggunakan objek [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Mengembalikan nilai item sebagai tipe yang ditentukan. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Jangan dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Jangan dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Menyebarkan node saat ini dan node anaknya ke objek [XmlWriter](../../system.xml/xmlwriter/) yang ditentukan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke sebuah instance dari kelas ini. |

## Lihat Juga

* Kelas [XPathItem](../xpathitem/)
* Kelas [IXPathNavigable](../ixpathnavigable/)
* Kelas [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Ruang Nama [System::Xml::XPath](../)
* Perpustakaan [Aspose.Slides](../../)