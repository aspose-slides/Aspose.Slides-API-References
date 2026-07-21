---
title: X509KeyUsageFlags
second_title: Aspose.Slides для C++ справочник API
description: Определяет, как может использоваться ключ сертификата.
type: docs
weight: 274
url: /ru/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Определяет, как может использоваться ключ сертификата.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Нет параметров использования ключа. |
| EncipherOnly | 1 | Ключ может использоваться только для шифрования. |
| CrlSign | 2 | Ключ может использоваться для подписи списка отзыва сертификатов. |
| KeyCertSign | 4 | Ключ может использоваться для подписи сертификатов. |
| KeyAgreement | 8 | Ключ может использоваться для установления согласования ключей. |
| DataEncipherment | 16 | Ключ может использоваться для шифрования данных. |
| KeyEncipherment | 32 | Ключ может использоваться для шифрования ключа. |
| NonRepudiation | 64 | Ключ может использоваться для аутентификации. |
| DigitalSignature | 128 | Ключ может использоваться в качестве цифровой подписи. |
| DecipherOnly | 32768 | Ключ может использоваться только для дешифрования. |

## См. также

* Пространство имён [System::Security::Cryptography::X509Certificates](../)
* Библиотека [Aspose.Slides](../../)