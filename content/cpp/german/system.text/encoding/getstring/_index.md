---
title: GetString()
second_title: Aspose.Slides für C++ API Referenz
description: Dekodiert einen Puffer von Bytes in einen String.
type: docs
weight: 313
url: /de/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |
| byte_count | int | Größe des Eingabepuffers. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(ArrayPtr\<uint8_t\>) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |
| index | int | Offset im Eingabepuffer. |
| count | int | Größe des Eingabepuffers. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |
| index | int | Offset im Eingabepuffer. |
| count | int | Größe des Eingabepuffers. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) Methode

Dekodiert einen Puffer von Bytes in einen String.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) zum Lesen von Bytes. |
| index | int | Offset im Eingabepuffer. |
| count | int | Größe des Eingabepuffers. |

### Rückgabewert

[String](../../../system/string/) der dekodierten Zeichen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Encoding](../)
* Klasse [ReadOnlySpan](../../../system/readonlyspan/)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)