---
title: GetCharCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet tecken som behövs för att avkoda en bytebuffert.
type: docs
weight: 53
url: /sv/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffert.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| count | int | Antal byte. |

### Returvärde

Antal tecken.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | Skivans början. |
| count | int | Skivans storlek. |

### Returvärde

Antal tecken.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |

### Returvärde

Antal tecken.

## ICUEncoding::GetCharCount(const uint8_t *, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| count | int | Antal byte. |

### Returvärde

Antal tecken.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* klass [ICUEncoding](../)
* namnrymd [System::Text](../../)
* bibliotek [Aspose.Slides](../../../)