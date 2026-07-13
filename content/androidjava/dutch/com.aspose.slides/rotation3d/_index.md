---
title: Rotation3D
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt 3D-rotatie van een grafiek voor.
type: docs
url: /nl/com.aspose.slides/rotation3d/
---
**Erfelijkheid:**
java.lang.Object

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Stelt 3D-rotatie van een grafiek voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRotationX()](#getRotationX--) | Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. |
| [setRotationX(byte value)](#setRotationX-byte-) | Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. |
| [getRotationY()](#getRotationY--) | Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. |
| [setRotationY(int value)](#setRotationY-int-) | Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. |
| [getPerspective()](#getPerspective--) | Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-grafieken terug of stelt deze in (tussen 0 en 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-grafieken terug of stelt deze in (tussen 0 en 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bepaalt of de grafiekassen onder rechte hoeken staan, in plaats van in perspectief getekend te worden. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bepaalt of de grafiekassen onder rechte hoeken staan, in plaats van in perspectief getekend te worden. |
| [getDepthPercents()](#getDepthPercents--) | Geeft de diepte van een 3D-grafiek als percentage van de grafiekbreedte terug of stelt deze in (tussen 20 en 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Geeft de diepte van een 3D-grafiek als percentage van de grafiekbreedte terug of stelt deze in (tussen 20 en 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Bepaalt de hoogte van een 3-D-grafiek als percentage van de grafiekbreedte (tussen 5 en 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Bepaalt de hoogte van een 3-D-grafiek als percentage van de grafiekbreedte (tussen 5 en 500 procent). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```


Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. in de Y-richting voor 3D-grafieken (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X Rotation) in ECMA-376 en met de “Y Rotation”-optie in PowerPoint 2007+. Lezen/Schrijven byte.

**Retour:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```


Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. in de Y-richting voor 3D-grafieken (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.157 rotX (X Rotation) in ECMA-376 en met de “Y Rotation”-optie in PowerPoint 2007+. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```


Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. in de X-richting voor 3D-grafieken (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y Rotation) in ECMA-376 en met de “X Rotation”-optie in PowerPoint 2007+. Lezen/Schrijven int.

**Retour:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```


Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. in de X-richting voor 3D-grafieken (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y Rotation) in ECMA-376 en met de “X Rotation”-optie in PowerPoint 2007+. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```


Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-grafieken terug of stelt deze in (tussen 0 en 240). Wordt genegeerd wanneer de eigenschap RightAngleAxes de waarde true heeft. Lezen/Schrijven byte.

**Retour:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```


Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-grafieken terug of stelt deze in (tussen 0 en 240). Wordt genegeerd wanneer de eigenschap RightAngleAxes de waarde true heeft. Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```


Bepaalt of de grafiekassen onder rechte hoeken staan, in plaats van in perspectief getekend te worden. Met andere woorden, bepaalt of de hoeken van de assen onafhankelijk zijn van de rotatie of elevatie van de grafiek. Lezen/Schrijven boolean.

**Retour:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```


Bepaalt of de grafiekassen onder rechte hoeken staan, in plaats van in perspectief getekend te worden. Met andere woorden, bepaalt of de hoeken van de assen onafhankelijk zijn van de rotatie of elevatie van de grafiek. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```


Geeft de diepte van een 3D-grafiek als percentage van de grafiekbreedte terug of stelt deze in (tussen 20 en 2000 procent). Lezen/Schrijven int.

**Retour:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```


Geeft de diepte van een 3D-grafiek als percentage van de grafiekbreedte terug of stelt deze in (tussen 20 en 2000 procent). Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```


Bepaalt de hoogte van een 3-D-grafiek als percentage van de grafiekbreedte (tussen 5 en 500 procent). Lezen/Schrijven int.

**Retour:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```


Bepaalt de hoogte van een 3-D-grafiek als percentage van de grafiekbreedte (tussen 5 en 500 procent). Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject