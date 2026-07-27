---
title: VerifySignature()
second_title: Referência da API Aspose.Slides para C++
description: Verifica a assinatura do hash dos dados.
type: docs
weight: 40
url: /pt/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Verifica a assinatura do hash dos dados.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash calculado para os dados. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Assinatura recebida para os dados. |

### Valor de retorno

True se a assinatura for válida, false caso contrário.

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RSAPKCS1SignatureDeformatter](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)