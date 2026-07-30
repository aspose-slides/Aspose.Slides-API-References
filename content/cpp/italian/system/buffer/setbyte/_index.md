---
title: SetByte()
second_title: Aspose.Slides per C++ Riferimento API
description: Interpreta l'array tipizzato specificato come un array di byte grezzo e imposta il valore byte specificato allo offset di byte specificato.
type: docs
weight: 40
url: /it/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) metodo

Interpreta l'array tipizzato specificato come un array di byte grezzo e imposta il valore byte specificato allo offset di byte specificato.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | L'array di destinazione |
| index | int | Offset basato su zero del byte da impostare |
| value | **uint8_t** | Il valore del byte da impostare |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) metodo

Interpreta l'array tipizzato specificato come un array di byte grezzo e imposta il valore byte specificato allo offset di byte specificato.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'array |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | La vista dell'array di destinazione |
| index | int | Offset basato su zero del byte da impostare |
| value | **uint8_t** | Il valore del byte da impostare |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) metodo

Interpreta l'array tipizzato specificato come un array di byte grezzo e imposta il valore byte specificato allo offset di byte specificato.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo degli elementi dell'array |
| N | La dimensione dell'array di stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | L'array di stack di destinazione |
| index | int | Offset basato su zero del byte da impostare |
| value | **uint8_t** | Il valore del byte da impostare |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../../array/)
* Classe [Buffer](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)