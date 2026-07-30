---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.
type: docs
weight: 391
url: /it/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore restituito

Il numero di byte letti

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore restituito

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [SslStream](../)
* Spazio dei nomi [System::Net::Security](../../)
* Libreria [Aspose.Slides](../../../)