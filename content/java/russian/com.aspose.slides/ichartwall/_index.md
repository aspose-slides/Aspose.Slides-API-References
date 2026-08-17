---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Представляет стены 3D-диаграмм.
type: docs
url: /ru/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Представляет стены 3D-диаграмм.
## Методы

| Метод | Описание |
| --- | --- |
| [getThickness()](#getThickness--) | Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма области построения. |
| [setThickness(int value)](#setThickness-int-) | Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма области построения. |
| [getFormat()](#getFormat--) | Возвращает заливку стены, линию, эффект, 3D-стили. |
| [getPictureType()](#getPictureType--) | Возвращает или задаёт тип изображения. |
| [setPictureType(int value)](#setPictureType-int-) | Возвращает или задаёт тип изображения. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма области построения. Чтение/запись int.

**Возвращаемое значение:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Возвращает или задаёт толщину стен в процентах от наибольшего измерения объёма области построения. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Возвращает заливку стены, линию, эффект, 3D-стили. Только для чтения [IFormat](../../com.aspose.slides/iformat).

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