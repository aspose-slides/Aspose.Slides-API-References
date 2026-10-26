---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje LightRig.
type: docs
url: /pl/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Reprezentuje LightRig.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek światła. |
| [setDirection(int value)](#setDirection-int-) | Kierunek światła. |
| [getLightType()](#getLightType--) | Reprezentuje wstępnie ustawione światło po prawej, które można zastosować do kształtu. |
| [setLightType(int value)](#setLightType-int-) | Reprezentuje wstępnie ustawione światło po prawej, które można zastosować do kształtu. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi, przy czym współrzędne szerokości i długości są używane. |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi, przy czym współrzędne szerokości i długości są używane. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Kierunek światła. Odczyt/zapis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Zwraca:**
int

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Kierunek światła. Odczyt/zapis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Reprezentuje wstępnie ustawione światło po prawej, które można zastosować do kształtu. System oświetlenia reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Zwraca:**
int

### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Reprezentuje wstępnie ustawione światło po prawej, które można zastosować do kształtu. System oświetlenia reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi, przy czym współrzędne szerokości i długości są używane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| latitude | float | Współrzędna szerokości typu float |
| longitude | float | Współrzędna długości typu float |
| revolution | float | Współrzędna obrotu typu float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi, przy czym współrzędne szerokości i długości są używane. pierwszy element w tablicy zwracanej - szerokość, drugi - długość, trzeci - obrót.

**Zwraca:**
float[] - współrzędne rotacji jako float[]