---
title: ByteLength()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt die Anzahl der Bytes, die von allen Elementen des angegebenen Arrays belegt werden.
type: docs
weight: 14
url: /de/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) Methode

Bestimmt die Anzahl der Bytes, die von allen Elementen des angegebenen Arrays belegt werden.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements of the array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Ein Array |

### Rückgabewert

Die Anzahl der Bytes, die von allen Elementen des angegebenen Arrays belegt werden

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) Methode

Bestimmt die Anzahl der Bytes, die von allen Elementen der angegebenen ArrayView belegt werden.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements of the array view |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Ein ArrayView |

### Rückgabewert

Die Anzahl der Bytes, die von allen Elementen der angegebenen ArrayView belegt werden

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) Methode

Bestimmt die Anzahl der Bytes, die von allen Elementen des angegebenen Stack-Arrays belegt werden.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Ein Stack-Array |

### Rückgabewert

Die Anzahl der Bytes, die von allen Elementen des angegebenen Stack-Arrays belegt werden

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)