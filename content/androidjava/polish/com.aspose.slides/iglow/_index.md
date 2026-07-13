---
title: IGlow
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje efekt poświaty, w którym kolorowa rozmyta obwódka jest dodawana poza krawędziami obiektu.
type: docs
url: /pl/com.aspose.slides/iglow/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Reprezentuje efekt poświaty, w którym rozmyta, kolorowa obwódka jest dodawana wokół krawędzi obiektu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Promień. |
| [setRadius(double value)](#setRadius-double-) | Promień. |
| [getColor()](#getColor--) | Format koloru. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Promień. Odczyt/zapis double.

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Promień. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Format koloru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)