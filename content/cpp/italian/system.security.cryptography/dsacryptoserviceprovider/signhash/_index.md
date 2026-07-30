---
title: SignHash()
second_title: Riferimento API Aspose.Slides per C++
description: Calcola la firma del valore di input specificato.
type: docs
weight: 196
url: /it/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) metodo


Calcola la firma del valore di input specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash value of data to be signed. |
| str | const [String](../../../system/string/)\& | Hash algorithm identifier used to create the hash. |

### Valore restituito

[DSA](../../dsa/) firma per i dati specificati.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)