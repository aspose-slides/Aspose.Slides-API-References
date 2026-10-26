---
title: SmartArtNode
second_title: Référence API Java pour Aspose.Slides pour Android
description: Représente un nœud d'un objet SmartArt
type: docs
url: /fr/com.aspose.slides/smartartnode/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Représente un nœud d'un objet SmartArt
## Méthodes

| Méthode | Description |
|---|---|
| [getChildNodes()](#getChildNodes--) | Renvoie les collections de tous les nœuds enfants du nœud actuel. |
| [getShapes()](#getShapes--) | Renvoie les collections de toutes les formes associées au nœud. |
| [getTextFrame()](#getTextFrame--) | Renvoie le cadre de texte du nœud. |
| [isAssistant()](#isAssistant--) | Renvoie ou définit le nœud comme assistant. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Renvoie ou définit le nœud comme assistant. |
| [getLevel()](#getLevel--) | Renvoie le niveau d’imbrication du nœud. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Renvoie l’objet FillFormat qui contient les propriétés de format de remplissage pour une puce de nœud. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. |
| [setPosition(int value)](#setPosition-int-) | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. |
| [isHidden()](#isHidden--) | Renvoie true si ce nœud est un nœud masqué dans le modèle de données. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Renvoie ou définit le type de mise en page du diagramme organisationnel associé au nœud actuel. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Renvoie ou définit le type de mise en page du diagramme organisationnel associé au nœud actuel. |
| [remove()](#remove--) | Supprime le nœud actuel. |

### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Renvoie les collections de tous les nœuds enfants du nœud actuel. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Renvoie :**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Renvoie les collections de toutes les formes associées au nœud. Lecture seule [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Renvoie :**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Renvoie le cadre de texte du nœud. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Renvoie ou définit le nœud comme assistant. Lecture/écriture boolean.

**Renvoie :**
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Renvoie ou définit le nœud comme assistant. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
|---|---|---|
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```

Renvoie le niveau d’imbrication du nœud. Lecture seule int.

**Renvoie :**
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Renvoie l’objet FillFormat qui contient les propriétés de format de remplissage pour une puce de nœud. Remarque : peut retourner null pour certains types de mise en page SmartArt qui ne fournissent pas de puces pour les nœuds. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int .

**Renvoie :**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int .

**Paramètres :**
| Paramètre | Type | Description |
|---|---|---|
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Renvoie true si ce nœud est un nœud masqué dans le modèle de données. Lecture seule boolean.

**Renvoie :**
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Renvoie ou définit le type de mise en page du diagramme organisationnel associé au nœud actuel. Lecture/écriture [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Renvoie :**
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Renvoie ou définit le type de mise en page du diagramme organisationnel associé au nœud actuel. Lecture/écriture [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Paramètres :**
| Paramètre | Type | Description |
|---|---|---|
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```

Supprime le nœud actuel.

**Renvoie :**
boolean - true si la suppression a réussi, sinon false