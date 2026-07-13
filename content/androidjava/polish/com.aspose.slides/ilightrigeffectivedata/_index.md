---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /pl/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Obiekt niezmienny zawierający efektywne właściwości układu oświetlenia.

--------------------

Ten interfejs jest używany jako część [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek światła. |
| [getLightType()](#getLightType--) | Reprezentuje wstępnie ustawione światło prawostronne, które można zastosować do kształtu. |
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


Reprezentuje wstępnie ustawione światło prawostronne, które można zastosować do kształtu. Układ oświetlenia reprezentuje grupę świateł ustawioną w określony sposób względem sceny 3D. Tylko do odczytu [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Zwraca:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Rotacja jest definiowana przy użyciu współrzędnej szerokości, współrzędnej długości oraz obrotu wokół osi jako współrzędnych szerokości i długości. Pierwszy element w zwracanej tablicy – szerokość, drugi – długość, trzeci – obrót.

**Zwraca:**
float[] - Współrzędne rotacji jako float[]