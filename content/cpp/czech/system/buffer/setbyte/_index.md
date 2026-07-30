---
title: SetByte()
second_title: Aspose.Slides pro C++ API Reference
description: Interpretujte zadané typované pole jako surové pole bajtů a nastavte zadanou hodnotu bajtu na určený offset bajtu.
type: docs
weight: 40
url: /cs/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

Interpretujte zadané typované pole jako surové pole bajtů a nastavte zadanou hodnotu bajtu na zadaný offset bajtu.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Cílové pole |
| index | int | Offset bajtu, počítáno od nuly |
| value | **uint8_t** | Hodnota bajtu, která se má nastavit |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

Interpretujte zadané typované pole jako surové pole bajtů a nastavte zadanou hodnotu bajtu na zadaný offset bajtu.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Parametry šablONY

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Cílový pohled na pole |
| index | int | Offset bajtu, počítáno od nuly |
| value | **uint8_t** | Hodnota bajtu, která se má nastavit |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

Interpretujte zadané typované pole jako surové pole bajtů a nastavte zadanou hodnotu bajtu na zadaný offset bajtu.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Parametry šablONY

| Parametr | Popis |
| --- | --- |
| T | Typ prvků pole |
| N | Velikost zásobníkového pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Cílové zásobníkové pole |
| index | int | Offset bajtu, počítáno od nuly |
| value | **uint8_t** | Hodnota bajtu, která se má nastavit |

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)