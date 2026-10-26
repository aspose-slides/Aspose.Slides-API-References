---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /ru/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Представляет свойства форматирования маркировки абзаца.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Возвращает или задаёт тип маркера абзаца без наследования. |
| [setType(byte value)](#setType-byte-) | Возвращает или задаёт тип маркера абзаца без наследования. |
| [getChar()](#getChar--) | Возвращает или задаёт символ маркера абзаца без наследования. |
| [setChar(char value)](#setChar-char-) | Возвращает или задаёт символ маркера абзаца без наследования. |
| [getFont()](#getFont--) | Возвращает или задаёт шрифт маркера абзаца без наследования. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Возвращает или задаёт шрифт маркера абзаца без наследования. |
| [getHeight()](#getHeight--) | Возвращает или задаёт высоту маркера абзаца без наследования. |
| [setHeight(float value)](#setHeight-float-) | Возвращает или задаёт высоту маркера абзаца без наследования. |
| [getColor()](#getColor--) | Возвращает формат цвета маркера абзаца без наследования. |
| [getPicture()](#getPicture--) | Возвращает изображение, используемое в качестве маркера в абзаце без наследования. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Возвращает или задаёт первое число, используемое для группы нумерованных маркеров без наследования. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Возвращает или задаёт первое число, используемое для группы нумерованных маркеров без наследования. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Возвращает или задаёт стиль нумерованного маркера без наследования. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Возвращает или задаёт стиль нумерованного маркера без наследования. |
| [isBulletHardColor()](#isBulletHardColor--) | Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. |
| [isBulletHardFont()](#isBulletHardFont--) | Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Устанавливает значения сдвигов, отличные от нуля, для эффективного отступа абзаца (Indent) и левого поля (MarginLeft), когда маркеры включены (как PowerPoint делает при включении маркеров/нумерации абзаца). |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования маркера с учётом наследования. |
### getType() {#getType--}
```
public abstract byte getType()
```


Возвращает или задаёт тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Возвращает:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Возвращает или задаёт тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Возвращает или задаёт символ маркера абзаца без наследования. Чтение/запись char.

**Возвращает:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Возвращает или задаёт символ маркера абзаца без наследования. Чтение/запись char.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Возвращает или задаёт шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Возвращает или задаёт шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Возвращает или задаёт высоту маркера абзаца без наследования. Значение Float.NaN определяет, что высота маркера наследуется из первой части абзаца. Чтение/запись float.

**Возвращает:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Возвращает или задаёт высоту маркера абзаца без наследования. Значение Float.NaN определяет, что высота маркера наследуется из первой части абзаца. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Возвращает формат цвета маркера абзаца без наследования. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```


Возвращает изображение, используемое в качестве маркера в абзаце без наследования. Только для чтения [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Возвращает:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Возвращает или задаёт первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short.

**Возвращает:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Возвращает или задаёт первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Возвращает или задаёт стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Возвращает:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Возвращает или задаёт стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. **NullableBool\#True** if bullet has own color and **NullableBool\#False** if bullet inherits color from the first portion in the paragraph. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. **NullableBool\#True** if bullet has own color and **NullableBool\#False** if bullet inherits color from the first portion in the paragraph. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. **NullableBool\#True** if bullet has own font and **NullableBool\#False** if bullet inherits font from the first portion in the paragraph. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. **NullableBool\#True** if bullet has own font and **NullableBool\#False** if bullet inherits font from the first portion in the paragraph. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Устанавливает значения сдвигов, отличные от нуля, для эффективного отступа абзаца (Indent) и левого поля (MarginLeft), когда маркеры включены (как PowerPoint делает при включении маркеров/нумерации абзаца). Если маркеры отключены, то просто сбрасывает отступ абзаца и левое поле (как PowerPoint делает при отключении маркеров/нумерации абзаца). Сдвиги отступов применяются относительно текущего контекста маркеров — IBulletFormat.Type, .NumberedBulletStyle и FontHeight первой части. Сдвиги, отличные от нуля, применяются к эффективным Indent и MarginLeft текущего абзаца (чтобы полученные значения были локальными).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Получает эффективные данные форматирования маркера с учётом наследования.

--------------------

> ```
> Этот пример демонстрирует получение некоторых эффективных свойств форматирования маркера.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).