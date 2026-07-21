---
title: Cancel()
second_title: Справочник API Aspose.Slides для C++
description: Сообщает запрос на отмену.
type: docs
weight: 40
url: /ru/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() метод


Сообщает запрос на отмену.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Примечания



Все зарегистрированные обратные вызовы будут выполнены. 

Последующие вызовы [get_IsCancellationRequested()](../get_iscancellationrequested/) вернут true. 

Обратные вызовы выполняются синхронно во время этого вызова. 

## См. также

* Класс [CancellationTokenSource](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)