---
title: VerifyHash()
second_title: Referência da API Aspose.Slides para C++
description: Verifica a assinatura dos dados.
type: docs
weight: 118
url: /pt/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) método


Verifica a assinatura dos dados.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash calculado para os dados recebidos. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Assinatura conforme recebida. |

### Valor de Retorno

True if signature is valid, false otherwise.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [ECDsa](../)
* Namespace [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)