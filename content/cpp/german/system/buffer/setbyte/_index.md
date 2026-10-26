---
title: SetByte()
second_title: Aspose.Slides für C++ API-Referenz
description: Interpretiert das angegebene typisierte Array als rohes Byte-Array und setzt den angegebenen Byte-Wert an dem angegebenen Byte-Offset.
type: docs
weight: 40
url: /de/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) Methode


Interpretier das angegebene typisierte Array als rohes Byte-Array und setze den angegebenen Byte-Wert an dem angegebenen Byte-Offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des Arrays |

### Arguments

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Das Zielarray |
| index | int | Nullbasierter Offset des zu setzenden Bytes |
| value | **uint8_t** | Der zu setzende Byte-Wert |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) Methode


Interpretier das angegebene typisierte Array als rohes Byte-Array und setze den angegebenen Byte-Wert an dem angegebenen Byte-Offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des Arrays |

### Arguments

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Die Ziel-Array-Ansicht |
| index | int | Nullbasierter Offset des zu setzenden Bytes |
| value | **uint8_t** | Der zu setzende Byte-Wert |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) Methode


Interpretier das angegebene typisierte Array als rohes Byte-Array und setze den angegebenen Byte-Wert an dem angegebenen Byte-Offset.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente des Arrays |
| N | Die Größe des Stack-Arrays |

### Arguments

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Das Ziel-Stack-Array |
| index | int | Nullbasierter Offset des zu setzenden Bytes |
| value | **uint8_t** | Der zu setzende Byte-Wert |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)