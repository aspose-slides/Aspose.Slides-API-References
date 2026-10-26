---
title: ByteLength()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen.
type: docs
weight: 14
url: /nl/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) methode


Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van de array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Een array |

### Retourwaarde

Het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) methode


Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van de array view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Een array view |

### Retourwaarde

Het aantal bytes dat door alle elementen van de opgegeven array view wordt ingenomen

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) methode


Bepaalt het aantal bytes dat door alle elementen van de opgegeven array wordt ingenomen.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen van de stack array |
| N | De grootte van de stack array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Een stack array |

### Retourwaarde

Het aantal bytes dat door alle elementen van de opgegeven stack array wordt ingenomen

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../../array/)
* Klasse [Buffer](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)