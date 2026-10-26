---
title: VerifySignature()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica la firma dell'hash dei dati.
type: docs
weight: 40
url: /it/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

Verifica la firma dell'hash dei dati.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash calcolato per i dati. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Firma ricevuta per i dati. |

### Valore restituito

True se la firma è valida, false altrimenti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RSAPKCS1SignatureDeformatter](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)