---
title: ByteLength()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje počet bajtů zabraných všemi prvky zadaného pole.
type: docs
weight: 14
url: /cs/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


Určuje počet bajtů zabraných všemi prvky zadaného pole.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Pole |

### Návratová hodnota

Počet bajtů zabraných všemi prvky zadaného pole

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Určuje počet bajtů zabraných všemi prvky zadaného zobrazení pole.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků zobrazení pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Zobrazení pole |

### Návratová hodnota

Počet bajtů zabraných všemi prvky zadaného zobrazení pole

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Určuje počet bajtů zabraných všemi prvky zadaného zásobníkového pole.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků zásobníkového pole |
| N | Velikost zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Zásobníkové pole |

### Návratová hodnota

Počet bajtů zabraných všemi prvky zadaného zásobníkového pole

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Array](../../array/)
* Třída [Buffer](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)