---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la rotation 3D d'un graphique.
type: docs
url: /fr/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Représente la rotation 3D d'un graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Retourne ou définit le degré de rotation autour de l'axe X, c'est-à-dire |
| [setRotationX(byte value)](#setRotationX-byte-) | Retourne ou définit le degré de rotation autour de l'axe X, c'est-à-dire |
| [getRotationY()](#getRotationY--) | Retourne ou définit le degré de rotation autour de l'axe Y, c'est-à-dire |
| [setRotationY(int value)](#setRotationY-int-) | Retourne ou définit le degré de rotation autour de l'axe Y, c'est-à-dire |
| [getPerspective()](#getPerspective--) | Retourne ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Retourne ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [getDepthPercents()](#getDepthPercents--) | Retourne ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Retourne ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [getHeightPercents()](#getHeightPercents--) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Retourne ou définit le degré de rotation autour de l'axe X, c'est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (X Rotation) dans ECMA-376 et à l'option "Y Rotation" dans PowerPoint 2007+. Lecture/écriture byte.

**Retourne :**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Retourne ou définit le degré de rotation autour de l'axe X, c'est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (X Rotation) dans ECMA-376 et à l'option "Y Rotation" dans PowerPoint 2007+. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Retourne ou définit le degré de rotation autour de l'axe Y, c'est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Y Rotation) dans ECMA-376 et à l'option "X Rotation" dans PowerPoint 2007+. Lecture/écriture int.

**Retourne :**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Retourne ou définit le degré de rotation autour de l'axe Y, c'est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Y Rotation) dans ECMA-376 et à l'option "X Rotation" dans PowerPoint 2007+. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Retourne ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). Ignoré si la propriété RightAngleAxes vaut vrai. Lecture/écriture byte.

**Retourne :**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Retourne ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). Ignoré si la propriété RightAngleAxes vaut vrai. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d’autres termes, cela détermine si les angles des axes sont indépendants de la rotation ou de l’élévation du graphique. Lecture/écriture boolean.

**Retourne :**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d’autres termes, cela détermine si les angles des axes sont indépendants de la rotation ou de l’élévation du graphique. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Retourne ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Retourne :**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Retourne ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Spécifie la hauteur d'un graphique 3-D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Retourne :**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Spécifie la hauteur d'un graphique 3-D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |