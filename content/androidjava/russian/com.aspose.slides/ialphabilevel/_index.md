---
title: IAlphaBiLevel
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет эффект Alpha Bi-Level.
type: docs
url: /ru/com.aspose.slides/ialphabilevel/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Представляет эффект Alpha Bi-Level. Значения Alpha (Opacity) меньше порога изменяются на 0 (полностью прозрачные), а значения alpha, большие или равные порогу, изменяются на 100% (полностью непрозрачные).

--------------------

Используйте ImageTransformOperationFactory для создания экземпляров в COM.
## Методы

| Метод | Описание |
| --- | --- |
| [getThreshold()](#getThreshold--) | Возвращает порог эффекта. |
| [setThreshold(float value)](#setThreshold-float-) | Возвращает порог эффекта. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Возвращает порог эффекта. Чтение/запись float.

**Возвращает:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Возвращает порог эффекта. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |