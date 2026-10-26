---
title: GetEnvironmentVariable()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение указанной переменной окружения, связанной с текущим процессом.
type: docs
weight: 287
url: /ru/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) метод


Возвращает значение указанной переменной окружения, связанной с текущим процессом.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Строка, содержащая имя переменной для получения |

### Возвращаемое значение

Значение указанной переменной

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) метод


Возвращает значение указанной переменной окружения из указанного места.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| variable | const [String](../../string/)\& | Строка, содержащая имя переменной для получения |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Местоположение переменной |

### Возвращаемое значение

Значение указанной переменной

## Смотрите также

* Перечисление [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Класс [String](../../string/)
* Структура [Environment](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)