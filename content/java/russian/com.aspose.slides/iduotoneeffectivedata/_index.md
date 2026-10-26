---
title: IDuotoneEffectiveData
second_title: Aspose.Slides для справочника API Java
description: Неизменяемый объект, представляющий эффект Duotone.
type: docs
url: /ru/com.aspose.slides/iduotoneeffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект Duotone. Для каждого пиксела комбинация clr1 и clr2 выполняется с помощью линейной интерполяции для определения нового цвета пиксела.
## Методы

| Метод | Описание |
| --- | --- |
| [getColor1()](#getColor1--) | Возвращает целевой формат цвета для тёмных пикселей. |
| [getColor2()](#getColor2--) | Возвращает целевой формат цвета для светлых пикселей. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Возвращает целевой формат цвета для тёмных пикселей. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Возвращает целевой формат цвета для светлых пикселей. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color