---
title: Enter()
second_title: Справочник API Aspose.Slides для C++
description: Захватывает эксклюзивный замок на указанном объекте.
type: docs
weight: 1
url: /ru/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) метод


Захватывает эксклюзивный замок на указанном объекте.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Объект, на котором нужно захватить мониторный замок. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) метод


Захватывает эксклюзивный замок на указанном объекте и атомарно устанавливает значение, указывающее, был ли замок получен.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## См. также

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [Monitor](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)