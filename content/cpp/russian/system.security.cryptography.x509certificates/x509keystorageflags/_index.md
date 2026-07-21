---
title: X509KeyStorageFlags
second_title: Справочник API Aspose.Slides для C++
description: Определяет, как хранить ключ.
type: docs
weight: 261
url: /ru/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


Определяет, как хранить ключ.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| DefaultKeySet | 0 | Использовать набор ключей по умолчанию. |
| UserKeySet | 1 | Использовать хранилище, связанное с пользователем, вместо локального машины. |
| MachineKeySet | 2 | Использовать локальное машинное хранилище вместо пользовательского. |
| Exportable | 4 | Помечать импортированные ключи как экспортируемые. |
| UserProtected | 8 | Уведомить пользователя, что ключ используется. |
| PersistKeySet | 16 | Ключ сохраняется при импорте сертификата. |

## См. также

* Пространство имён [System::Security::Cryptography::X509Certificates](../)
* Библиотека [Aspose.Slides](../../)