---
title: GetHostEntry()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр IPHostEntry-class, используя указанную строку, содержащую имя хоста или IP-адрес.
type: docs
weight: 79
url: /ru/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) метод


Создает новый IPHostEntry-class экземпляр, используя указанную строку, содержащую имя хоста или IP-адрес.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Строка, содержащая имя хоста или IP-адрес. |

### Return Value

Новый созданный IPHostEntry-class экземпляр.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) метод


Создает новый IPHostEntry-class экземпляр, используя указанный IP-адрес.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-адрес. |

### Return Value

Новый созданный IPHostEntry-class экземпляр.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPHostEntry](../../iphostentry/)
* Класс [String](../../../system/string/)
* Класс [Dns](../)
* Класс [IPAddress](../../ipaddress/)
* Пространство имен [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)