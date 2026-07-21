---
title: ComputeSignature()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт подпись.
type: docs
weight: 14
url: /ru/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) метод

Создает подпись.

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | Signer для использования. |
| silent | **bool** | Нужно ли подавить запрос пользовательa о действительном сертификате, если сертификат, связанный с **signer**, недействителен. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [CmsSigner](../../cmssigner/)
* Класс [SignedCms](../)
* Пространство имён [System::Security::Cryptography::Pkcs](../../)
* Библиотека [Aspose.Slides](../../../)