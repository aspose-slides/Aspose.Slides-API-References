---
title: UrlDecodeToBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendekode fragmen URI dari array byte.
type: docs
weight: 14
url: /id/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metode

Mendekode fragmen URI dari array byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang telah dienkode. |

### Nilai Kembalian

Fragmen URI yang telah didekode.

## HttpUtility::UrlDecodeToBytes(const String\&) metode

Mendekode fragmen URI dari string byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmen URI yang telah dienkode. |

### Nilai Kembalian

Fragmen URI yang telah didekode.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metode

Mendekode fragmen URI dari string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragmen URI yang telah dienkode. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Pengkodean yang akan digunakan. |

### Nilai Kembalian

Fragmen URI yang telah didekode.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Mendekode fragmen URI dari array byte.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang telah dienkode. |
| offset | **int32_t** | Offset dalam array byte yang diberikan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembalian

Fragmen URI yang telah didekode.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [HttpUtility](../)
* Kelas [String](../../../system/string/)
* Kelas [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Perpustakaan [Aspose.Slides](../../../)