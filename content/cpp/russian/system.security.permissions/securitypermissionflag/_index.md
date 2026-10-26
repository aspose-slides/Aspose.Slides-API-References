---
title: SecurityPermissionFlag
second_title: Aspose.Slides для C++ справочник API
description: Флаги разрешения безопасности.
type: docs
weight: 27
url: /ru/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag перечисление


Флаги разрешения безопасности.

```cpp
enum class SecurityPermissionFlag
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| NoFlags | 0 | Нет доступа. |
| Assertion | 1 | Утверждать, что разрешение предоставлено. |
| UnmanagedCode | 2 | Вызвать неуправляемый код. |
| SkipVerification | 4 | Пропустить проверку кода. |
| Execution | 8 | Выполнять код. |
| ControlThread | 16 | Выполнять операции над потоками. |
| ControlEvidence | 32 | Управлять или изменять доказательства CLR. |
| ControlPolicy | 64 | Просматривать и изменять политику. |
| SerializationFormatter | 128 | Сериализовать. |
| ControlDomainPolicy | 256 | Устанавливать политику домена. |
| ControlPrincipal | 512 | Управлять объектом principal. |
| ControlAppDomain | 1024 | Управлять доменом приложения. |
| RemotingConfiguration | 2048 | Настраивать удалённый доступ. |
| Infrastructure | 4096 | Подключаться к инфраструктуре CLR. |
| BindingRedirects | 8192 | Выполнять явное перенаправление привязки. |
| AllFlags | 16383 | Не ограничено. |

## См. также

* Пространство имён [System::Security::Permissions](../)
* Библиотека [Aspose.Slides](../../)