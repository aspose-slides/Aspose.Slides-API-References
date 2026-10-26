---
title: XmlReaderSettings
second_title: Referensi API Aspose.Slides untuk C++
description: "Menentukan serangkaian fitur yang didukung pada objek XmlReader yang dibuat oleh metode XmlReader::Create."
type: docs
weight: 443
url: /id/system.xml/xmlreadersettings/
---
## XmlReaderSettings kelas

Menentukan serangkaian fitur untuk didukung pada objek [XmlReader](../xmlreader/) yang dibuat oleh metode [XmlReader::Create](../xmlreader/create/).

```cpp
class XmlReaderSettings : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Membuat salinan dari instance [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Menirukan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Menirukan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Mengembalikan nilai yang menunjukkan apakah akan melakukan pemeriksaan karakter. |
| **bool** [get_CloseInput](./get_closeinput/)() | Mengembalikan nilai yang menunjukkan apakah aliran dasar atau TextReader harus ditutup ketika pembaca ditutup. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Mengembalikan tingkat kepatuhan yang akan dipatuhi oleh [XmlReader](../xmlreader/). |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Mengembalikan nilai yang menentukan pemrosesan DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Mengembalikan nilai yang menunjukkan apakah mengabaikan komentar. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Mengembalikan nilai yang menunjukkan apakah mengabaikan instruksi pemrosesan. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Mengembalikan nilai yang menunjukkan apakah mengabaikan spasi putih yang tidak signifikan. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Mengembalikan offset nomor baris dari objek [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Mengembalikan offset posisi baris dari objek [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Mengembalikan nilai yang menunjukkan jumlah maksimum karakter yang diizinkan dalam dokumen yang dihasilkan dari perluasan entitas. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Mengembalikan nilai yang menunjukkan jumlah maksimum karakter yang diizinkan dalam dokumen XML. Nilai nol (0) berarti tidak ada batasan pada ukuran dokumen XML. Nilai bukan nol menentukan ukuran maksimum, dalam karakter. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Mengembalikan [XmlNameTable](../xmlnametable/) yang digunakan untuk perbandingan string atomik. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Mengembalikan nilai yang menunjukkan apakah melarang pemrosesan definisi tipe dokumen (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Mengembalikan XmlSchemaSet yang digunakan saat melakukan validasi skema. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Mengembalikan nilai yang menunjukkan pengaturan validasi skema. Pengaturan ini berlaku untuk objek [XmlReader](../xmlreader/) yang memvalidasi skema (nilai [XmlReaderSettings::get_ValidationType](./get_validationtype/) adalah [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Mengembalikan nilai yang menunjukkan apakah [XmlReader](../xmlreader/) akan melakukan validasi atau penugasan tipe saat membaca. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [Reset](./reset/)() | Mengatur ulang anggota kelas pengaturan ke nilai default. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Menetapkan nilai yang menunjukkan apakah melakukan pemeriksaan karakter. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Menetapkan nilai yang menunjukkan apakah aliran dasar atau TextReader harus ditutup ketika pembaca ditutup. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Menetapkan tingkat kepatuhan yang akan dipatuhi oleh [XmlReader](../xmlreader/). |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Menetapkan nilai yang menentukan pemrosesan DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Menetapkan nilai yang menunjukkan apakah mengabaikan komentar. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Menetapkan nilai yang menunjukkan apakah mengabaikan instruksi pemrosesan. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Menetapkan nilai yang menunjukkan apakah mengabaikan spasi putih yang tidak signifikan. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Menetapkan offset nomor baris dari objek [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Menetapkan offset posisi baris dari objek [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Menetapkan nilai yang menunjukkan jumlah maksimum karakter yang diizinkan dalam dokumen yang dihasilkan dari perluasan entitas. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Menetapkan nilai yang menunjukkan jumlah maksimum karakter yang diizinkan dalam dokumen XML. Nilai nol (0) berarti tidak ada batasan pada ukuran dokumen XML. Nilai bukan nol menentukan ukuran maksimum, dalam karakter. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Menetapkan [XmlNameTable](../xmlnametable/) yang digunakan untuk perbandingan string atomik. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Menetapkan nilai yang menunjukkan apakah melarang pemrosesan definisi tipe dokumen (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Menetapkan XmlSchemaSet yang digunakan saat melakukan validasi skema. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Menetapkan nilai yang menunjukkan pengaturan validasi skema. Pengaturan ini berlaku untuk objek [XmlReader](../xmlreader/) yang memvalidasi skema (nilai [XmlReaderSettings::get_ValidationType](./get_validationtype/) adalah [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Menetapkan nilai yang menunjukkan apakah [XmlReader](../xmlreader/) akan melakukan validasi atau penugasan tipe saat membaca. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Menetapkan [XmlResolver](../xmlresolver/) yang digunakan untuk mengakses dokumen eksternal. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai terkini penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Menambahkan penangan peristiwa yang terjadi ketika pembaca menemukan kesalahan validasi. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Menghapus penangan peristiwa yang terjadi ketika pembaca menemukan kesalahan validasi. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Menginisialisasi instance baru dari kelas [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Alias Tipe

| Alias | Deskripsi |
| --- | --- |
| [Ptr](./ptr/) | Alias untuk shared pointer ke instance kelas ini. |

## Catatan

Objek dari kelas ini harus hanya dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance dari tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. 

## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Xml](../)
* Pustaka [Aspose.Slides](../../)