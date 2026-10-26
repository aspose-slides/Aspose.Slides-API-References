---
title: NetworkStream()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр.
type: docs
weight: 170
url: /ru/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Сокет, используемый для отправки и получения данных. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Сокет, используемый для отправки и получения данных. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Указывает тип доступа, предоставляемый экземпляру через указанный сокет. |
| ownsSocket | **bool** | Значение, указывающее, принимает ли текущий экземпляр владение указанным сокетом, если значение истинно. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) конструктор

Создаёт новый экземпляр.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Сокет, используемый для отправки и получения данных. |
| ownsSocket | **bool** | Значение, указывающее, принимает ли текущий экземпляр владение указанным сокетом, если значение истинно. |

## См. также

* Перечисление [FileAccess](../../../system.io/fileaccess/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Socket](../../socket/)
* Класс [NetworkStream](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)