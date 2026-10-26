---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Обеспечивает доступ к верхним/нижним полосам линейной или биржевой диаграммы.
type: docs
url: /ru/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Обеспечивает доступ к верхним/нижним полосам линейной или биржевой диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Возвращает формат верхних полос. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Возвращает формат нижних полос. |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, имеет ли диаграмма верхние/нижние полосы. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Определяет, имеет ли диаграмма верхние/нижние полосы. |
| [getGapWidth()](#getGapWidth--) | Возвращает или задает ширину промежутка. |
| [setGapWidth(int value)](#setGapWidth-int-) | Возвращает или задает ширину промежутка. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Возвращает формат верхних полос. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**  
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Возвращает формат нижних полос. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**  
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Определяет, имеет ли диаграмма верхние/нижние полосы. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Определяет, имеет ли диаграмма верхние/нижние полосы. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Возвращает или задает ширину промежутка. Чтение/запись int.

**Возвращаемое значение:**  
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Возвращает или задает ширину промежутка. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |