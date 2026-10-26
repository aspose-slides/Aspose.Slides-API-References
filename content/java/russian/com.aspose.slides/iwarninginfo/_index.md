---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /ru/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Представляет базовый интерфейс для всех предупреждений.
## Методы

| Метод | Описание |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Если receiver не равен null, завершает предупреждение заданному receiver и бросает AbortRequestedException, если receiver решил прервать операцию. |
| [getWarningType()](#getWarningType--) | Возвращает тип предупреждения. |
| [getDescription()](#getDescription--) | Возвращает человекочитаемое описание этого предупреждения. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Если receiver не равен null, завершает предупреждение заданному receiver и бросает AbortRequestedException, если receiver решил прервать операцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Объект receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Возвращает тип предупреждения. Только для чтения [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Возвращаемое значение:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Возвращает человекочитаемое описание этого предупреждения. Только для чтения String.

**Возвращаемое значение:**
java.lang.String