---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
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
| [getLightType()](#getLightType--) | Reprezentuje przedsdefiniowane światło po prawej, które może zostać zastosowane do kształtu. |
| [setLightType(int value)](#setLightType-int-) | Reprezentuje przedsdefiniowane światło po prawej, które może zostać zastosowane do kształtu. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Rotacja jest określana przy użyciu współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
| [getRotation()](#getRotation--) | Rotacja jest określana przy użyciu współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. |
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

Reprezentuje przedsdefiniowane światło po prawej, które może zostać zastosowane do kształtu. light rig reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Zwraca:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Reprezentuje przedsdefiniowane światło po prawej, które może zostać zastosowane do kształtu. light rig reprezentuje grupę świateł ustawionych w określony sposób względem sceny 3D. Odczyt/zapis [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Rotacja jest określana przy użyciu współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| latitude | float | Współrzędna szerokości geograficznej typu float |
| longitude | float | Współrzędna długości geograficznej typu float |
| revolution | float | Współrzędna obrotu typu float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotacja jest określana przy użyciu współrzędnej szerokości geograficznej, współrzędnej długości geograficznej oraz obrotu wokół osi jako współrzędnych szerokości i długości. pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót.

**Zwraca:**
float[] - Współrzędne rotacji jako float[]