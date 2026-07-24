---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API Referansı
description: URI parçacığını kodlar.
type: docs
weight: 66
url: /tr/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) yöntemi

URI parçacığını kodlar.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodlanacak URI parçacığı. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) yöntemi

URI parçacığını kodlar.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodlanacak URI parçacığı. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) yöntemi

URI parçacığını kodlar.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanacak URI parçacığı. |

### Dönüş Değeri

Kodlanmış URI parçacığı.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntemi

URI parçacığını kodlar.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [HttpUtility](../)
* Sınıf [Encoding](../../../system.text/encoding/)
* AdAlanı [System::Web](../../)
* Library [Aspose.Slides](../../../)