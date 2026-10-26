---
title: UrlEncodeToBytes()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Koduje fragment URI.
type: docs
weight: 66
url: /pl/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) metoda

Koduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI do zakodowania. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metoda

Koduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Fragment URI do zakodowania. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metoda

Koduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI do zakodowania. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Koduje fragment URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Fragment URI do zakodowania. |
| offset | **int32_t** | Offset w podanej tablicy bajtów. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Zakodowany fragment URI.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [HttpUtility](../)
* Klasa [Encoding](../../../system.text/encoding/)
* Przestrzeń nazw [System::Web](../../)
* Biblioteka [Aspose.Slides](../../../)