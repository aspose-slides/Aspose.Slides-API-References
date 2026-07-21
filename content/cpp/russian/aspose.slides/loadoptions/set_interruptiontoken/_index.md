---
title: set_InterruptionToken()
second_title: Aspose.Slides для C++ Справочник API
description: Токен для отслеживания запросов прерывания.
type: docs
weight: 248
url: /ru/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) метод

Токен, используемый для отслеживания запросов прерывания.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Примечания

Этот токен управляет всем временем жизни экземпляра [IPresentation](../../ipresentation/). Любая длительная операция, например загрузка или сохранение презентации, будет прервана вызовом метода [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) объекта [InterruptionTokenSource](../../interruptiontokensource/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IInterruptionToken](../../iinterruptiontoken/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)