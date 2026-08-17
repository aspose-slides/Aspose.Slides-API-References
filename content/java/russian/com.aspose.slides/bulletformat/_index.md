---
title: BulletFormat
second_title: Aspose.Slides для Java: справочник API
description: Представляет свойства форматирования маркеров абзаца.
type: docs
url: /ru/com.aspose.slides/bulletformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
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
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Возвращает или задает стиль нумерованного маркера без наследования. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Возвращает или задает стиль нумерованного маркера без наследования. |
| [isBulletHardColor()](#isBulletHardColor--) | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. |
| [isBulletHardFont()](#isBulletHardFont--) | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. |
| [getPicture()](#getPicture--) | Возвращает изображение, используемое в качестве маркера в абзаце без наследования. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Устанавливает смещения по умолчанию, отличные от нуля, для эффективного отступа абзаца и MarginLeft, когда маркеры включены (как PowerPoint делает при включении маркеров/нумерации абзацев). |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования маркера с учётом наследования. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Возвращает или задает тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Возвращаемое значение:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Возвращает или задает тип маркера абзаца без наследования. Чтение/запись [BulletType](../../com.aspose.slides/bullettype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Возвращает или задает символ маркера абзаца без наследования. Чтение/запись char .

**Возвращаемое значение:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Возвращает или задает символ маркера абзаца без наследования. Чтение/запись char .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Возвращает или задает шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Возвращает или задает шрифт маркера абзаца без наследования. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Возвращает или задает высоту маркера абзаца без наследования. Значение Float.NaN определяет, что маркер наследует высоту от первой части абзаца. Чтение/запись float .

**Возвращаемое значение:**
float

Отрицательное значение высоты означает, что высота указана в пунктах, а положительное значение означает, что высота задаётся в процентах от окружающего текста.

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Возвращает или задает высоту маркера абзаца без наследования. Значение Float.NaN определяет, что маркер наследует высоту от первой части абзаца. Чтение/запись float .

Отрицательное значение высоты означает, что высота указана в пунктах, а положительное значение означает, что высота задаётся в процентах от окружающего текста.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Возвращает формат цвета маркера абзаца без наследования. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short .

**Возвращаемое значение:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Возвращает или задает первое число, используемое для группы нумерованных маркеров без наследования. Чтение/запись short .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Возвращает или задает стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Возвращаемое значение:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Возвращает или задает стиль нумерованного маркера без наследования. Чтение/запись [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. **NullableBool.True** если маркер имеет собственный цвет и **NullableBool.False** если маркер наследует цвет от первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. **NullableBool.True** если маркер имеет собственный цвет и **NullableBool.False** если маркер наследует цвет от первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. **NullableBool.True** если маркер имеет собственный шрифт и **NullableBool.False** если маркер наследует шрифт от первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. **NullableBool.True** если маркер имеет собственный шрифт и **NullableBool.False** если маркер наследует шрифт от первой части абзаца. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Возвращает изображение, используемое в качестве маркера в абзаце без наследования. Только для чтения [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Возвращаемое значение:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Устанавливает смещения по умолчанию, отличные от нуля, для эффективного отступа абзаца и MarginLeft, когда маркеры включены (как PowerPoint делает при включении маркеров/нумерации абзацев). Если маркеры отключены, то просто сбрасывает отступ абзаца и MarginLeft (как PowerPoint делает при отключении маркеров/нумерации абзацев). Смещения отступов применяются относительно текущего контекста маркера — IBulletFormat.Type, .NumberedBulletStyle и FontHeight первой части. Ненулевые смещения отступов применяются к эффективному Indent и MarginLeft текущего абзаца (делая полученные значения локальными).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования маркера с учётом наследования.

> ```
> This example demonstrates getting some effective bullet format properties.
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


**Возвращаемое значение:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) — [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**
long