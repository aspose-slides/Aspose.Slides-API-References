---
title: ISmartArtNode
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un nœud d'un diagramme SmartArt.
type: docs
url: /fr/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Représente un nœud d'un diagramme SmartArt.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Renvoie les collections de tous les nœuds enfants du nœud actuel. |
| [getShapes()](#getShapes--) | Renvoie les collections de toutes les formes associées au nœud. |
| [getTextFrame()](#getTextFrame--) | Renvoie ou définit le texte du nœud. |
| [isAssistant()](#isAssistant--) | Renvoie ou définit le nœud comme assistant. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Renvoie ou définit le nœud comme assistant. |
| [getLevel()](#getLevel--) | Renvoie le niveau d'imbrication du nœud. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Renvoie l'objet FillFormat qui contient les propriétés de mise en forme de remplissage pour la puce d'un nœud. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. |
| [setPosition(int value)](#setPosition-int-) | Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. |
| [isHidden()](#isHidden--) | Renvoie vrai si ce nœud est un nœud masqué dans le modèle de données. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Renvoie ou définit le type de mise en page du organigramme associé au nœud actuel. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Renvoie ou définit le type de mise en page du organigramme associé au nœud actuel. |
| [remove()](#remove--) | Supprime le nœud actuel. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Renvoie les collections de tous les nœuds enfants du nœud actuel. Lecture seule [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Renvoie :**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Renvoie les collections de toutes les formes associées au nœud. Lecture seule [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Renvoie :**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Renvoie ou définit le texte du nœud. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Renvoie ou définit le nœud comme assistant. Lecture/écriture booléen.

**Renvoie :**  
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Renvoie ou définit le nœud comme assistant. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Renvoie le niveau d'imbrication du nœud. Lecture seule int.

**Renvoie :**  
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Renvoie l'objet FillFormat qui contient les propriétés de mise en forme de remplissage pour la puce d'un nœud. Remarque : peut renvoyer null pour certains types de mise en page SmartArt qui ne fournissent pas de puces pour les nœuds. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int.

**Renvoie :**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Renvoie ou définit la position basée sur zéro du nœud parmi les nœuds frères. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Renvoie vrai si ce nœud est un nœud masqué dans le modèle de données. Lecture seule booléen.

**Renvoie :**  
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Renvoie ou définit le type de mise en page du organigramme associé au nœud actuel. Lecture/écriture [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Renvoie :**  
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Renvoie ou définit le type de mise en page du organigramme associé au nœud actuel. Lecture/écriture [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Supprime le nœud actuel.

**Renvoie :**  
booléen - vrai si la suppression a réussi, sinon faux.