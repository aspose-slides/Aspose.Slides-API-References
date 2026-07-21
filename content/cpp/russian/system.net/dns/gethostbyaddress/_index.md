---
title: GetHostByAddress()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса IPHostEntry, используя указанное строковое представление IP-адреса.
type: docs
weight: 14
url: /ru/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) метод

Создает новый экземпляр класса IPHostEntry, используя указанное строковое представление IP-адреса.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [String](../../../system/string/) | Строковое представление IP-адреса. |

### Return Value

Возвращаемое значение  
Новый созданный экземпляр класса IPHostEntry.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) метод

Создает новый экземпляр класса IPHostEntry, используя указанный IP-адрес.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP-адрес. |

### Return Value

Возвращаемое значение  
Новый созданный экземпляр класса IPHostEntry.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPHostEntry](../../iphostentry/)
* Класс [String](../../../system/string/)
* Класс [Dns](../)
* Класс [IPAddress](../../ipaddress/)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)