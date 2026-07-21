---
title: Warning()
second_title: Aspose.Slides для C++ справочник API
description: Метод обратного вызова, который получает предупреждение и решает, следует ли отменять операцию.
type: docs
weight: 1
url: /ru/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) method

Метод обратного вызова, который получает предупреждение и решает, следует ли отменять операцию.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Предупреждение для обработки. |

### Возвращаемое значение

Решение об отмене [ReturnAction](../../returnaction/).

## Смотрите также

* Перечисление [ReturnAction](../../returnaction/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IWarningInfo](../../iwarninginfo/)
* Класс [IWarningCallback](../)
* Пространство имён [Aspose::Slides::Warnings](../../)
* Библиотека [Aspose.Slides](../../../)