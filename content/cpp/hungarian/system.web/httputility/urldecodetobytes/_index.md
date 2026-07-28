---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API referencia
description: Dekódolja az URI részletet bájt tömbből.
type: docs
weight: 14
url: /hu/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) metódus


Dekódolja az URI részletet bájt tömbből.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolt URI részlet. |

### Visszatérési érték

Dekódolt URI részlet.

## HttpUtility::UrlDecodeToBytes(const String\&) metódus


Dekódolja az URI részletet bájt karakterláncból.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kódolt URI részlet. |

### Visszatérési érték

Dekódolt URI részlet.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) metódus


Dekódolja az URI részletet karakterláncból.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Kódolt URI részlet. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Használandó kódolás. |

### Visszatérési érték

Dekódolt URI részlet.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Dekódolja az URI részletet bájt tömbből.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolt URI részlet. |
| offset | **int32_t** | Az adott bájt tömb offsetje. |
| count | **int32_t** | A beolvasandó bájtok száma. |

### Visszatérési érték

Dekódolt URI részlet.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [HttpUtility](../)
* Osztály [String](../../../system/string/)
* Osztály [Encoding](../../../system.text/encoding/)
* Névterület [System::Web](../../)
* Library [Aspose.Slides](../../../)