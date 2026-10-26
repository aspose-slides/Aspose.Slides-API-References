---
title: GetByte()
second_title: Riferimento API di Aspose.Slides per C++
description: Interpreta l'array tipizzato specificato come un array di byte grezzo e recupera il valore del byte all'offset byte specificato.
type: docs
weight: 27
url: /it/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) metodo


Interpreta l'array tipizzato specificato come un array di byte grezzo e recupera il valore del byte all'offset byte specificato.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | L'array di destinazione |
| index | int | Offset zero-based del byte da recuperare |

### Valore di ritorno

Il valore del byte all'indice specificato

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) metodo


Interpreta l'array tipizzato specificato come un array di byte grezzo e recupera il valore del byte all'offset byte specificato.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi della vista dell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | La vista dell'array di destinazione |
| index | int | Offset zero-based del byte da recuperare |

### Valore di ritorno

Il valore del byte all'indice specificato

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) metodo


Interpreta l'array tipizzato specificato come un array di byte grezzo e recupera il valore del byte all'offset byte specificato.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'array di stack |
| N | La dimensione dell'array di stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | L'array di stack di destinazione |
| index | int | Offset zero-based del byte da recuperare |

### Valore di ritorno

Il valore del byte all'indice specificato

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)