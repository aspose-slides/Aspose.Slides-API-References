---
title: BlockCopy()
second_title: Odwołanie API Aspose.Slides dla C++
description: Kopiuje określoną liczbę bajtów z bufora źródłowego do bufora docelowego.
type: docs
weight: 1
url: /pl/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metoda


Kopiuje określoną liczbę bajtów z bufora źródłowego do bufora docelowego.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const **uint8_t** * | Wskaźnik do bufora źródłowego |
| srcOffset | int | Przesunięcie w bajtach w buforze źródłowym, od którego rozpoczyna się kopiowanie |
| dst | **uint8_t** * | Wskaźnik do bufora docelowego |
| dstOffset | int | Przesunięcie w bajtach w buforze docelowym, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów tablicy źródłowej |
| TDst | Typ elementów tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metoda


Interpretuj dwa określone tablice jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów widoku tablicy źródłowej |
| TDst | Typ elementów widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Widok tablicy źródłowej |
| srcOffset | int | Przesunięcie w bajtach w widoku tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const System::Details::ArrayView\<TDst\>\& | Widok tablicy docelowej |
| dstOffset | int | Przesunięcie w bajtach w widoku tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów tablicy źródłowej |
| TDst | Typ elementów widoku tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const System::Details::ArrayView\<TDst\>\& | Widok tablicy docelowej |
| dstOffset | int | Przesunięcie w bajtach w widoku tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów widoku tablicy źródłowej |
| TDst | Typ elementów tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Widok tablicy źródłowej |
| srcOffset | int | Przesunięcie w bajtach w widoku tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów stosowanej tablicy źródłowej |
| NS | Rozmiar stosowanej tablicy źródłowej |
| TDst | Typ elementów stosowanej tablicy docelowej |
| ND | Rozmiar stosowanej tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Stosowana tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w stosowanej tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Stosowana tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w stosowanej tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów tablicy źródłowej |
| TDst | Typ elementów stosowanej tablicy docelowej |
| ND | Rozmiar stosowanej tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Stosowana tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w stosowanej tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metoda


Interpretuj dwa określone tablice typowane jako surowe tablice bajtów i kopiuje dane z jednej do drugiej.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TSrc | Typ elementów stosowanej tablicy źródłowej |
| NS | Rozmiar stosowanej tablicy źródłowej |
| TDst | Typ elementów tablicy docelowej |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Stosowana tablica źródłowa |
| srcOffset | int | Przesunięcie w bajtach w stosowanej tablicy źródłowej, od którego rozpoczyna się kopiowanie |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Tablica docelowa |
| dstOffset | int | Przesunięcie w bajtach w tablicy docelowej, od którego rozpocząć wstawianie danych |
| count | int | Liczba bajtów do skopiowania |

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Buffer](../)
* Klasa [Array](../../array/)
* Klasa [ArrayBase](../../arraybase/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)