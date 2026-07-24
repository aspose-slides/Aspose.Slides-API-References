---
title: GetBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.
type: docs
weight: 66
url: /de/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu codierende Zeichen. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu codierende Zeichen. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zu codieren. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu codierende Zeichen. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Zu codierende Zeichen. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Zu codierende Zeichen. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zu codieren. |
| char_index | int | Beginn des Zeichensabschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## UTF7Encoding::GetBytes(const String\&) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zu codieren. |

### Rückgabewert

[Buffer](../../../system/buffer/) die die Darstellung der zu codierenden Zeichen enthält.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu codierende Zeichen. |
| index | int | Beginn des Zeichensabschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) die die Darstellung der zu codierenden Zeichen enthält.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Zu codierende Zeichen. |
| index | int | Beginn des Zeichensabschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) die die Darstellung der zu codierenden Zeichen enthält.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Zu codierende Zeichen. |
| index | int | Beginn des Zeichensabschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) die die Darstellung der zu codierenden Zeichen enthält.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu codierende Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) die die Darstellung der zu codierenden Zeichen enthält.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) Methode

Ermittelt die Bytes, die durch die Codierung eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu codierende Zeichen. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)