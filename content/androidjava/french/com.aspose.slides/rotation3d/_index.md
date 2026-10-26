---
title: Rotation3D
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente la rotation 3D d'un graphique.
type: docs
url: /fr/com.aspose.slides/rotation3d/
---
**Héritage:**  
java.lang.Object  

**Toutes les Interfaces Implémentées:**  
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject  
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Représente la rotation 3D d'un graphique.  

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Renvoie ou définit le degré de rotation autour de l'axe X, c.-à-d. |
| [setRotationX(byte value)](#setRotationX-byte-) | Renvoie ou définit le degré de rotation autour de l'axe X, c.-à-d. |
| [getRotationY()](#getRotationY--) | Renvoie ou définit le degré de rotation autour de l'axe Y, c.-à-d. |
| [setRotationY(int value)](#setRotationY-int-) | Renvoie ou définit le degré de rotation autour de l'axe Y, c.-à-d. |
| [getPerspective()](#getPerspective--) | Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. |
| [getDepthPercents()](#getDepthPercents--) | Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). |
| [getHeightPercents()](#getHeightPercents--) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Renvoie ou définit le degré de rotation autour de l'axe X, c.-à-d. dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (X Rotation) de la norme ECMA-376 et à l'option \"Y Rotation\" de PowerPoint 2007+. Lecture/écriture byte.

**Renvoie:**  
byte  

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Renvoie ou définit le degré de rotation autour de l'axe X, c.-à-d. dans la direction Y pour les graphiques 3D (entre -90 et 90 degrés). La propriété correspond à l'élément 21.2.2.157 rotX (X Rotation) de la norme ECMA-376 et à l'option \"Y Rotation\" de PowerPoint 2007+. Lecture/écriture byte.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Renvoie ou définit le degré de rotation autour de l'axe Y, c.-à-d. dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Y Rotation) de la norme ECMA-376 et à l'option \"X Rotation\" de PowerPoint 2007+. Lecture/écriture int.

**Renvoie:**  
int  

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Renvoie ou définit le degré de rotation autour de l'axe Y, c.-à-d. dans la direction X pour les graphiques 3D (entre 0 et 360 degrés). La propriété correspond à l'élément 21.2.2.158 rotY (Y Rotation) de la norme ECMA-376 et à l'option \"X Rotation\" de PowerPoint 2007+. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). Ignoré si la propriété RightAngleAxes est vraie. Lecture/écriture byte.

**Renvoie:**  
byte  

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Renvoie ou définit la valeur de perspective (angle de champ de vision) pour les graphiques 3D (entre 0 et 240). Ignoré si la propriété RightAngleAxes est vraie. Lecture/écriture byte.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d'autres termes, cela indique si les angles des axes sont indépendants de la rotation ou de l'élévation du graphique. Lecture/écriture boolean.

**Renvoie:**  
boolean  

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Détermine si les axes du graphique sont à angle droit, plutôt que dessinés en perspective. En d'autres termes, cela indique si les angles des axes sont indépendants de la rotation ou de l'élévation du graphique. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Renvoie:**  
int  

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Renvoie ou définit la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2000 %). Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Renvoie:**  
int  

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Spécifie la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 %). Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**  
com.aspose.slides.IDOMObject