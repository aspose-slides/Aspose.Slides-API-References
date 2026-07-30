---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.
type: docs
weight: 27
url: /it/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** per iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** per iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | La dimensione dell'array di stack |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | L'array di stack di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** per iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Stream::Read(const System::Span\<uint8_t\>\&) metodo

Legge il numero specificato di byte dallo stream e li scrive nello span di byte specificato.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Lo span di byte in cui scrivere i byte letti |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Stream](../)
* Classe [Span](../../../system/span/)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)