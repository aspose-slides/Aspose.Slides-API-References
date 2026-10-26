---
title: get_InterruptionToken()
second_title: Aspose.Slides для C++ справочник API
description: Токен для отслеживания запросов на прерывание.
type: docs
weight: 235
url: /ru/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() метод

Токен, используемый для мониторинга запросов на прерывание.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Примечания

Этот токен управляет полной продолжительностью жизни экземпляра [IPresentation](../../ipresentation/). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана вызовом метода [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) объекта [InterruptionTokenSource](../../interruptiontokensource/).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IInterruptionToken](../../iinterruptiontoken/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)