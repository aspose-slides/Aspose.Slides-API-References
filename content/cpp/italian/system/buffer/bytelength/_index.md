---
title: ByteLength()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina il numero di byte occupati da tutti gli elementi dell'array specificato.
type: docs
weight: 14
url: /it/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


Determina il numero di byte occupati da tutti gli elementi dell'array specificato.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi dell'array |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Un array |

### Valore di ritorno

Il numero di byte occupati da tutti gli elementi dell'array specificato

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Determina il numero di byte occupati da tutti gli elementi della vista dell'array specificata.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi della vista dell'array |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Una vista dell'array |

### Valore di ritorno

Il numero di byte occupati da tutti gli elementi della vista dell'array specificata

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Determina il numero di byte occupati da tutti gli elementi dell'array stack specificato.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi dell'array stack |
| N | La dimensione dell'array stack |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Un array stack |

### Valore di ritorno

Il numero di byte occupati da tutti gli elementi dell'array stack specificato

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)