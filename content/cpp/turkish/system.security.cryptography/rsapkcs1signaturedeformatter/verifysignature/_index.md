---
title: VerifySignature()
second_title: Aspose.Slides for C++ API Referansı
description: Veri karmasının imzasını doğrular.
type: docs
weight: 40
url: /tr/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodu


Veri karmasının imzasını doğrular.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Veri için hesaplanan hash. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Veri için alınan imza. |

### Dönüş Değeri

İmza geçerli ise True, aksi takdirde false.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [RSAPKCS1SignatureDeformatter](../)
* İsim Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)