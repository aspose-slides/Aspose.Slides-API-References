---
title: IColorChangeEffectiveData
second_title: Aspose.Slides для Android через справочник API Java
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

| Метод | Описание |
| --- | --- |
| [getFromColor()](#getFromColor--) | Цвет, который будет заменен. |
| [getToColor()](#getToColor--) | Цвет, который заменит. |
| [getUseAlpha()](#getUseAlpha--) | Возвращает логическое значение, определяющее, следует ли использовать альфа-компонент. |
### getFromColor() {#getFromColor--}
```
public abstract Integer getFromColor()
```


Цвет, который будет заменен. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer
### getToColor() {#getToColor--}
```
public abstract Integer getToColor()
```


Цвет, который заменит. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Возвращает логическое значение, определяющее, следует ли использовать альфа-компонент. Только для чтения boolean.

**Возвращает:**
boolean