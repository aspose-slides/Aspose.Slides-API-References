---
title: IRotation3D
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de 3D-rotatie van een diagram voor.
type: docs
url: /nl/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Stelt de 3D-rotatie van een diagram voor.
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getRotationX()](#getRotationX--) | Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. |
| [setRotationX(byte value)](#setRotationX-byte-) | Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. |
| [getRotationY()](#getRotationY--) | Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. |
| [setRotationY(int value)](#setRotationY-int-) | Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. |
| [getPerspective()](#getPerspective--) | Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen terug of stelt deze in (tussen 0 en 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen terug of stelt deze in (tussen 0 en 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bepaalt of de diagramassen recht hoeken vormen in plaats van in perspectief getekend te worden. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bepaalt of de diagramassen recht hoeken vormen in plaats van in perspectief getekend te worden. |
| [getDepthPercents()](#getDepthPercents--) | Geeft de diepte van een 3D-diagram als een percentage van de diagrambreedte terug of stelt deze in (tussen 20 en 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Geeft de diepte van een 3D-diagram als een percentage van de diagrambreedte terug of stelt deze in (tussen 20 en 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.2.157 rotX (X Rotation) in ECMA-376 en met de optie "Y Rotation" in PowerPoint 2007+. Lezen/schrijven byte.

**Retour:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Geeft de rotatiegraad rond de X-as terug of stelt deze in, d.w.z. in de Y-richting voor 3D-diagrammen (tussen -90 en 90 graden). De eigenschap komt overeen met het item 21.2.157 rotX (X Rotation) in ECMA-376 en met de optie "Y Rotation" in PowerPoint 2007+. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y Rotation) in ECMA-376 en met de optie "X Rotation" in PowerPoint 2007+. Lezen/schrijven int.

**Retour:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Geeft de rotatiegraad rond de Y-as terug of stelt deze in, d.w.z. in de X-richting voor 3D-diagrammen (tussen 0 en 360 graden). De eigenschap komt overeen met het item 21.2.2.158 rotY (Y Rotation) in ECMA-376 en met de optie "X Rotation" in PowerPoint 2007+. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen terug of stelt deze in (tussen 0 en 100). Genegeerd als de eigenschap RightAngleAxes waar is. Lezen/schrijven byte.

**Retour:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Geeft de perspectiefwaarde (zichtveldhoek) voor 3D-diagrammen terug of stelt deze in (tussen 0 en 100). Genegeerd als de eigenschap RightAngleAxes waar is. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Bepaalt of de diagramassen recht hoeken vormen in plaats van in perspectief getekend te worden. Met andere woorden, bepaalt of de hoeken van de as onafhankelijk zijn van rotatie of elevatie van het diagram. Lezen/schrijven boolean.

**Retour:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Bepaalt of de diagramassen recht hoeken vormen in plaats van in perspectief getekend te worden. Met andere woorden, bepaalt of de hoeken van de as onafhankelijk zijn van rotatie of elevatie van het diagram. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Geeft de diepte van een 3D-diagram als een percentage van de diagrambreedte terug of stelt deze in (tussen 20 en 2000 procent). Lezen/schrijven int.

**Retour:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Geeft de diepte van een 3D-diagram als een percentage van de diagrambreedte terug of stelt deze in (tussen 20 en 2000 procent). Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Lezen/schrijven int.

**Retour:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Specificeert de hoogte van een 3-D-diagram als een percentage van de diagrambreedte (tussen 5 en 500 procent). Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |