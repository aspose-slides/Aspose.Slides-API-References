---
title: ToBase64CharArray()
second_title: Aspose.Slides för C++ API-referens
description: Base-64 kodar ett intervall av element i den angivna byte-arrayen och lagrar de kodade data som en array av Unicode-tecken.
type: docs
weight: 27
url: /sv/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method


Base-64 kodar ett intervall av element i den angivna byte-arrayen och lagrar de kodade data som en array av Unicode-tecken.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Arrayen med byte som innehåller intervallet av element som ska kodas |
| offset_in | int | Ett index för ett element i inmatningsarrayen där intervallet som ska kodas börjar |
| length | int | Längden på intervallet av element som ska kodas |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | En konstant referens till utdataarrayen dit de resulterande data ska placeras |
| offset_out | int | Ett index i utdataarrayen där de resulterande data ska börja placeras |
| insert_line_breaks | **bool** | Anger om radbrytningstecken ska infogas i utdataarrayen efter var 76:e base-64-tecken |

### Returvärde

Antalet tecken som skrivits till utdataarrayen

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method


Base-64 kodar ett intervall av element i den angivna byte-arrayen och lagrar de kodade data som en array av Unicode-tecken.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Arrayen med byte som innehåller intervallet av element som ska kodas |
| offset_in | int | Ett index för ett element i inmatningsarrayen där intervallet som ska kodas börjar |
| length | int | Längden på intervallet av element som ska kodas |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | En konstant referens till utdataarrayen dit de resulterande data ska placeras |
| offset_out | int | Ett index i utdataarrayen där de resulterande data ska börja placeras |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Anger formateringsalternativ för base-64-kodade data |

### Returvärde

Antalet tecken som skrivits till utdataarrayen

## Se även

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)