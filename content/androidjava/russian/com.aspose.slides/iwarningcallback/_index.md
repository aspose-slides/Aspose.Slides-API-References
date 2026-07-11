---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /ru/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Интерфейс для классов, получающих предупреждения
## Методы

| Метод | Описание |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Метод обратного вызова, который получает предупреждение и решает, следует ли отменить операцию. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Метод обратного вызова, который получает предупреждение и решает, следует ли отменить операцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Предупреждение для обработки. |

**Возвращаемое значение:**
int - Решение об отмене [ReturnAction](../../com.aspose.slides/returnaction).