---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства заполнения узором.
type: docs
url: /ru/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства заполнения узором.

--------------------

Этот интерфейс используется как часть [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) и [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Возвращает стиль узора. |
| [getForeColor()](#getForeColor--) | Возвращает цвет переднего узора. |
| [getBackColor()](#getBackColor--) | Возвращает цвет заднего узора. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Создает изображение плитки для заполнения узором с указанными цветами. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Возвращает стиль узора. Только для чтения [PatternStyle](../../com.aspose.slides/patternstyle).

**Возвращаемое значение:**  
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Возвращает цвет переднего узора. Только для чтения java.lang.Integer.

**Возвращаемое значение:**  
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Возвращает цвет заднего узора. Только для чтения java.lang.Integer.

**Возвращаемое значение:**  
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Создает изображение плитки для заполнения узором с указанными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.lang.Integer | Значение java.lang.Integer для цвета заднего узора. |
| foreground | java.lang.Integer | Значение java.lang.Integer для цвета переднего узора. |

**Возвращаемое значение:**  
[IImage](../../com.aspose.slides/iimage) - Плитка [IImage](../../com.aspose.slides/iimage).