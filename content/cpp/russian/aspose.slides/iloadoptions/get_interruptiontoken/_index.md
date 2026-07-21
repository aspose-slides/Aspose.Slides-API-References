---
title: get_InterruptionToken()
second_title: Aspose.Slides для C++ справочник API
description: Токен для отслеживания запросов на прерывание.
type: docs
weight: 235
url: /ru/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() метод

Токен для отслеживания запросов на прерывание.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Примечания

Этот токен управляет жизненным циклом всего экземпляра [IPresentation](../../ipresentation/). Любая длительная операция, например загрузка или сохранение презентации, будет прервана вызовом метода [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) [IInterruptionTokenSource](../../iinterruptiontokensource/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)