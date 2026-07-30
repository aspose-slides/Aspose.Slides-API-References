---
title: SignData()
second_title: Riferimento API Aspose.Slides per C++
description: Calcola la firma del valore di input specificato.
type: docs
weight: 183
url: /it/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) per leggere i dati di input da. |

### Valore di ritorno

[DSA](../../dsa/) firma per i dati specificati.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Flusso da cui leggere i dati da firmare. |

### Valore di ritorno

[DSA](../../dsa/) firma per i dati specificati.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) per leggere i dati di input da. |
| offset | **int32_t** | Indice iniziale della sezione del buffer di input. |
| count | **int32_t** | Dimensione della sezione del buffer di input. |

### Valore di ritorno

[DSA](../../dsa/) firma per i dati specificati.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce la firma [DSA](../../dsa/) per i dati di input. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da utilizzare come dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce la firma [DSA](../../dsa/) per i dati di input. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Calcola il valore hash del flusso binario specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flusso binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce la firma [DSA](../../dsa/) per i dati di input. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [DSACryptoServiceProvider](../)
* Classe [Stream](../../../system.io/stream/)
* Struttura [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)