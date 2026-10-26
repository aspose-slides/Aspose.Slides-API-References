---
title: UrlDecode()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizeden URI bölümünü çözer.
type: docs
weight: 1
url: /tr/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metod


Bir dizeden URI bölümünü çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodlanmış URI bölümü. |

### Dönüş Değeri

Çözülmüş URI bölümü.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metod


Bir dizeden URI bölümünü çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodlanmış URI bölümü. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Kullanılacak kodlama. |

### Dönüş Değeri

Çözülmüş URI bölümü.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metod


Bayt dizisinden URI bölümünü çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanmış URI bölümü. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama. |

### Dönüş Değeri

Çözülmüş URI bölümü.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metod


Bayt dizisinden URI bölümünü çözer.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanmış URI bölümü. |
| offset | **int32_t** | Verilen bayt dizisindeki ofset. |
| count | **int32_t** | Okunacak bayt sayısı. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama. |

### Dönüş Değeri

Çözülmüş URI bölümü.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [HttpUtility](../)
* Sınıf [Encoding](../../../system.text/encoding/)
* Ad Alanı [System::Web](../../)
* Library [Aspose.Slides](../../../)