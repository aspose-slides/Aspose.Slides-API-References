---
title: UrlEncode()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Koduje fragment URI.
type: docs
weight: 53
url: /pl/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metoda

Koduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) | fragment URI do zakodowania. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metoda

Koduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) | fragment URI do zakodowania. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do użycia. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metoda

Koduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | fragment URI do zakodowania. |

### Wartość zwracana

Zakodowany fragment URI.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Koduje fragment URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | fragment URI do zakodowania. |
| offset | **int32_t** | Przesunięcie w podanej tablicy bajtów. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Zakodowany fragment URI.

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [HttpUtility](../)
* Klasa [Encoding](../../../system.text/encoding/)
* Przestrzeń nazw [System::Web](../../)
* Library [Aspose.Slides](../../../)