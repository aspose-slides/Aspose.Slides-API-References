---
title: UrlDecode()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendekode fragmen URI dari string.
type: docs
weight: 1
url: /id/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metode


Mendekode fragmen URI dari string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmen URI yang dienkode. |

### Nilai Kembali

Fragmen URI yang didekode.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metode


Mendekode fragmen URI dari string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmen URI yang dienkode. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Encoding yang akan digunakan. |

### Nilai Kembali

Fragmen URI yang didekode.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metode


Mendekode fragmen URI dari array byte.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang dienkode. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding yang akan digunakan. |

### Nilai Kembali

Fragmen URI yang didekode.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metode


Mendekode fragmen URI dari array byte.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang dienkode. |
| offset | **int32_t** | Offset dalam array byte yang diberikan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding yang akan digunakan. |

### Nilai Kembali

Fragmen URI yang didekode.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)