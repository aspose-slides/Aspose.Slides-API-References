---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /ru/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Представляет значение коррекции геометрической формы. Эти значения влияют на форму фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getRawValue()](#getRawValue--) | Возвращает или задает значение коррекции "как есть". |
| [setRawValue(long value)](#setRawValue-long-) | Возвращает или задает значение коррекции "как есть". |
| [getAngleValue()](#getAngleValue--) | Возвращает или задает значение, интерпретируя его как угол в градусах. |
| [setAngleValue(float value)](#setAngleValue-float-) | Возвращает или задает значение, интерпретируя его как угол в градусах. |
| [getName()](#getName--) | Возвращает имя этого значения коррекции. |
| [getType()](#getType--) | Возвращает тип коррекции фигуры. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Возвращает или задает значение коррекции "как есть". Чтение/запись long.

**Возвращает:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Возвращает или задает значение коррекции "как есть". Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Возвращает или задает значение, интерпретируя его как угол в градусах. Чтение/запись float.

**Возвращает:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Возвращает или задает значение, интерпретируя его как угол в градусах. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя этого значения коррекции. Только для чтения String.

**Возвращает:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип коррекции фигуры. Только для чтения [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Возвращает:**
int