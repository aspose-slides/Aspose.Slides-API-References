---
title: GetBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen.
type: docs
weight: 40
url: /de/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu kodierende Zeichen. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl geschriebener Bytes.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu kodierende Zeichen. |
| char_index | int | Beginn des Zeichenausschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Versatz im Ausgabepuffer. |

### Rückgabewert

Anzahl geschriebener Bytes.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Zu kodierende Zeichen. |
| char_index | int | Beginn des Zeichenausschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Versatz im Ausgabepuffer. |

### Rückgabewert

Anzahl geschriebener Bytes.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Zu kodierende Zeichen. |
| char_index | int | Beginn des Zeichenausschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Versatz im Ausgabepuffer. |

### Rückgabewert

Anzahl geschriebener Bytes.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zu kodieren. |
| char_index | int | Beginn des Zeichenausschnitts. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_index | int | Versatz im Ausgabepuffer. |

### Rückgabewert

Anzahl geschriebener Bytes.

## ICUEncoding::GetBytes(const String\&) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) zu kodieren. |

### Rückgabewert

[Buffer](../../../system/buffer/) das die Darstellung der zu kodierenden Zeichen enthält.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu kodierende Zeichen. |
| index | int | Beginn des Zeichenausschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) das die Darstellung der zu kodierenden Zeichen enthält.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Zu kodierende Zeichen. |
| index | int | Beginn des Zeichenausschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) das die Darstellung der zu kodierenden Zeichen enthält.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Zu kodierende Zeichen. |
| index | int | Beginn des Zeichenausschnitts. |
| count | int | Anzahl der zu konvertierenden Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) das die Darstellung der zu kodierenden Zeichen enthält.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Zu kodierende Zeichen. |

### Rückgabewert

[Buffer](../../../system/buffer/) das die Darstellung der zu kodierenden Zeichen enthält.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) Methode

Gibt die Bytes zurück, die durch das Kodieren eines Zeichenpuffers entstehen.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chars | const char_t * | Zu kodierende Zeichen. |
| char_count | int | Anzahl der zu konvertierenden Zeichen. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) zum Ablegen der Zeichen. |
| byte_count | int | Größe des Ausgabepuffers. |

### Rückgabewert

Anzahl geschriebener Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)