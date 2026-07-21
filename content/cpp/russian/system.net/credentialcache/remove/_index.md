---
title: Remove()
second_title: Aspose.Slides для C++ — справочник API
description: Удаляет сетевые учетные данные для указанного префикса URI и типа аутентификации.
type: docs
weight: 53
url: /ru/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) метод

Удаляет сетевые учетные данные для указанного префикса URI и типа аутентификации.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Префикс URI. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## CredentialCache::Remove(String, int32_t, String) метод

Удаляет сетевые учетные данные для указанного имени хоста, порта и типа аутентификации.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя хоста, с которым связаны учетные данные. |
| port | **int32_t** | Номер порта. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [CredentialCache](../)
* Пространство имен [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)