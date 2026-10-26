---
title: IBackground
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje tło slajdu.
type: docs
url: /pl/com.aspose.slides/ibackground/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Reprezentuje tło slajdu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca typ wypełnienia tła. |
| [setType(byte value)](#setType-byte-) | Zwraca typ wypełnienia tła. |
| [getFillFormat()](#getFillFormat--) | Zwraca FillFormat dla wypełnienia BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Zwraca EffectFormat dla wypełnienia BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Zwraca ColorFormat dla wypełnienia BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane tła z zastosowanym dziedziczeniem. |
### getType() {#getType--}
```
public abstract byte getType()
```


Zwraca typ wypełnienia tła. Odczyt/zapis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Zwraca:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Zwraca typ wypełnienia tła. Odczyt/zapis [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Zwraca FillFormat dla wypełnienia BackgroundType.OwnBackground. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Zwraca EffectFormat dla wypełnienia BackgroundType.OwnBackground. Tylko do odczytu [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Zwraca:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Zwraca ColorFormat dla wypełnienia BackgroundType.Themed. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. 0 oznacza brak wypełnienia. 1..999 – indeks. Odczyt/zapis int.

**Zwraca:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Zwraca indeks wypełnienia BackgroundType.Themed w kolekcji motywów tła. 0 oznacza brak wypełnienia. 1..999 – indeks. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Pobiera efektywne dane tła z zastosowanym dziedziczeniem.

**Zwraca:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).