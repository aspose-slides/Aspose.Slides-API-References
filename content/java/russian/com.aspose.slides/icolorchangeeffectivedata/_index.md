---
title: IColorChangeEffectiveData
second_title: Aspose.Slides для Java: справочник API
description: Неизменяемый объект, представляющий эффект изменения цвета.
type: docs
url: /ru/com.aspose.slides/icolorchangeeffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект изменения цвета. Экземпляры FromColor заменяются экземплярами ToColor.
## Методы

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Цвет, который будет заменён. |
| [getToColor()](#getToColor--) | Цвет, который заменит. |
| [getUseAlpha()](#getUseAlpha--) | Возвращает значение типа boolean, которое определяет, следует ли использовать альфа-компонент. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Цвет, который будет заменён. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Цвет, который заменит. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Возвращает значение типа boolean, которое определяет, следует ли использовать альфа-компонент. Точно только для чтения boolean.

**Возвращает:**
boolean