---
title: TextFrameFormat
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/textframeformat/
---
## classe TextFrameFormat

  Contient les propriétés formatTextFrameFormatting du TextFrame.
 
### TextFrameFormat {#TextFrameFormat}

| Nom | Description |
| --- | --- |
| TextFrameFormat() | Initialise une nouvelle instance de la classe TextFrameFormat. |

 **Renvoie :**
TextFrameFormat


---


### getAnchoringType {#getAnchoringType}

| Nom | Description |
| --- | --- |
| getAnchoringType () | Renvoie ou définit le texte d’ancre verticale dans un TextFrame. Lecture/écriture TextAnchorType. |

 **Renvoie :**
byte


---


### getAutofitType {#getAutofitType}

| Nom | Description |
| --- | --- |
| getAutofitType () | Renvoie ou définit le mode d’ajustement automatique du texte. Lecture/écriture TextAutofitType. |

 **Renvoie :**
byte


---


### getCenterText {#getCenterText}

| Nom | Description |
| --- | --- |
| getCenterText () | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### getColumnCount {#getColumnCount}

| Nom | Description |
| --- | --- |
| getColumnCount () | Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. La valeur 0 signifie valeur non définie. Lecture/écriture int. |

 **Renvoie :**
int


---


### getColumnSpacing {#getColumnSpacing}

| Nom | Description |
| --- | --- |
| getColumnSpacing () | Renvoie ou définit l’espace entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s’appliquer que lorsqu’il y a plus d’une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. Lecture/écriture double. |

 **Renvoie :**
double


---


### getEffective {#getEffective}

| Nom | Description |
| --- | --- |
| getEffective () | Obtient les données de formatage effectif du cadre de texte avec l’héritage appliqué. |

 **Renvoie :**
TextFrameFormatEffectiveData


---


### getKeepTextFlat {#getKeepTextFlat}

| Nom | Description |
| --- | --- |
| getKeepTextFlat () | Obtient ou définit le maintien du texte à plat même si un effet de rotation 3-D a été appliqué. Lecture/écriture boolean. |

 **Renvoie :**
boolean


---


### getMarginBottom {#getMarginBottom}

| Nom | Description |
| --- | --- |
| getMarginBottom () | Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
double


---


### getMarginLeft {#getMarginLeft}

| Nom | Description |
| --- | --- |
| getMarginLeft () | Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
double


---


### getMarginRight {#getMarginRight}

| Nom | Description |
| --- | --- |
| getMarginRight () | Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
double


---


### getMarginTop {#getMarginTop}

| Nom | Description |
| --- | --- |
| getMarginTop () | Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
double


---


### getRotationAngle {#getRotationAngle}

| Nom | Description |
| --- | --- |
| getRotationAngle () | Spécifie la rotation personnalisée appliquée au texte à l’intérieur du cadre englobant. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle s’applique indépendamment de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation du texte lui--même. La valeur visuelle résultante de la rotation du texte est résumée à partir de cette propriété et du type vertical pré-défini dans la propriété TextVerticalType. Lecture/écriture float. |

 **Renvoie :**
float


---


### getTextStyle {#getTextStyle}

| Nom | Description |
| --- | --- |
| getTextStyle () | Renvoie le style du texte. Lecture seule ITextStyle. |

 **Renvoie :**
[TextStyle](../textstyle)


---


### getTextVerticalType {#getTextVerticalType}

| Nom | Description |
| --- | --- |
| getTextVerticalType () | Détermine l’orientation du texte. La valeur visuelle résultante de la rotation du texte est résumée à partir de cette propriété et de l’angle personnalisé dans la propriété RotationAngle. Lecture/écriture TextVerticalType. |

 **Renvoie :**
byte


---


### getThreeDFormat {#getThreeDFormat}

| Nom | Description |
| --- | --- |
| getThreeDFormat () | Renvoie l’objet ThreeDFormat qui représente les propriétés d’effet 3D pour un texte. Lecture seule IThreeDFormat. |

 **Renvoie :**
[ThreeDFormat](../threedformat)


---


### getTransform {#getTransform}

| Nom | Description |
| --- | --- |
| getTransform () | Obtient ou définit la forme d’encadrement du texte. Lecture/écriture TextShapeType. |

 **Renvoie :**
byte


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie :**
long


---


### getWrapText {#getWrapText}

| Nom | Description |
| --- | --- |
| getWrapText () | Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### setAnchoringType {#setAnchoringType}

| Nom | Description |
| --- | --- |
| setAnchoringType (byte) | Renvoie ou définit le texte d’ancre verticale dans un TextFrame. Lecture/écriture TextAnchorType. |

 **Renvoie :**
void


---


### setAutofitType {#setAutofitType}

| Nom | Description |
| --- | --- |
| setAutofitType (byte) | Renvoie ou définit le mode d’ajustement automatique du texte. Lecture/écriture TextAutofitType. |

 **Renvoie :**
void


---


### setCenterText {#setCenterText}

| Nom | Description |
| --- | --- |
| setCenterText (byte) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---


### setColumnCount {#setColumnCount}

| Nom | Description |
| --- | --- |
| setColumnCount (int) | Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. La valeur 0 signifie valeur non définie. Lecture/écriture int. |

 **Renvoie :**
void


---


### setColumnSpacing {#setColumnSpacing}

| Nom | Description |
| --- | --- |
| setColumnSpacing (double) | Renvoie ou définit l’espace entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s’appliquer que lorsqu’il y a plus d’une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera mise à zéro. Lecture/écriture double. |

 **Renvoie :**
void


---


### setKeepTextFlat {#setKeepTextFlat}

| Nom | Description |
| --- | --- |
| setKeepTextFlat (boolean) | Obtient ou définit le maintien du texte à plat même si un effet de rotation 3-D a été appliqué. Lecture/écriture boolean. |

 **Renvoie :**
void


---


### setMarginBottom {#setMarginBottom}

| Nom | Description |
| --- | --- |
| setMarginBottom (double) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
void


---


### setMarginLeft {#setMarginLeft}

| Nom | Description |
| --- | --- |
| setMarginLeft (double) | Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
void


---


### setMarginRight {#setMarginRight}

| Nom | Description |
| --- | --- |
| setMarginRight (double) | Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
void


---


### setMarginTop {#setMarginTop}

| Nom | Description |
| --- | --- |
| setMarginTop (double) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double. |

 **Renvoie :**
void


---


### setRotationAngle {#setRotationAngle}

| Nom | Description |
| --- | --- |
| setRotationAngle (float) | Spécifie la rotation personnalisée appliquée au texte à l’intérieur du cadre englobant. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle s’applique indépendamment de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation du texte lui--même. La valeur visuelle résultante de la rotation du texte est résumée à partir de cette propriété et du type vertical pré-défini dans la propriété TextVerticalType. Lecture/écriture float. |

 **Renvoie :**
void


---


### setTextVerticalType {#setTextVerticalType}

| Nom | Description |
| --- | --- |
| setTextVerticalType (byte) | Détermine l’orientation du texte. La valeur visuelle résultante de la rotation du texte est résumée à partir de cette propriété et de l’angle personnalisé dans la propriété RotationAngle. Lecture/écriture TextVerticalType. |

 **Renvoie :**
void


---


### setTransform {#setTransform}

| Nom | Description |
| --- | --- |
| setTransform (byte) | Obtient ou définit la forme d’encadrement du texte. Lecture/écriture TextShapeType. |

 **Renvoie :**
void


---


### setWrapText {#setWrapText}

| Nom | Description |
| --- | --- |
| setWrapText (byte) | Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---