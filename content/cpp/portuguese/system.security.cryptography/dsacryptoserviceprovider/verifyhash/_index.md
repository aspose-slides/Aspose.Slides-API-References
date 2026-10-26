---
title: VerifyHash()
second_title: Aspose.Slides para C++ Referência da API
description: Verifica a assinatura dos dados.
type: docs
weight: 222
url: /pt/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method

Verifica a assinatura dos dados.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calculado para os dados recebidos. |
| str | const [String](../../../system/string/)\& | Nome do algoritmo de hash usado. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Assinatura conforme recebida. |

### Valor de Retorno

True se a assinatura for válida, false caso contrário.

## Veja Também

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)