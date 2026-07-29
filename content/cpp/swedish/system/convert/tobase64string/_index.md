---
title: ToBase64String()
second_title: Aspose.Slides för C++ API-referens
description: Base-64 kodar element i den angivna byte-arrayen och returnerar den kodade datan som en sträng.
type: docs
weight: 40
url: /sv/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) metod

Base-64 kodar element i den angivna byte-arrayen och returnerar den kodade data som en sträng.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Byte-arrayen som ska kodas |
| insert_line_breaks | **bool** | Anger om radbrytningstecken ska infogas i utdatatexten efter varje 76 base-64-tecken |

### Returvärde

Strängen som innehåller den base-64-kodade representationen av inmatnings-arrayen

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) metod

Base-64 kodar ett intervall av element i den angivna byte-arrayen och returnerar den kodade data som en sträng.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Byte-arrayen som innehåller intervallet av element som ska kodas |
| offset_in | int | Ett index för ett element i inmatnings-arrayen där intervallet som ska kodas börjar |
| length | int | Längden på intervallet av element som ska kodas |
| insert_line_breaks | **bool** | Anger om radbrytningstecken ska infogas i utdatatexten efter varje 76 base-64-tecken |

### Returvärde

Strängen som innehåller den base-64-kodade representationen av intervallet av element i inmatnings-arrayen

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) metod

Base-64 kodar element i den angivna byte-arrayen och returnerar den kodade data som en sträng.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Byte-arrayen som ska kodas |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Anger formateringsalternativ för base-64-kodad data |

### Returvärde

Strängen som innehåller den base-64-kodade representationen av inmatnings-arrayen

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) metod

Base-64 kodar ett intervall av element i den angivna byte-arrayen och returnerar den kodade data som en sträng.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Byte-arrayen som innehåller intervallet av element som ska kodas |
| offset_in | int | Ett index för ett element i inmatnings-arrayen där intervallet som ska kodas börjar |
| length | int | Längden på intervallet av element som ska kodas |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Anger formateringsalternativ för base-64-kodad data |

### Returvärde

Strängen som innehåller den base-64-kodade representationen av intervallet av element i inmatnings-arrayen

## Se också

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../../string/)
* Struktur [Convert](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)