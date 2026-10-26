---
title: Rotation3D
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje 3D rotaci grafu.
type: docs
url: /cs/com.aspose.slides/rotation3d/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Představuje 3D rotaci grafu.
## Metody

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Vrací nebo nastavuje úhel rotace kolem osy X, tj. |
| [setRotationX(byte value)](#setRotationX-byte-) | Vrací nebo nastavuje úhel rotace kolem osy X, tj. |
| [getRotationY()](#getRotationY--) | Vrací nebo nastavuje úhel rotace kolem osy Y, tj. |
| [setRotationY(int value)](#setRotationY-int-) | Vrací nebo nastavuje úhel rotace kolem osy Y, tj. |
| [getPerspective()](#getPerspective--) | Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Určuje, zda jsou osy grafu pravé úhly, místo aby byly vykresleny v perspektivě. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Určuje, zda jsou osy grafu pravé úhly, místo aby byly vykresleny v perspektivě. |
| [getDepthPercents()](#getDepthPercents--) | Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procent). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Vrací nebo nastavuje úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi -90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a možnosti „Y Rotation“ v PowerPoint 2007+. Čtení/zápis byte.

**Vrací:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Vrací nebo nastavuje úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi -90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a možnosti „Y Rotation“ v PowerPoint 2007+. Čtení/zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Vrací nebo nastavuje úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.2.158 rotY (Y Rotation) v ECMA-376 a možnosti „X Rotation“ v PowerPoint 2007+. Čtení/zápis int.

**Vrací:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Vrací nebo nastavuje úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.158 rotY (Y Rotation) v ECMA-376 a možnosti „X Rotation“ v PowerPoint 2007+. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čtení/zápis byte.

**Vrací:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čtení/zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Určuje, zda jsou osy grafu pravé úhly, místo aby byly vykresleny v perspektivě. Jinými slovy určuje, zda jsou úhly os nezávislé na rotaci nebo nadzvednutí grafu. Čtení/zápis boolean.

**Vrací:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Určuje, zda jsou osy grafu pravé úhly, místo aby byly vykresleny v perspektivě. Jinými slovy určuje, zda jsou úhly os nezávislé na rotaci nebo nadzvednutí grafu. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). Čtení/zápis int.

**Vrací:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procent). Čtení/zápis int.

**Vrací:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procent). Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject