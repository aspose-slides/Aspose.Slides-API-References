---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a gradient format.
type: docs
url: /pl/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Reprezentuje format gradientu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję (0..1) punktu gradientu. |
| [setPosition(float value)](#setPosition-float-) | Zwraca lub ustawia pozycję (0..1) punktu gradientu. |
| [getColor()](#getColor--) | Zwraca kolor punktu gradientu. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Zwraca lub ustawia pozycję (0..1) punktu gradientu. Odczyt/zapis float.

**Zwraca:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Zwraca lub ustawia pozycję (0..1) punktu gradientu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Zwraca kolor punktu gradientu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)