---
title: GetCredential()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает учетные данные для указанного префикса URI и типа аутентификации.
type: docs
weight: 66
url: /ru/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) метод

Возвращает учетные данные для указанного префикса URI и типа аутентификации.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Префикс URI. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## CredentialCache::GetCredential(String, int32_t, String) метод

Возвращает учетные данные для указанного имени хоста, порта и типа аутентификации.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя хоста, с которым связаны учетные данные. |
| port | **int32_t** | Номер порта. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [NetworkCredential](../../networkcredential/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [CredentialCache](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)