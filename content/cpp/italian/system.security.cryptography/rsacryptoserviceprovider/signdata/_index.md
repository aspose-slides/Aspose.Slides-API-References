---
title: SignData()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola la firma del valore di input specificato.
type: docs
weight: 183
url: /it/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) metodo

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) per leggere i dati di input da. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritmo hash da utilizzare. |

### Valore di ritorno

[RSA](../../rsa/) firma per i dati specificati.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) metodo

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Flusso da cui leggere i dati da firmare. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritmo hash da utilizzare. |

### Valore di ritorno

[RSA](../../rsa/) firma per i dati specificati.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) metodo

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) per leggere i dati di input da. |
| offset | **int32_t** | Indice di inizio della porzione del buffer di input. |
| count | **int32_t** | Dimensione della porzione del buffer di input. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritmo hash da utilizzare. |

### Valore di ritorno

[RSA](../../rsa/) firma per i dati specificati.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [RSACryptoServiceProvider](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)