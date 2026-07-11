---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет базовый интерфейс для всех предупреждений.
type: docs
url: /ru/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Представляет базовый интерфейс для всех предупреждений.
## Методы

| Метод | Описание |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Если получатель не null, завершаем предупреждение указанному получателю и бросаем AbortRequestedException, если получатель решил прервать операцию. |
| [getWarningType()](#getWarningType--) | Возвращает тип предупреждения. |
| [getDescription()](#getDescription--) | Возвращает человекочитаемое описание этого предупреждения. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Если получатель не null, завершаем предупреждение указанному получателю и бросаем AbortRequestedException, если получатель решил прервать операцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Объект получателя [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Возвращает тип предупреждения. Только для чтения [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Возврат:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Возвращает человекочитаемое описание этого предупреждения. Только для чтения String.

**Возврат:**
java.lang.String