---
title: GetCharCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet tecken som behövs för att avkoda en bytebuffer.
type: docs
weight: 79
url: /sv/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffer.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | Segmentets början. |
| count | int | Segmentets storlek. |

### Returvärde

Antal tecken.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffer.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte att avkoda. |
| count | int | Antal byte. |

### Returvärde

Antal tecken.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |
| index | int | Segmentets början. |
| count | int | Segmentets storlek. |

### Returvärde

Antal tecken.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte att avkoda. |

### Returvärde

Antal teck

## UTF7Encoding::GetCharCount(const uint8_t *, int) metod

Hämtar antalet tecken som behövs för att avkoda en bytebuffer.

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
* Klass [UTF7Encoding](../)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)