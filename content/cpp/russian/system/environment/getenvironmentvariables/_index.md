---
title: GetEnvironmentVariables()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает словарь, содержащий все имена переменных среды и их значения, связанные с текущим процессом.
type: docs
weight: 326
url: /ru/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() метод

Возвращает словарь, содержащий все имена переменных среды и их значения, связанные с текущим процессом.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) метод

Возвращает словарь, содержащий все имена переменных среды и их значения из указанного местоположения.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Местоположение переменных |

### Возвращаемое значение

Словарь, содержащий все имена переменных среды и их значения из указанного местоположения

## См. также

* Перечисление [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Класс [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Класс [String](../../string/)
* Структура [Environment](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)