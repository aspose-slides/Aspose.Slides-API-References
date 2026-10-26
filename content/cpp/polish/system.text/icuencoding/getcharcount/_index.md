---
title: GetCharCount()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca liczbę znaków potrzebnych do zdekodowania bufora bajtów.
type: docs
weight: 53
url: /pl/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora bajtów.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Wartość zwracana

Liczba znaków.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Wartość zwracana

Liczba znaków.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### Wartość zwracana

Liczba znaków.

## ICUEncoding::GetCharCount(const uint8_t *, int) metoda

Zwraca liczbę znaków potrzebnych do zdekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Wartość zwracana

Liczba znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)