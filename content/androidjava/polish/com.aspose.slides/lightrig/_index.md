---
title: LightRig
second_title: Aspose.Slides for Android - odniesienie API Java
description: Reprezentuje LightRig.
type: docs
url: /pl/com.aspose.slides/lightrig/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Reprezentuje LightRig.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Kierunek światła. |
| [setDirection(int value)](#setDirection-int-) | Kierunek światła. |
| [getLightType()](#getLightType--) | Reprezentuje wstępnie ustawione światło po prawej, które może być zastosowane do kształtu. |
| [setLightType(int value)](#setLightType-int-) | Reprezentuje wstępnie ustawione światło po prawej, które może być zastosowane do kształtu. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

Kierunek światła. Odczyt/zapis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Zwraca:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

Kierunek światła. Odczyt/zapis [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Reprezentuje wstępnie ustawione światło po prawej, które może być zastosowane do kształtu. Light rig reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Zwraca:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Reprezentuje wstępnie ustawione światło po prawej, które może być zastosowane do kształtu. Light rig reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. Jeśli jakakolwiek wartość współrzędnej jest Float.NaN, cała rotacja jest niezdefiniowana.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót. Zwraca null, jeśli nie zdefiniowano rotacji.

**Zwraca:**
float[]