---
title: GetByte()
second_title: Aspose.Slides pro C++ API referenci
description: Interpretovat zadané typované pole jako surové pole bajtů a získat hodnotu bajtu na určeném offsetu bajtu.
type: docs
weight: 27
url: /cs/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) metoda


Interpretovat zadané typované pole jako surové pole bajtů a získat hodnotu bajtu na určeném offsetu bajtu.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Cílové pole |
| index | int | Nulový offset bajtu, který se má získat |

### Návratová hodnota

Hodnota bajtu na určeném indexu

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) metoda


Interpretovat zadané typované pole jako surové pole bajtů a získat hodnotu bajtu na určeném offsetu bajtu.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pohledu na pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Cílový pohled na pole |
| index | int | Nulový offset bajtu, který se má získat |

### Návratová hodnota

Hodnota bajtu na určeném indexu

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) metoda


Interpretovat zadané typované pole jako surové pole bajtů a získat hodnotu bajtu na určeném offsetu bajtu.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků zásobníkového pole |
| N | Velikost zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Cílové zásobníkové pole |
| index | int | Nulový offset bajtu, který se má získat |

### Návratová hodnota

Hodnota bajtu na určeném indexu

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)