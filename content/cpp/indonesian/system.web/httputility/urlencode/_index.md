---
title: UrlEncode()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyandikan fragmen URI.
type: docs
weight: 53
url: /id/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metode

Menyandikan fragmen URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmen URI yang akan disandikan. |

### Nilai Kembali

Fragmen URI yang disandikan.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metode

Menyandikan fragmen URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) | Fragmen URI yang akan disandikan. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding yang akan digunakan. |

### Nilai Kembali

Fragmen URI yang disandikan.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metode

Menyandikan fragmen URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang akan disandikan. |

### Nilai Kembali

Fragmen URI yang disandikan.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Menyandikan fragmen URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragmen URI yang akan disandikan. |
| offset | **int32_t** | Offset dalam array byte yang diberikan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembali

Fragmen URI yang disandikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [HttpUtility](../)
* Kelas [Encoding](../../../system.text/encoding/)
* Ruang nama [System::Web](../../)
* Library [Aspose.Slides](../../../)