---
title: GetByteCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaal het aantal tekens dat nodig is om een tekenbuffer te coderen.
type: docs
weight: 235
url: /nl/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method

Bepaalt het aantal tekens dat nodig is om een tekenbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekenbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method

Bepaalt het aantal tekens dat nodig is om een tekenbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tekenbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Bepaalt het aantal tekens dat nodig is om een tekenbuffer te coderen.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tekenbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## Encoding::GetByteCount(const String\&) method

Bepaalt het aantal tekens dat nodig is om een tekenreeks te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) om te coderen. |

### Retourwaarde

Vereiste buffergrootte.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) method

Bepaalt het aantal tekens dat nodig is om een tekenbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekenbuffer. |

### Retourwaarde

Vereiste buffergrootte.

## Encoding::GetByteCount(const char_t *, int) method

Bepaalt het aantal tekens dat nodig is om een tekenbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const char_t * | Tekenbuffer. |
| count | int | [Buffer](../../../system/buffer/) grootte. |

### Retourwaarde

Vereiste buffergrootte.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Encoding](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)