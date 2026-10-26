---
title: UrlDecode()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dekoduje fragment URI z ciągu znaków.
type: docs
weight: 1
url: /pl/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metoda

Dekoduje fragment URI z ciągu znaków.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Zakodowany fragment URI. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metoda

Dekoduje fragment URI z ciągu znaków.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) | Zakodowany fragment URI. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Kodowanie do użycia. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metoda

Dekoduje fragment URI z tablicy bajtów.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakodowany fragment URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metoda

Dekoduje fragment URI z tablicy bajtów.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakodowany fragment URI. |
| offset | **int32_t** | Przesunięcie w podanej tablicy bajtów. |
| count | **int32_t** | Liczba bajtów do odczytania. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia. |

### Wartość zwracana

Zdekodowany fragment URI.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)