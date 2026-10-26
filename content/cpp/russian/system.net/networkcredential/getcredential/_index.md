---
title: GetCredential()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает учетные данные для указанного URI и типа аутентификации.
type: docs
weight: 92
url: /ru/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) метод


Возвращает учётные данные для указанного URI и типа аутентификации.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## NetworkCredential::GetCredential(String, int32_t, String) метод


Возвращает учётные данные для указанного имени хоста, порта и типа аутентификации.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя хоста. |
| port | **int32_t** | Номер порта. |
| authenticationType | [String](../../../system/string/) | Тип аутентификации. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [NetworkCredential](../)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)