---
title: PatternFormat
second_title: Aspose.Sildes pour PHP via Référence API Java
description: 
type: docs

url: /fr/aspose.slides/patternformat/
---
## PatternFormat classe

 Représente un motif pour remplir une forme.
 
### getBackColor {#getBackColor}

| Nom | Description |
| --- | --- |
| getBackColor () | Renvoie la couleur de motif d'arrière-plan. Lecture seule IColorFormat. |

 **Renvoie:**
[ColorFormat](../colorformat)


---


### getForeColor {#getForeColor}

| Nom | Description |
| --- | --- |
| getForeColor () | Renvoie la couleur de motif de premier plan. Lecture seule IColorFormat. |

 **Renvoie:**
[ColorFormat](../colorformat)


---


### getPatternStyle {#getPatternStyle}

| Nom | Description |
| --- | --- |
| getPatternStyle () | Renvoie ou définit le style du motif. Lecture/écriture PatternStyle. |

 **Renvoie:**
byte


---


### getTile {#getTile}

| Nom | Description |
| --- | --- |
| getTile (Color, Color) | Crée une image en mosaïque pour le remplissage du motif avec des couleurs spécifiées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| background | Color | La couleur d'arrière-plan java.awt.Color pour le motif. |
| foreground | Color | La couleur de premier plan java.awt.Color pour le motif. |

 **Renvoie:**
IImage


---


### getTile {#getTile}

| Nom | Description |
| --- | --- |
| getTile (Color) | Crée une image en mosaïque pour le remplissage du motif. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| styleColor | Color | La couleur java.awt.Color par défaut |

 **Renvoie:**
IImage


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie:**
long


---


### setPatternStyle {#setPatternStyle}

| Nom | Description |
| --- | --- |
| setPatternStyle (byte) | Renvoie ou définit le style du motif. Lecture/écriture PatternStyle. |

 **Renvoie:**
void


---