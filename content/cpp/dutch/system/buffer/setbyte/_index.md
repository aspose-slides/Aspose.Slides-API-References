---
title: SetByte()
second_title: Aspose.Slides voor C++ API Referentie
description: Interpreteert de opgegeven getypeerde array als een ruwe byte-array en stelt de opgegeven bytewaarde in op de opgegeven byte-offset.
type: docs
weight: 40
url: /nl/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en stelt de opgegeven bytewaarde in op de opgegeven byte-offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | De doelarray |
| index | int | Nulgebaseerde offset van de byte die moet worden ingesteld |
| value | **uint8_t** | De bytewaarde die moet worden ingesteld |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en stelt de opgegeven bytewaarde in op de opgegeven byte-offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | De doel-arrayview |
| index | int | Nulgebaseerde offset van de byte die moet worden ingesteld |
| value | **uint8_t** | De bytewaarde die moet worden ingesteld |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en stelt de opgegeven bytewaarde in op de opgegeven byte-offset.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de array |
| N | De grootte van de stack-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | De doel stack-array |
| index | int | Nulgebaseerde offset van de byte die moet worden ingesteld |
| value | **uint8_t** | De bytewaarde die moet worden ingesteld |

## Zie Ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)