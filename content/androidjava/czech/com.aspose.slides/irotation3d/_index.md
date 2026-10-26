---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje 3D rotaci grafu.
type: docs
url: /cs/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Reprezentuje 3D rotaci grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRotationX()](#getRotationX--) | Vrací nebo nastavuje úhel rotace kolem osy X, tj. |
| [setRotationX(byte value)](#setRotationX-byte-) | Vrací nebo nastavuje úhel rotace kolem osy X, tj. |
| [getRotationY()](#getRotationY--) | Vrací nebo nastavuje úhel rotace kolem osy Y, tj. |
| [setRotationY(int value)](#setRotationY-int-) | Vrací nebo nastavuje úhel rotace kolem osy Y, tj. |
| [getPerspective()](#getPerspective--) | Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Určuje, zda jsou osy grafu pravouhlé, místo aby byly vykresleny v perspektivě. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Určuje, zda jsou osy grafu pravouhlé, místo aby byly vykresleny v perspektivě. |
| [getDepthPercents()](#getDepthPercents--) | Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Určuje výšku 3D grafu jako procento šířky grafu (mezi 5 a 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Určuje výšku 3D grafu jako procento šířky grafu (mezi 5 a 500 procent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Vrací nebo nastavuje úhel rotace kolem osy X, tj. ve směru osy Y pro 3D grafy (mezi -90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a možnosti „Y Rotation“ v PowerPoint 2007+. Čtení / zápis byte.

**Vrací:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Vrací nebo nastavuje úhel rotace kolem osy X, tj. ve směru osy Y pro 3D grafy (mezi -90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a možnosti „Y Rotation“ v PowerPoint 2007+. Čtení / zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Vrací nebo nastavuje úhel rotace kolem osy Y, tj. ve směru osy X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.158 rotY (Y Rotation) v ECMA-376 a možnosti „X Rotation“ v PowerPoint 2007+. Čtení / zápis int.

**Vrací:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Vrací nebo nastavuje úhel rotace kolem osy Y, tj. ve směru osy X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.158 rotY (Y Rotation) v ECMA-376 a možnosti „X Rotation“ v PowerPoint 2007+. Čtení / zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 100). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čtení / zápis byte.

**Vrací:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Vrací nebo nastavuje hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 100). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čtení / zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Určuje, zda jsou osy grafu pravouhlé, místo aby byly vykresleny v perspektivě. Jinak řečeno, určuje, zda jsou úhly os grafu nezávislé na rotaci nebo elevaci grafu. Čtení / zápis boolean.

**Vrací:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Určuje, zda jsou osy grafu pravouhlé, místo aby byly vykresleny v perspektivě. Jinak řečeno, určuje, zda jsou úhly os grafu nezávislé na rotaci nebo elevaci grafu. Čtení / zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). Čtení / zápis int.

**Vrací:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Vrací nebo nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procent). Čtení / zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Určuje výšku 3D grafu jako procento šířky grafu (mezi 5 a 500 procent). Čtení / zápis int.

**Vrací:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Určuje výšku 3D grafu jako procento šířky grafu (mezi 5 a 500 procent). Čtení / zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |