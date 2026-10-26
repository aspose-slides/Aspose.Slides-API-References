---
title: set_InterruptionToken()
second_title: Aspose.Slides для C++ справочника API
description: Токен для отслеживания запросов на прерывание.
type: docs
weight: 248
url: /ru/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) метод

Токен для отслеживания запросов на прерывание.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Примечания

Этот токен управляет всей жизнью экземпляра [IPresentation](../../ipresentation/). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана вызовом метода [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) объекта [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IInterruptionToken](../../iinterruptiontoken/)
* Класс [ILoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)