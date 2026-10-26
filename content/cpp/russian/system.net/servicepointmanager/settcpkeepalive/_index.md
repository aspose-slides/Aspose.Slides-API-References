---
title: SetTcpKeepAlive()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, указывающее, включена ли опция 'Keep-Alive'.
type: docs
weight: 326
url: /ru/system.net/servicepointmanager/settcpkeepalive/
---
## ServicePointManager::SetTcpKeepAlive(bool, int32_t, int32_t) метод

Устанавливает значение, указывающее, включена ли опция 'Keep-Alive'.

```cpp
static void System::Net::ServicePointManager::SetTcpKeepAlive(bool enabled, int32_t keepAliveTime, int32_t keepAliveInterval)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| enabled | **bool** | Значение, указывающее, включена ли опция 'Keep-Alive'. |
| keepAliveTime | **int32_t** | Тайм-аут в миллисекундах, после которого будет отправлен первый пакет 'Keep-Alive'. |
| keepAliveInterval | **int32_t** | Тайм-аут в миллисекундах между отправкой пакетов 'Keep-Alive'. |

## См. также

* Класс [ServicePointManager](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)