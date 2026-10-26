---
title: Add()
second_title: Aspose.Slides для C++ справочника API
description: Добавляет указанные сетевые учётные данные в кэш.
type: docs
weight: 40
url: /ru/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method


Добавляет указанные сетевые учётные данные в кэш.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Префикс URI ресурса, с которым связаны учётные данные. |
| authenticationType | [String](../../../system/string/) | Схема аутентификации. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Учётные данные для добавления. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method


Добавляет указанные сетевые учётные данные в кэш.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя хоста, с которым связаны учётные данные. |
| port | **int32_t** | Номер порта. |
| authenticationType | [String](../../../system/string/) | Схема аутентификации. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Учётные данные для добавления. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [NetworkCredential](../../networkcredential/)
* Класс [CredentialCache](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)