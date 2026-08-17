---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /ru/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства заливки узором.

--------------------

Этот интерфейс используется как часть [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) и [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Creates a tile image for the pattern fill with a specified colors. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Возвращает стиль узора. Только для чтения [PatternStyle](../../com.aspose.slides/patternstyle).

**Возвращает:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Возвращает цвет переднего плана узора. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Возвращает цвет фона узора. Только для чтения java.awt.Color.

**Возвращает:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Создаёт изображение-плитку для заливки узором с указанными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.awt.Color | The background java.awt.Color for the pattern. |
| foreground | java.awt.Color | The foreground java.awt.Color for the pattern. |

**Возвращает:** [IImage](../../com.aspose.slides/iimage) - Плитка [IImage](../../com.aspose.slides/iimage).