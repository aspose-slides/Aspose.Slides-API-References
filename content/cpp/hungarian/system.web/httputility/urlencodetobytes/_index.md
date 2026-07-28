---
title: UrlEncodeToBytes()
second_title: Aspose.Slides for C++ API-referencia
description: URI töredéket kódol.
type: docs
weight: 66
url: /hu/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) metódus

URI töredéket kódol.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kódolandó URI töredék. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metódus

URI töredéket kódol.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kódolandó URI töredék. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Használandó kódolás. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metódus

URI töredéket kódol.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolandó URI töredék. |

### Visszatérési érték

Kódolt URI töredék.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

URI töredéket kódol.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolandó URI töredék. |
| offset | **int32_t** | Eltolás a megadott bájt tömbben. |
| count | **int32_t** | Olvasandó bájtok száma. |

### Visszatérési érték

Kódolt URI töredék.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [HttpUtility](../)
* Osztály [Encoding](../../../system.text/encoding/)
* Névtér [System::Web](../../)
* Könyvtár [Aspose.Slides](../../../)