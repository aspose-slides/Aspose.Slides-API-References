---
title: IParagraphFormat
second_title: Aspose.Slides for Android через Java API Reference
description: Этот класс содержит свойства форматирования абзаца.
type: docs
url: /ru/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Этот класс содержит свойства форматирования абзаца. В отличие от [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), все свойства этого класса доступны для записи.

--------------------

Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая наследованные, необходимо использовать метод [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective), который возвращает экземпляр [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata). 

## Методы

| Метод | Описание |
| --- | --- |
| [getBullet()](#getBullet--) | Возвращает формат маркера абзаца. |
| [getDepth()](#getDepth--) | Возвращает или задает глубину абзаца. |
| [setDepth(short value)](#setDepth-short-) | Возвращает или задает глубину абзаца. |
| [getAlignment()](#getAlignment--) | Возвращает или задает выравнивание текста в абзаце без наследования. |
| [setAlignment(int value)](#setAlignment-int-) | Возвращает или задает выравнивание текста в абзаце без наследования. |
| [getSpaceWithin()](#getSpaceWithin--) | Возвращает или задает количество пространства между базовыми строками в абзаце. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Возвращает или задает количество пространства между базовыми строками в абзаце. |
| [getSpaceBefore()](#getSpaceBefore--) | Возвращает или задает количество пространства перед первой строкой в абзаце без наследования. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Возвращает или задает количество пространства перед первой строкой в абзаце без наследования. |
| [getSpaceAfter()](#getSpaceAfter--) | Возвращает или задает количество пространства после последней строки в абзаце без наследования. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Возвращает или задает количество пространства после последней строки в абзаце без наследования. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Определяет, используется ли разрыв строки Восточно-азиатского стиля в абзаце. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Определяет, используется ли разрыв строки Восточно-азиатского стиля в абзаце. |
| [getRightToLeft()](#getRightToLeft--) | Определяет, используется ли написание справа налево в абзаце. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Определяет, используется ли написание справа налево в абзаце. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Определяет, используется ли латинский разрыв строки в абзаце. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Определяет, используется ли латинский разрыв строки в абзаце. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Определяет, используется ли «виснущая» пунктуация в абзаце. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Определяет, используется ли «виснущая» пунктуация в абзаце. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает или задает левый отступ в абзаце без наследования. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Возвращает или задает левый отступ в абзаце без наследования. |
| [getMarginRight()](#getMarginRight--) | Возвращает или задает правый отступ в абзаце без наследования. |
| [setMarginRight(float value)](#setMarginRight-float-) | Возвращает или задает правый отступ в абзаце без наследования. |
| [getIndent()](#getIndent--) | Возвращает или задает первый строковый отступ/«виснущий» отступ абзаца без наследования. |
| [setIndent(float value)](#setIndent-float-) | Возвращает или задает первый строковый отступ/«виснущий» отступ абзаца без наследования. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Возвращает или задает размер табуляции по умолчанию без наследования. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Возвращает или задает размер табуляции по умолчанию без наследования. |
| [getTabs()](#getTabs--) | Возвращает табуляции абзаца. |
| [getFontAlignment()](#getFontAlignment--) | Возвращает или задает выравнивание шрифта в абзаце без наследования. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Возвращает или задает выравнивание шрифта в абзаце без наследования. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Возвращает формат части текста по умолчанию абзаца. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования абзаца с учётом наследования. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Возвращает формат маркера абзаца. Только для чтения [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Возвращаемое значение:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Возвращает или задает глубину абзаца. Значение 0 означает неопределённое значение. Чтение/запись short.

**Возвращаемое значение:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Возвращает или задает глубину абзаца. Значение 0 означает неопределённое значение. Чтение/запись short.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Возвращает или задает выравнивание текста в абзаце без наследования. Чтение/запись [TextAlignment](../../com.aspose.slides/textalignment).

**Возвращаемое значение:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Возвращает или задает выравнивание текста в абзаце без наследования. Чтение/запись [TextAlignment](../../com.aspose.slides/textalignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Возвращает или задает количество пространства между базовыми строками в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись float.

**Возвращаемое значение:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Возвращает или задает количество пространства между базовыми строками в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Возвращает или задает количество пространства перед первой строкой в абзаце без наследования. Положительное значение задаёт процент от размера шрифта, которым должно быть пространство; отрицательное значение задаёт размер пространства в пунктах. Чтение/запись float.

**Возвращаемое значение:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Возвращает или задает количество пространства перед первой строкой в абзаце без наследования. Положительное значение задаёт процент от размера шрифта, которым должно быть пространство; отрицательное значение задаёт размер пространства в пунктах. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Возвращает или задает количество пространства после последней строки в абзаце без наследования. Положительное значение задаёт процент от размера шрифта, которым должно быть пространство; отрицательное значение задаёт размер пространства в пунктах. Чтение/запись float.

**Возвращаемое значение:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Возвращает или задает количество пространства после последней строки в абзаце без наследования. Положительное значение задаёт процент от размера шрифта, которым должно быть пространство; отрицательное значение задаёт размер пространства в пунктах. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Определяет, используется ли разрыв строки Восточно-азиатского стиля в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Определяет, используется ли разрыв строки Восточно-азиатского стиля в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Определяет, используется ли латинский разрыв строки в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Определяет, используется ли латинский разрыв строки в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Определяет, используется ли «виснущая» пунктуация в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Определяет, используется ли «виснущая» пунктуация в абзаце. Наследование не применяется. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Возвращает или задает левый отступ в абзаце без наследования. Чтение/запись float.

**Возвращаемое значение:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Возвращает или задает левый отступ в абзаце без наследования. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Возвращает или задает правый отступ в абзаце без наследования. Чтение/запись float.

**Возвращаемое значение:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Возвращает или задает правый отступ в абзаце без наследования. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Возвращает или задает первый строковый отступ/«виснущий» отступ абзаца без наследования. «Виснущий» отступ может быть задан отрицательными значениями. Чтение/запись float.

**Возвращаемое значение:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Возвращает или задает первый строковый отступ/«виснущий» отступ абзаца без наследования. «Виснущий» отступ может быть задан отрицательными значениями. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Возвращает или задает размер табуляции по умолчанию без наследования. Чтение/запись float.

**Возвращаемое значение:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Возвращает или задает размер табуляции по умолчанию без наследования. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [ITabCollection](../../com.aspose.slides/itabcollection).

**Возвращаемое значение:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Возвращает или задает выравнивание шрифта в абзаце без наследования. Чтение/запись [FontAlignment](../../com.aspose.slides/fontalignment).

**Возвращаемое значение:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Возвращает или задает выравнивание шрифта в абзаце без наследования. Чтение/запись [FontAlignment](../../com.aspose.slides/fontalignment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Возвращает формат части текста по умолчанию абзаца. Наследование не применяется. Только для чтения [IPortionFormat](../../com.aspose.slides/iportionformat).

**Возвращаемое значение:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования абзаца с учётом наследования.

**Возвращаемое значение:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).