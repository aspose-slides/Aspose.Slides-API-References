---
title: VerifyData()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che la firma dei dati specificati sia valida.
type: docs
weight: 170
url: /it/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metodo

Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. restituisce true se la firma è valida, altrimenti - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) metodo

Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da hashare. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. restituisce true se la firma è valida, altrimenti - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) metodo

Verifica che la firma del flusso binario specificato sia valida.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. restituisce true se la firma è valida, altrimenti - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metodo

Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce true se la firma è valida, altrimenti - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metodo

Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da hashare. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce true se la firma è valida, altrimenti - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metodo

Verifica che la firma del flusso binario specificato sia valida.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce true se la firma è valida, altrimenti - false. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [ECDsaBotan](../)
* Struttura [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)