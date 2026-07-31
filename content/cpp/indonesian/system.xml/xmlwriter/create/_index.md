---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance XmlWriter baru menggunakan nama file yang ditentukan.
type: docs
weight: 469
url: /id/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan nama file yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | File yang ingin Anda tulis. [XmlWriter](../) membuat file di jalur yang ditentukan dan menulis ke dalamnya dengan sintaks teks XML 1.0. **outputFileName** harus berupa jalur sistem file. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan nama file dan objek [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | File yang ingin Anda tulis. [XmlWriter](../) membuat file di jalur yang ditentukan dan menulis ke dalamnya dengan sintaks teks XML 1.0. **outputFileName** harus berupa jalur sistem file. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objek [XmlWriterSettings](../../xmlwritersettings/) yang digunakan untuk mengonfigurasi instance [XmlWriter](../) baru. Jika ini **nullptr**, sebuah [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan default akan digunakan. Jika [XmlWriter](../) digunakan dengan metode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), Anda harus menggunakan nilai XslCompiledTransform::get_OutputSettings untuk memperoleh objek [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan yang tepat. Ini memastikan bahwa objek [XmlWriter](../) yang dibuat memiliki pengaturan output yang benar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan stream yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda tulis ke. [XmlWriter](../) menulis sintaks teks XML 1.0 dan menambahkannya ke stream yang ditentukan. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan stream dan objek [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda tulis ke. [XmlWriter](../) menulis sintaks teks XML 1.0 dan menambahkannya ke stream yang ditentukan. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objek [XmlWriterSettings](../../xmlwritersettings/) yang digunakan untuk mengonfigurasi instance [XmlWriter](../) baru. Jika ini **nullptr**, sebuah [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan default akan digunakan. Jika [XmlWriter](../) digunakan dengan metode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), Anda harus menggunakan nilai XslCompiledTransform::get_OutputSettings untuk memperoleh objek [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan yang tepat. Ini memastikan bahwa objek [XmlWriter](../) yang dibuat memiliki pengaturan output yang benar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan TextWriter yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda tulis ke. [XmlWriter](../) menulis sintaks teks XML 1.0 dan menambahkannya ke TextWriter yang ditentukan. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan TextWriter dan objek [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda tulis ke. [XmlWriter](../) menulis sintaks teks XML 1.0 dan menambahkannya ke TextWriter yang ditentukan. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objek [XmlWriterSettings](../../xmlwritersettings/) yang digunakan untuk mengonfigurasi instance [XmlWriter](../) baru. Jika ini **nullptr**, sebuah [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan default akan digunakan. Jika [XmlWriter](../) digunakan dengan metode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), Anda harus menggunakan nilai XslCompiledTransform::get_OutputSettings untuk memperoleh objek [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan yang tepat. Ini memastikan bahwa objek [XmlWriter](../) yang dibuat memiliki pengaturan output yang benar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan [Text::StringBuilder](../../../system.text/stringbuilder/) yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) yang akan ditulisi. Konten yang ditulis oleh [XmlWriter](../) ditambahkan ke [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan [Text::StringBuilder](../../../system.text/stringbuilder/) dan objek [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) yang akan ditulisi. Konten yang ditulis oleh [XmlWriter](../) ditambahkan ke [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objek [XmlWriterSettings](../../xmlwritersettings/) yang digunakan untuk mengonfigurasi instance [XmlWriter](../) baru. Jika ini **nullptr**, sebuah [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan default akan digunakan. Jika [XmlWriter](../) digunakan dengan metode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), Anda harus menggunakan nilai XslCompiledTransform::get_OutputSettings untuk memperoleh objek [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan yang tepat. Ini memastikan bahwa objek [XmlWriter](../) yang dibuat memiliki pengaturan output yang benar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan objek [XmlWriter](../) yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Objek [XmlWriter](../) yang ingin Anda gunakan sebagai penulis dasar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../) yang dibungkus di sekitar objek [XmlWriter](../) yang ditentukan.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) metode


Membuat sebuah instance [XmlWriter](../) baru menggunakan [XmlWriter](../) dan objek [XmlWriterSettings](../../xmlwritersettings/) yang ditentukan.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Objek [XmlWriter](../) yang ingin Anda gunakan sebagai penulis dasar. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Objek [XmlWriterSettings](../../xmlwritersettings/) yang digunakan untuk mengonfigurasi instance [XmlWriter](../) baru. Jika ini **nullptr**, sebuah [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan default akan digunakan. Jika [XmlWriter](../) digunakan dengan metode XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), Anda harus menggunakan nilai XslCompiledTransform::get_OutputSettings untuk memperoleh objek [XmlWriterSettings](../../xmlwritersettings/) dengan pengaturan yang tepat. Ini memastikan bahwa objek [XmlWriter](../) yang dibuat memiliki pengaturan output yang benar. |

### Nilai Kembali

Sebuah objek [XmlWriter](../) yang dibungkus di sekitar objek [XmlWriter](../) yang ditentukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlWriter](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlWriterSettings](../../xmlwritersettings/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [TextWriter](../../../system.io/textwriter/)
* Kelas [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)