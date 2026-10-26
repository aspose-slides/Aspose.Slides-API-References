---
title: GetByteCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal het aantal tekens op dat nodig is om een karakterbuffer te coderen.
type: docs
weight: 157
url: /nl/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakterbuffer. |
| count | int | [Buffer](../../../system/buffer/) grootte. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakterbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakterbuffer. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(const String\&) methode


Geeft het aantal tekens dat nodig is om een tekenreeks te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) te coderen. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakterbuffer. |

### Retourwaarde

Vereiste buffergrootte.

## UTF7Encoding::GetByteCount(const char_t *, int) methode


Geeft het aantal tekens dat nodig is om een karakterbuffer te coderen.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakterbuffer. |
| count | int | [Buffer](../../../system/buffer/) grootte. |

### Retourwaarde

Vereiste buffergrootte.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [UTF7Encoding](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)