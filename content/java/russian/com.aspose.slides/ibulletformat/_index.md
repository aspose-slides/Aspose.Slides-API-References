---
title: IBulletFormat
second_title: Aspose.Slides for Java API Reference
description: Представляет свойства форматирования маркеров абзаца.
type: docs
url: /ru/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Представляет свойства форматирования маркеров абзаца.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Возвращает или задает тип маркера абзаца без наследования. |
| [setType(byte value)](#setType-byte-) | Возвращает или задает тип маркера абзаца без наследования. |
| [getChar()](#getChar--) | Возвращает или задает символ маркера абзаца без наследования. |
| [setChar(char value)](#setChar-char-) | Возвращает или задает символ маркера абзаца без наследования. |
| [getFont()](#getFont--) | Возвращает или задает шрифт маркера абзаца без наследования. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Возвращает или задает шрифт маркера абзаца без наследования. |
| [getHeight()](#getHeight--) | Возвращает или задает высоту маркера абзаца без наследования. |
| [setHeight(float value)](#setHeight-float-) | Возвращает или задает высоту маркера абзаца без наследования. |
| [getColor()](#getColor--) | Возвращает формат цвета маркера абзаца без наследования. |
| [getPicture()](#getPicture--) | Возвращает изображение, используемое в качестве маркера в абзаце без наследования. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Возвращает или задает стиль нумерованного маркера без наследования. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Возвращает или задает стиль нумерованного маркера без наследования. |
| [isBulletHardColor()](#isBulletHardColor--) | Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. |
| [isBulletHardFont()](#isBulletHardFont--) | Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Устанавливает значения по умолчанию, не равные нулю, для эффективного отступа абзаца (Indent) и левого поля (MarginLeft), когда маркеры включены (как делает PowerPoint при включении маркеров/нумерации абзаца). |
| [getEffective()](#getEffective--) | Получает данные эффективного форматирования маркеров с примененным наследованием. |
### getType() {#getType--}
```
public abstract byte getType()
```


Возвращает или задает тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Возвращает:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Возвращает или задает тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```


Возвращает или задает символ маркера абзаца без наследования. Чтение/запись char.

**Возвращает:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```


Возвращает или задает символ маркера абзаца без наследования. Чтение/запись char.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Возвращает или задает шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```


Возвращает или задает шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Возвращает или задает высоту маркера абзаца без наследования. Значение Float.NaN определяет, что высота маркера наследуется из первой части абзаца. Чтение/запись float.

**Возвращает:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Возвращает или задает высоту маркера абзаца без наследования. Значение Float.NaN определяет, что высота маркера наследуется из первой части абзаца. Чтение/запись float.

**Parameters:**
| Parameter | Type | Description |
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


Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short.

**Возвращает:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```


Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Возвращает или задает стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Возвращает:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```


Возвращает или задает стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```


Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. **NullableBool\#True** если маркер имеет собственный цвет и **NullableBool\#False** если маркер наследует цвет из первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```


Определяет, имеет ли маркер собственный цвет или наследует его из первой части абзаца. **NullableBool\#True** если маркер имеет собственный цвет и **NullableBool\#False** если маркер наследует цвет из первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```


Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. **NullableBool\#True** если маркер имеет собственный шрифт и **NullableBool\#False** если маркер наследует шрифт из первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращает:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```


Определяет, имеет ли маркер собственный шрифт или наследует его из первой части абзаца. **NullableBool\#True** если маркер имеет собственный шрифт и **NullableBool\#False** если маркер наследует шрифт из первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```


Устанавливает значения по умолчанию, не равные нулю, для эффективного отступа абзаца (Indent) и левого поля (MarginLeft), когда маркеры включены (как делает PowerPoint при включении маркеров/нумерации абзаца). Если маркеры отключены, то просто сбрасывает отступ и левое поле (как делает PowerPoint при отключении маркеров/нумерации). Сдвиги отступов применяются с учётом текущего контекста маркера — IBulletFormat.Type, .NumberedBulletStyle и высоты шрифта первой части. Ненулевые сдвиги отступов применяются к эффективному Indent и MarginLeft текущего абзаца (делая результирующие значения локальными).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```


Получает данные эффективного форматирования маркеров с примененным наследованием.

--------------------

> ```
> Этот пример демонстрирует получение некоторых эффективных свойств формата маркера.
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
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).