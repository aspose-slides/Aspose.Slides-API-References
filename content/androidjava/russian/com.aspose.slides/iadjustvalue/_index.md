---
title: IAdjustValue
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет значение регулировки геометрической фигуры. Эти значения влияют на форму фигуры.
type: docs
url: /ru/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Представляет значение регулировки геометрической фигуры. Эти значения влияют на форму фигуры.
## Методы

| Method | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | Возвращает или задаёт значение регулировки «as is». |
| [setRawValue(long value)](#setRawValue-long-) | Возвращает или задаёт значение регулировки «as is». |
| [getAngleValue()](#getAngleValue--) | Возвращает или задаёт значение, интерпретируя его как угол в градусах. |
| [setAngleValue(float value)](#setAngleValue-float-) | Возвращает или задаёт значение, интерпретируя его как угол в градусах. |
| [getName()](#getName--) | Возвращает имя этого значения регулировки. |
| [getType()](#getType--) | Возвращает тип регулировки фигуры. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Возвращает или задаёт значение регулировки «as is». Чтение/запись long.

**Возвращаемое значение:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Возвращает или задаёт значение регулировки «as is». Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Возвращает или задаёт значение, интерпретируя его как угол в градусах. Чтение/запись float.

**Возвращаемое значение:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Возвращает или задаёт значение, интерпретируя его как угол в градусах. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя этого значения регулировки. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип регулировки фигуры. Только для чтения [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Возвращаемое значение:**
int