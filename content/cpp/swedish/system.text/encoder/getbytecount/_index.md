---
title: GetByteCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet byte som behövs för att koda en buffert.
type: docs
weight: 40
url: /sv/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Hämtar antalet byte som behövs för att koda en buffert.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Antal tecken att koda. |
| flush | **bool** | Om true, rensar intern encoder-tillstånd efter beräkning. |

### Return Value

Antalet byte som krävs för att koda bufferten.

## Encoder::GetByteCount(const char_t *, int, bool) method


Hämtar antalet byte som behövs för att koda en buffert.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| count | int | Antal tecken att koda. |
| flush | **bool** | Om true, rensar intern encoder-tillstånd efter beräkning. |

### Return Value

Antalet byte som krävs för att koda bufferten.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Encoder](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)