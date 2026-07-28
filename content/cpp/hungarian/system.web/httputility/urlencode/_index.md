---
title: UrlEncode()
second_title: Aspose.Slides C++ API Referencia
description: Kódolja az URI töredéket.
type: docs
weight: 53
url: /hu/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) metódus


Kódolja az URI töredéket.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kódolandó URI töredék. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) metódus


Kódolja az URI töredéket.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kódolandó URI töredék. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Használandó kódolás. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) metódus


Kódolja az URI töredéket.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolandó URI töredék. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Kódolja az URI töredéket.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolandó URI töredék. |
| offset | **int32_t** | Eltolás a megadott bájttömbben. |
| count | **int32_t** | Olvasandó bájtok száma. |

### Visszatérési érték

Kódolt URI töredék.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [HttpUtility](../)
* Osztály [Encoding](../../../system.text/encoding/)
* Névtér [System::Web](../../)
* Library [Aspose.Slides](../../../)