---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance XmlReader baru dengan URI yang ditentukan.
type: docs
weight: 1015
url: /id/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan URI yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI untuk file yang berisi data XML. Kelas [XmlUrlResolver](../../xmlurlresolver/) digunakan untuk mengonversi jalur ke representasi data kanonik. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan URI dan pengaturan yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI untuk file yang berisi data XML. Objek [XmlResolver](../../xmlresolver/) pada objek [XmlReaderSettings](../../xmlreadersettings/) digunakan untuk mengonversi jalur ke representasi data kanonik. Jika nilai XmlReaderSettings::get_XmlResolver **nullptr**, sebuah objek [XmlUrlResolver](../../xmlurlresolver/) baru digunakan. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan URI, pengaturan, dan informasi konteks untuk parsing yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI untuk file yang berisi data XML. Objek [XmlResolver](../../xmlresolver/) pada objek [XmlReaderSettings](../../xmlreadersettings/) digunakan untuk mengonversi jalur ke representasi data kanonik. Jika nilai XmlReaderSettings::get_XmlResolver **nullptr**, sebuah objek [XmlUrlResolver](../../xmlurlresolver/) baru digunakan. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informasi konteks yang diperlukan untuk mem-parsing fragmen XML. Informasi konteks dapat mencakup [XmlNameTable](../../xmlnametable/) yang akan digunakan, enkoding, ruang nama, ruang lingkup **xml:lang** dan **xml:space**, URI dasar, dan definisi tipe dokumen. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) metode

Membuat sebuah instance [XmlReader](../) baru menggunakan aliran yang ditentukan dengan pengaturan default.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML. [XmlReader](../) memindai byte pertama aliran untuk mencari tanda urutan byte atau tanda lain dari enkoding. Setelah enkoding ditentukan, enkoding tersebut digunakan untuk melanjutkan pembacaan aliran, dan pemrosesan melanjutkan parsing masukan sebagai aliran karakter (Unicode). |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan aliran dan pengaturan yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML. [XmlReader](../) memindai byte pertama aliran untuk mencari tanda urutan byte atau tanda lain dari enkoding. Setelah enkoding ditentukan, enkoding tersebut digunakan untuk melanjutkan pembacaan aliran, dan pemrosesan melanjutkan parsing masukan sebagai aliran karakter (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metode

Membuat sebuah instance [XmlReader](../) baru menggunakan aliran, URI dasar, dan pengaturan yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML. [XmlReader](../) memindai byte pertama aliran untuk mencari tanda urutan byte atau tanda lain dari enkoding. Setelah enkoding ditentukan, enkoding tersebut digunakan untuk melanjutkan pembacaan aliran, dan pemrosesan melanjutkan parsing masukan sebagai aliran karakter (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | URI dasar untuk entitas atau dokumen yang sedang dibaca. Nilai ini dapat **nullptr**. **[Security](../../../system.security/) Catatan** URI dasar digunakan untuk menyelesaikan URI relatif dokumen XML. Jangan gunakan URI dasar dari sumber yang tidak tepercaya. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metode

Membuat sebuah instance [XmlReader](../) baru menggunakan aliran, pengaturan, dan informasi konteks untuk parsing yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML. [XmlReader](../) memindai byte pertama aliran untuk mencari tanda urutan byte atau tanda lain dari enkoding. Setelah enkoding ditentukan, enkoding tersebut digunakan untuk melanjutkan pembacaan aliran, dan pemrosesan melanjutkan parsing masukan sebagai aliran karakter (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informasi konteks yang diperlukan untuk mem-parsing fragmen XML. Informasi konteks dapat mencakup [XmlNameTable](../../xmlnametable/) yang akan digunakan, enkoding, ruang nama, ruang lingkup **xml:lang** dan **xml:space**, URI dasar, dan definisi tipe dokumen. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan pembaca teks yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Pembaca teks dari mana data XML dibaca. Pembaca teks mengembalikan aliran karakter Unicode, sehingga enkoding yang ditentukan dalam deklarasi XML tidak digunakan oleh pembaca XML untuk mendekode aliran data. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan pembaca teks dan pengaturan yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Pembaca teks dari mana data XML dibaca. Pembaca teks mengembalikan aliran karakter Unicode, sehingga enkoding yang ditentukan dalam deklarasi XML tidak digunakan oleh pembaca XML untuk mendekode aliran data. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Pengaturan untuk [XmlReader](../) baru. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan pembaca teks, pengaturan, dan URI dasar yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Pembaca teks dari mana data XML dibaca. Pembaca teks mengembalikan aliran karakter Unicode, sehingga enkoding yang ditentukan dalam deklarasi XML tidak digunakan oleh [XmlReader](../) untuk mendekode aliran data. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | URI dasar untuk entitas atau dokumen yang sedang dibaca. Nilai ini dapat **nullptr**. **[Security](../../../system.security/) Catatan** URI dasar digunakan untuk menyelesaikan URI relatif dokumen XML. Jangan gunakan URI dasar dari sumber yang tidak tepercaya. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan pembaca teks, pengaturan, dan informasi konteks untuk parsing yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Pembaca teks dari mana data XML dibaca. Pembaca teks mengembalikan aliran karakter Unicode, sehingga enkoding yang ditentukan dalam deklarasi XML tidak digunakan oleh pembaca XML untuk mendekode aliran data. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Nilai ini dapat **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Informasi konteks yang diperlukan untuk mem-parsing fragmen XML. Informasi konteks dapat mencakup [XmlNameTable](../../xmlnametable/) yang akan digunakan, enkoding, ruang nama, ruang lingkup **xml:lang** dan **xml:space**, URI dasar, dan definisi tipe dokumen. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Sebuah objek yang digunakan untuk membaca data XML dalam aliran.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) metode

Membuat sebuah instance [XmlReader](../) baru dengan menggunakan pembaca XML dan pengaturan yang ditentukan.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Objek yang ingin Anda gunakan sebagai pembaca XML dasar. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Pengaturan untuk instance [XmlReader](../) baru. Tingkat kepatuhan objek [XmlReaderSettings](../../xmlreadersettings/) harus sama dengan tingkat kepatuhan pembaca dasar, atau harus disetel ke [ConformanceLevel::Auto](../../conformancelevel/). |

### Nilai Kembalian

Sebuah objek yang dibungkus di sekitar objek [XmlReader](../) yang ditentukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlReader](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlReaderSettings](../../xmlreadersettings/)
* Kelas [XmlParserContext](../../xmlparsercontext/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)