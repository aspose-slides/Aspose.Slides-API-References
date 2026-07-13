---
title: IColorEffect
second_title: Aspose.Slides dla Androida – Dokumentacja API Java
description: Reprezentuje efekt koloru dla zachowania animacji.
type: docs
url: /pl/com.aspose.slides/icoloreffect/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Reprezentuje efekt koloru dla zachowania animacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFrom()](#getFrom--) | Ta wartość jest używana do określenia początkowego koloru zachowania. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Ta wartość jest używana do określenia początkowego koloru zachowania. |
| [getTo()](#getTo--) | Opisuje wynikowy kolor dla zmiany koloru animacji. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Opisuje wynikowy kolor dla zmiany koloru animacji. |
| [getBy()](#getBy--) | Opisuje względną wartość offsetu dla animacji koloru. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Opisuje względną wartość offsetu dla animacji koloru. |
| [getColorSpace()](#getColorSpace--) | Reprezentuje przestrzeń barw zachowania. |
| [setColorSpace(int value)](#setColorSpace-int-) | Reprezentuje przestrzeń barw zachowania. |
| [getDirection()](#getDirection--) | Określa, w którym kierunku obracać odcień wokół koła kolorów. |
| [setDirection(int value)](#setDirection-int-) | Określa, w którym kierunku obracać odcień wokół koła kolorów. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

Ta wartość jest używana do określenia początkowego koloru zachowania. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

Ta wartość jest używana do określenia początkowego koloru zachowania. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

Opisuje wynikowy kolor dla zmiany koloru animacji. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

Opisuje wynikowy kolor dla zmiany koloru animacji. Odczyt/zapis [IColorFormat](../../com.aspose.slides/icolorformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

Opisuje względną wartość offsetu dla animacji koloru. Odczyt/zapis [IColorOffset](../../com.aspose.slides/icoloroffset).

**Zwraca:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

Opisuje względną wartość offsetu dla animacji koloru. Odczyt/zapis [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

Reprezentuje przestrzeń barw zachowania. Odczyt/zapis [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Zwraca:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

Reprezentuje przestrzeń barw zachowania. Odczyt/zapis [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Określa, w którym kierunku obracać odcień wokół koła kolorów. Odczyt/zapis [ColorDirection](../../com.aspose.slides/colordirection).

**Zwraca:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Określa, w którym kierunku obracać odcień wokół koła kolorów. Odczyt/zapis [ColorDirection](../../com.aspose.slides/colordirection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |