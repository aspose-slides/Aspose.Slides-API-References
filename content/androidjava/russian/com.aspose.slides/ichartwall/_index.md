---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет стены на 3D-диаграммах.
type: docs
url: /ru/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Представляет стены на 3D-диаграммах.
## Методы

| Метод | Описание |
| --- | --- |
| [getThickness()](#getThickness--) | Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма графика. |
| [setThickness(int value)](#setThickness-int-) | Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма графика. |
| [getFormat()](#getFormat--) | Возвращает заполнение стены, линию, эффект, 3D-стили. |
| [getPictureType()](#getPictureType--) | Возвращает или задаёт тип изображения. |
| [setPictureType(int value)](#setPictureType-int-) | Возвращает или задаёт тип изображения. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма графика. Чтение/запись int.

**Возвращаемое значение:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма графика. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Возвращает заполнение стены, линию, эффект, 3D-стили. Только чтение [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Возвращает или задаёт тип изображения. Чтение/запись [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Возвращаемое значение:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Возвращает или задаёт тип изображения. Чтение/запись [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |