---
title: IWarningCallback
second_title: Aspose.Slides для Java справка API
description: Интерфейс для классов, которые получают предупреждения
type: docs
url: /ru/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Интерфейс для классов, которые получают предупреждения
## Методы

| Метод | Описание |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Метод обратного вызова, который получает предупреждение и решает, следует ли прервать операцию. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Метод обратного вызова, который получает предупреждение и решает, следует ли прервать операцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Предупреждение для обработки. |

**Возврат:**
int — решение об отмене [ReturnAction](../../com.aspose.slides/returnaction).