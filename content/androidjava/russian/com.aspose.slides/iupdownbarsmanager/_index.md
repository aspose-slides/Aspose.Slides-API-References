---
title: IUpDownBarsManager
second_title: Aspose.Slides для Android через Java API Reference
description: Обеспечивает доступ к верхним/нижним столбикам линейного или биржевого графика.
type: docs
url: /ru/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Обеспечивает доступ к верхним/нижним столбикам линейного или биржевого графика.
## Методы

| Method | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Возвращает формат верхних столбиков. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Возвращает формат нижних столбиков. |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, есть ли у диаграммы верхние/нижние столбики. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Определяет, есть ли у диаграммы верхние/нижние столбики. |
| [getGapWidth()](#getGapWidth--) | Возвращает или задает ширину промежутка. |
| [setGapWidth(int value)](#setGapWidth-int-) | Возвращает или задает ширину промежутка. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Возвращает формат верхних столбиков. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Возвращает формат нижних столбиков. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Определяет, есть ли у диаграммы верхние/нижние столбики. Чтение/запись boolean.

**Возвращает:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Определяет, есть ли у диаграммы верхние/нижние столбики. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Возвращает или задает ширину промежутка. Чтение/запись int.

**Возвращает:**
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