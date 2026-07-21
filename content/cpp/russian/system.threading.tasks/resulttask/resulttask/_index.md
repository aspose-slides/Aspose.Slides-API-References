---
title: ResultTask()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт объект ResultTask с функцией, которая возвращает значение.
type: docs
weight: 1
url: /ru/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) конструктор


Создает [ResultTask](../) с функцией, которая возвращает значение.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Функция, которую нужно выполнить асинхронно и которая возвращает результат |

## ResultTask::ResultTask() конструктор


Внутренняя реализация. Не предназначено для пользовательского кода.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Примечания


Внутренний конструктор для создания неинициализированных задач результатов 
## ResultTask::ResultTask(const T\&) конструктор


Внутренний конструктор для создания задач результатов с указанным результатом.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## См. также

* Класс [Func](../../../system/func/)
* Класс [ResultTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)