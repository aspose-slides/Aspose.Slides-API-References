---
title: Write()
second_title: Riferimento API Aspose.Slides per C++
description: Scrive l'array di byte specificato nello stream.
type: docs
weight: 404
url: /it/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) method

Scrive l'array di byte specificato nello stream.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte da scrivere. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Scrive il sottointervallo di byte specificato dall'array di byte specificato nello stream.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array che contiene i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) method

Scrive l'array di byte specificato nello stream.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | L'array di byte da scrivere. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Scrive il sottointervallo di byte specificato dall'array di byte specificato nello stream.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | L'array che contiene i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## Vedi anche

* Definizione di tipo [ArrayPtr](../../../system/arrayptr/)
* Classe [SslStream](../)
* Spazio dei nomi [System::Net::Security](../../)
* Libreria [Aspose.Slides](../../../)