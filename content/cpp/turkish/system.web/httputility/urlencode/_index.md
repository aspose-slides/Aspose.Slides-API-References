---
title: UrlEncode()
second_title: Aspose.Slides for C++ API Referansı
description: URI parçacığını kodlar.
type: docs
weight: 53
url: /tr/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metodu

URI parçacığını kodlar.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodlanacak URI parçacığı. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metodu

URI parçacığını kodlar.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kodlanacak URI parçacığı. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metodu

URI parçacığını kodlar.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanacak URI parçacığı. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu

URI parçacığını kodlar.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanacak URI parçacığı. |
| offset | **int32_t** | Verilen bayt dizisindeki ofset. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [HttpUtility](../)
* Sınıf [Encoding](../../../system.text/encoding/)
* İsim Uzayı [System::Web](../../)
* Kütüphane [Aspose.Slides](../../../)