---
title: GetByte()
second_title: Aspose.Slides voor C++ API-referentie
description: Interpreteert de opgegeven getypeerde array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset.
type: docs
weight: 27
url: /nl/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) methode

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | De doel-array |
| index | int | Nul-gebaseerde offset van de byte die opgehaald moet worden |

### Retourwaarde

De byte-waarde op de opgegeven index

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) methode

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | De doel-array-view |
| index | int | Nul-gebaseerde offset van de byte die opgehaald moet worden |

### Retourwaarde

De byte-waarde op de opgegeven index

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) methode

Interpreteert de opgegeven getypeerde array als een ruwe byte-array en haalt de byte-waarde op op de opgegeven byte-offset.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de elementen van de stack-array |
| N | De grootte van de stack-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | De doel-stack-array |
| index | int | Nul-gebaseerde offset van de byte die opgehaald moet worden |

### Retourwaarde

De byte-waarde op de opgegeven index

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)