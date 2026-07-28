---
title: ByteLength()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa liczbę bajtów zajmowanych przez wszystkie elementy określonej tablicy.
type: docs
weight: 14
url: /pl/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) metoda


Określa liczbę bajtów zajmowanych przez wszystkie elementy określonej tablicy.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Tablica |

### Wartość zwracana

Liczba bajtów zajmowanych przez wszystkie elementy określonej tablicy

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) metoda


Określa liczbę bajtów zajmowanych przez wszystkie elementy określonego widoku tablicy.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów widoku tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Widok tablicy |

### Wartość zwracana

Liczba bajtów zajmowanych przez wszystkie elementy określonego widoku tablicy

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) metoda


Określa liczbę bajtów zajmowanych przez wszystkie elementy określonej tablicy stosu.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów tablicy stosu |
| N | Rozmiar tablicy stosu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Tablica stosu |

### Wartość zwracana

Liczba bajtów zajmowanych przez wszystkie elementy określonej tablicy stosu

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)