---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
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
| [getRotationX()](#getRotationX--) | Renvoie ou définit le degré de rotation autour de l'axe X, c’est-à-dire |
| [setRotationX(byte value)](#setRotationX-byte-) | Renvoie ou définit le degré de rotation autour de l'axe X, c’est-à-dire |
| [getRotationY()](#getRotationY--) | Renvoie ou définit le degré de rotation autour de l'axe Y, c’est-à-dire |
| [setRotationY(int value)](#setRotationY-int-) | Renvoie ou définit le degré de rotation autour de l'axe Y, c’est-à-dire |
| [getPerspective()](#getPerspective--) | Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [getDepthPercents()](#getDepthPercents--) | Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [getHeightPercents()](#getHeightPercents--) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Renvoie ou définit le degré de rotation autour de l'axe X, c’est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément rotX (Rotation X) 21.2.2.157 d'ECMA-376 et à l'option « Y Rotation » dans PowerPoint 2007+. Lecture/écriture byte.

**Renvoie :**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Renvoie ou définit le degré de rotation autour de l'axe X, c’est-à-dire dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément rotX (Rotation X) 21.2.2.157 d'ECMA-376 et à l'option « Y Rotation » dans PowerPoint 2007+. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Renvoie ou définit le degré de rotation autour de l'axe Y, c’est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément rotY (Rotation Y) 21.2.2.158 d'ECMA-376 et à l'option « X Rotation » dans PowerPoint 2007+. Lecture/écriture int.

**Renvoie :**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Renvoie ou définit le degré de rotation autour de l'axe Y, c’est-à-dire dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément rotY (Rotation Y) 21.2.2.158 d'ECMA-376 et à l'option « X Rotation » dans PowerPoint 2007+. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). Ignorée si la propriété RightAngleAxes a la valeur true. Lecture/écriture byte.

**Renvoie :**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 100). Ignorée si la propriété RightAngleAxes a la valeur true. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d’autres termes, il détermine si les angles des axes du graphique sont indépendants de la rotation ou de l’élévation du graphique. Lecture/écriture boolean.

**Renvoie :**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d’autres termes, il détermine si les angles des axes du graphique sont indépendants de la rotation ou de l’élévation du graphique. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Renvoie :**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Renvoie :**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |