---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API Referansı
description: Bayt dizisinden URI parçacığını çözer.
type: docs
weight: 14
url: /tr/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metodu

Bayt dizisinden URI parçacığını çözer.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanmış URI parçacığı. |

### Dönüş Değeri

Çözülen URI parçacığı.

## HttpUtility::UrlDecodeToBytes(const String\&) metodu

Dize üzerinden URI parçacığını çözer.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodlanmış URI parçacığı. |

### Dönüş Değeri

Çözülen URI parçacığı.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metodu

Dizeden URI parçacığını çözer.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kodlanmış URI parçacığı. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kullanılacak kodlama. |

### Dönüş Değeri

Çözülen URI parçacığı.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu

Bayt dizisinden URI parçacığını çözer.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kodlanmış URI parçacığı. |
| offset | **int32_t** | Verilen bayt dizisindeki ofset. |
| count | **int32_t** | Okunacak bayt sayısı. |

### Dönüş Değeri

Çözülen URI parçacığı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)