---
title: GetNameInfo()
second_title: Aspose.Slides для C++ API справка
description: Получает имя субъекта или издателя из сертификата.
type: docs
weight: 248
url: /ru/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const метод

Получает имя субъекта или издателя из сертификата.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Параметры форматирования имени. |
| for_issuer | **bool** | Если true, возвращает имя издателя, иначе — имя субъекта. |

### Возвращаемое значение

Отформатированное имя издателя или субъекта.

## См. также

* Перечисление [X509NameType](../../x509nametype/)
* Класс [String](../../../system/string/)
* Класс [X509Certificate2](../)
* Пространство имён [System::Security::Cryptography::X509Certificates](../../)
* Библиотека [Aspose.Slides](../../../)