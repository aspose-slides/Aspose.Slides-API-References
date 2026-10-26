---
title: IBackground
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje pozadí snímku.
type: docs
url: /cs/com.aspose.slides/ibackground/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Reprezentuje pozadí snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ výplně pozadí. |
| [setType(byte value)](#setType-byte-) | Vrací typ výplně pozadí. |
| [getFillFormat()](#getFillFormat--) | Vrací FillFormat pro výplň BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Vrací EffectFormat pro výplň BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Vrací ColorFormat pro výplň BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. |
| [getEffective()](#getEffective--) | Získává efektivní data pozadí s použitím dědičnosti. |
### getType() {#getType--}
```
public abstract byte getType()
```

Vrací typ výplně pozadí. Číst/zapisovat [BackgroundType](../../com.aspose.slides/backgroundtype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Vrací typ výplně pozadí. Číst/zapisovat [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Vrací FillFormat pro výplň BackgroundType.OwnBackground. Jen pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Vrací EffectFormat pro výplň BackgroundType.OwnBackground. Jen pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Vrací ColorFormat pro výplň BackgroundType.Themed. Jen pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. 0 znamená žádnou výplň. 1..999 - index. Číst/zapisovat int.

**Vrací:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. 0 znamená žádnou výplň. 1..999 - index. Číst/zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Získává efektivní data pozadí s použitím dědičnosti.

**Vrací:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).