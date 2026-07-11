---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides для Android через Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства форматирования абзаца.
type: docs
url: /ru/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства форматирования абзаца.

--------------------

Этот интерфейс используется совместно с интерфейсом [IParagraphFormat](../../com.aspose.slides/iparagraphformat) для возврата эффективных значений форматирования с учётом наследования.

## Методы

| Метод | Описание |
| --- | --- |
| [getBullet()](#getBullet--) | Возвращает формат маркера абзаца. |
| [getDepth()](#getDepth--) | Возвращает глубину абзаца. |
| [getAlignment()](#getAlignment--) | Возвращает выравнивание текста в абзаце. |
| [getSpaceWithin()](#getSpaceWithin--) | Возвращает количество пространства между базовыми строками в абзаце. |
| [getSpaceBefore()](#getSpaceBefore--) | Возвращает количество пространства перед первой строкой в абзаце. |
| [getSpaceAfter()](#getSpaceAfter--) | Возвращает количество пространства после последней строки в абзаце. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. |
| [getRightToLeft()](#getRightToLeft--) | Определяет, используется ли написание справа налево в абзаце. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Определяет, используется ли разрыв строки латинского типа в абзаце. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Определяет, используется ли висячая пунктуация в абзаце. |
| [getMarginLeft()](#getMarginLeft--) | Возвращает левый отступ в абзаце. |
| [getMarginRight()](#getMarginRight--) | Возвращает правый отступ в абзаце. |
| [getIndent()](#getIndent--) | Возвращает отступ первой строки/висячий отступ абзаца. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Возвращает размер табуляции по умолчанию. |
| [getTabs()](#getTabs--) | Возвращает табуляции абзаца. |
| [getFontAlignment()](#getFontAlignment--) | Возвращает выравнивание шрифта в абзаце. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Возвращает формат части по умолчанию в абзаце. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Возвращает формат маркера абзаца. Только для чтения [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Возвращаемое значение:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Возвращает глубину абзаца. Только для чтения short.

**Возвращаемое значение:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Возвращает выравнивание текста в абзаце. Только для чтения [TextAlignment](../../com.aspose.slides/textalignment).

**Возвращаемое значение:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Возвращает количество пространства между базовыми строками в абзаце. Только для чтения float.

**Возвращаемое значение:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Возвращает количество пространства перед первой строкой в абзаце. Только для чтения float.

**Возвращаемое значение:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Возвращает количество пространства после последней строки в абзаце. Только для чтения float.

**Возвращаемое значение:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Определяет, используется ли разрыв строки восточноазиатского типа в абзаце. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Определяет, используется ли написание справа налево в абзаце. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Определяет, используется ли разрыв строки латинского типа в абзаце. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Определяет, используется ли висячая пунктуация в абзаце. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Возвращает левый отступ в абзаце. Только для чтения float.

**Возвращаемое значение:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Возвращает правый отступ в абзаце. Только для чтения float.

**Возвращаемое значение:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Возвращает отступ первой строки/висячий отступ абзаца. Висячий отступ может быть задан отрицательными значениями. Только для чтения float.

**Возвращаемое значение:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Возвращает размер табуляции по умолчанию. Только для чтения float.

**Возвращаемое значение:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Возвращает табуляции абзаца. Только для чтения ITabEffectiveData[].

**Возвращаемое значение:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Возвращает выравнивание шрифта в абзаце. Только для чтения [FontAlignment](../../com.aspose.slides/fontalignment).

**Возвращаемое значение:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Возвращает формат части по умолчанию в абзаце. Только для чтения [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Возвращаемое значение:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)