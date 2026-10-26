---
title: UrlDecode()
second_title: Aspose.Slides C++ API referencia
description: Dekódolja az URI töredéket a karakterláncból.
type: docs
weight: 1
url: /hu/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) metódus


Dekódolja az URI töredéket a karakterláncból.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kódolt URI töredék. |

### Visszatérési érték

Dekódolt URI töredék.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) metódus


Dekódolja az URI töredéket a karakterláncból.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../../../system/string/) | Kódolt URI töredék. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Használandó kódolás. |

### Visszatérési érték

Dekódolt URI töredék.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) metódus


Dekódolja az URI töredéket a bájt tömbből.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolt URI töredék. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Használandó kódolás. |

### Visszatérési érték

Dekódolt URI töredék.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) metódus


Dekódolja az URI töredéket a bájt tömbből.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Kódolt URI töredék. |
| offset | **int32_t** | Az adott bájt tömbben lévő eltolás. |
| count | **int32_t** | Olvasandó bájtok száma. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Használandó kódolás. |

### Visszatérési érték

Dekódolt URI töredék.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [HttpUtility](../)
* Osztály [Encoding](../../../system.text/encoding/)
* Névtér [System::Web](../../)
* Könyvtár [Aspose.Slides](../../../)