---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Dekoduje fragment URI z tablicy bajtów.
type: docs
weight: 14
url: /pl/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metoda


Dekoduje fragment URI z tablicy bajtów.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakodowany fragment URI. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecodeToBytes(const String\&) metoda


Dekoduje fragment URI z łańcucha bajtów.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Zakodowany fragment URI. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metoda


Dekoduje fragment URI z łańcucha.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Zakodowany fragment URI. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia. |

### Wartość zwracana

Zdekodowany fragment URI.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Dekoduje fragment URI z tablicy bajtów.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zakodowany fragment URI. |
| offset | **int32_t** | Przesunięcie w podanej tablicy bajtów. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Zdekodowany fragment URI.

## Zobacz również

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [HttpUtility](../)
* Klasa [String](../../../system/string/)
* Klasa [Encoding](../../../system.text/encoding/)
* Przestrzeń nazw [System::Web](../../)
* Library [Aspose.Slides](../../../)