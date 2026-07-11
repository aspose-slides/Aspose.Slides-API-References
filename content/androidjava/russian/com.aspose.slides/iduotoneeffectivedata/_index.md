---
title: IDuotoneEffectiveData
second_title: Aspose.Slides для Android через справочник Java API
description: Неизменяемый объект, представляющий эффект Duotone.
type: docs
url: /ru/com.aspose.slides/iduotoneeffectivedata/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Неизменяемый объект, представляющий эффект Duotone. Для каждого пикселя сочетает clr1 и clr2 посредством линейной интерполяции, чтобы определить новый цвет для этого пикселя.
## Методы

| Method | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Возвращает целевой формат цвета для тёмных пикселей. |
| [getColor2()](#getColor2--) | Возвращает целевой формат цвета для светлых пикселей. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```


Возвращает целевой формат цвета для тёмных пикселей. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```


Возвращает целевой формат цвета для светлых пикселей. Только для чтения java.lang.Integer.

**Возвращает:**
java.lang.Integer