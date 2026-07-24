---
title: GetByte()
second_title: Aspose.Slides für C++ API-Referenz
description: Interpretiert das angegebene typisierte Array als rohes Byte-Array und gibt den Byte-Wert am angegebenen Byte-Offset zurück.
type: docs
weight: 27
url: /de/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) Methode


Interpretiert das angegebene typisierte Array als rohes Byte-Array und gibt den Byte-Wert am angegebenen Byte-Offset zurück.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente des Arrays |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Das Ziel-Array |
| index | int | Nullbasierter Offset des abzurufenden Bytes |

### Rückgabewert

Der Byte-Wert am angegebenen Index

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) Methode


Interpretiert das angegebene typisierte Array als rohes Byte-Array und gibt den Byte-Wert am angegebenen Byte-Offset zurück.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente der Array-Ansicht |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Die Ziel-Array-Ansicht |
| index | int | Nullbasierter Offset des abzurufenden Bytes |

### Rückgabewert

Der Byte-Wert am angegebenen Index

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) Methode


Interpretiert das angegebene typisierte Array als rohes Byte-Array und gibt den Byte-Wert am angegebenen Byte-Offset zurück.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente des Stack-Arrays |
| N | Die Größe des Stack-Arrays |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Das Ziel-Stack-Array |
| index | int | Nullbasierter Offset des abzurufenden Bytes |

### Rückgabewert

Der Byte-Wert am angegebenen Index

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)