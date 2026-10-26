---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości rigu świetlnego.
type: docs
url: /pl/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości rigu świetlnego.

--------------------

Ten interfejs jest używany jako część [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek światła. |
| [getLightType()](#getLightType--) | Reprezentuje wstępnie ustawione światło, które może być zastosowane do kształtu. |
| [getRotation()](#getRotation--) | Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Kierunek światła. Tylko do odczytu [LightingDirection](../../com.aspose.slides/lightingdirection).

**Zwraca:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Reprezentuje wstępnie ustawione światło, które może być zastosowane do kształtu. Zestaw świateł reprezentuje grupę świateł skierowanych w określony sposób względem sceny 3D. Tylko do odczytu [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Zwraca:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości i obrotu wokół osi jako współrzędnych szerokości i długości. Pierwszy element w zwracanej tablicy - szerokość, drugi - długość, trzeci - obrót.

**Zwraca:**
float[] - współrzędne rotacji jako float[]