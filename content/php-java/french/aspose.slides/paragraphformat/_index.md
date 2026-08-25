---
title: ParagraphFormat
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

 Cette classe contient les propriétés de mise en forme des paragraphes. Contrairement à IParagraphFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.  
 Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme des paragraphes définies pour le paragraphe particulier. Cela signifie qu’aucune héritage n’est appliqué lors de l’obtention des valeurs, de sorte que dans la majorité des cas vous recevrez des valeurs signifiant « undefined ».  
 Pour obtenir les valeurs des paramètres de mise en forme effectifs, y compris ceux hérités, vous devez utiliser la méthode ParagraphFormat#getEffective qui renvoie une instance de IParagraphFormatEffectiveData.  

### ParagraphFormat {#ParagraphFormat}

| Nom | Description |
| --- | --- |
| ParagraphFormat() | Initialise une nouvelle instance de la classe ParagraphFormat. |

 **Renvoie :**
ParagraphFormat


---


### getAlignment {#getAlignment}

| Nom | Description |
| --- | --- |
| getAlignment () | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture TextAlignment. |

 **Renvoie :**
int


---


### getBullet {#getBullet}

| Nom | Description |
| --- | --- |
| getBullet () | Renvoie le format du puce du paragraphe. Lecture seule IBulletFormat. |

 **Renvoie :**
[BulletFormat](../bulletformat)


---


### getDefaultPortionFormat {#getDefaultPortionFormat}

| Nom | Description |
| --- | --- |
| getDefaultPortionFormat () | Renvoie le format de portion par défaut d’un paragraphe. Aucun héritage appliqué. Lecture seule IPortionFormat. |

 **Renvoie :**
[PortionFormat](../portionformat)


---


### getDefaultTabSize {#getDefaultTabSize}

| Nom | Description |
| --- | --- |
| getDefaultTabSize () | Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture float. |

 **Renvoie :**
float


---


### getDepth {#getDepth}

| Nom | Description |
| --- | --- |
| getDepth () | Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture short. |

 **Renvoie :**
short


---


### getEastAsianLineBreak {#getEastAsianLineBreak}

| Nom | Description |
| --- | --- |
| getEastAsianLineBreak () | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### getEffective {#getEffective}

| Nom | Description |
| --- | --- |
| getEffective () | Obtient les données de mise en forme effectives du paragraphe avec l’héritage appliqué. |

 **Renvoie :**
ParagraphFormatEffectiveData


---


### getFontAlignment {#getFontAlignment}

| Nom | Description |
| --- | --- |
| getFontAlignment () | Renvoie ou définit l’alignement de la police dans un paragraphe sans héritage. Lecture/écriture FontAlignment. |

 **Renvoie :**
int


---


### getHangingPunctuation {#getHangingPunctuation}

| Nom | Description |
| --- | --- |
| getHangingPunctuation () | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### getIndent {#getIndent}

| Nom | Description |
| --- | --- |
| getIndent () | Renvoie ou définit le retrait de première ligne ou le retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture float. |

 **Renvoie :**
float


---


### getLatinLineBreak {#getLatinLineBreak}

| Nom | Description |
| --- | --- |
| getLatinLineBreak () | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### getMarginLeft {#getMarginLeft}

| Nom | Description |
| --- | --- |
| getMarginLeft () | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture float. |

 **Renvoie :**
float


---


### getMarginRight {#getMarginRight}

| Nom | Description |
| --- | --- |
| getMarginRight () | Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture float. |

 **Renvoie :**
float


---


### getRightToLeft {#getRightToLeft}

| Nom | Description |
| --- | --- |
| getRightToLeft () | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
byte


---


### getSpaceAfter {#getSpaceAfter}

| Nom | Description |
| --- | --- |
| getSpaceAfter () | Renvoie ou définit la quantité d’espace après la dernière ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture float. |

 **Renvoie :**
float


---


### getSpaceBefore {#getSpaceBefore}

| Nom | Description |
| --- | --- |
| getSpaceBefore () | Renvoie ou définit la quantité d’espace avant la première ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture float. |

 **Renvoie :**
float


---


### getSpaceWithin {#getSpaceWithin}

| Nom | Description |
| --- | --- |
| getSpaceWithin () | Renvoie ou définit la quantité d’espace entre les lignes de base d’un paragraphe. Une valeur positive signifie pourcentage, négative – taille en points. Aucun héritage appliqué. Lecture/écriture float. |

 **Renvoie :**
float


---


### getTabs {#getTabs}

| Nom | Description |
| --- | --- |
| getTabs () | Renvoie les tabulations d’un paragraphe. Aucun héritage appliqué. Lecture seule ITabCollection. |

 **Renvoie :**
[TabCollection](../tabcollection)


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie :**
long


---


### setAlignment {#setAlignment}

| Nom | Description |
| --- | --- |
| setAlignment (int) | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture TextAlignment. |

 **Renvoie :**
void


---


### setDefaultTabSize {#setDefaultTabSize}

| Nom | Description |
| --- | --- |
| setDefaultTabSize (float) | Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture float. |

 **Renvoie :**
void


---


### setDepth {#setDepth}

| Nom | Description |
| --- | --- |
| setDepth (short) | Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture short. |

 **Renvoie :**
void


---


### setEastAsianLineBreak {#setEastAsianLineBreak}

| Nom | Description |
| --- | --- |
| setEastAsianLineBreak (byte) | Détermine si le saut de ligne est-asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---


### setFontAlignment {#setFontAlignment}

| Nom | Description |
| --- | --- |
| setFontAlignment (int) | Renvoie ou définit l’alignement de la police dans un paragraphe sans héritage. Lecture/écriture FontAlignment. |

 **Renvoie :**
void


---


### setHangingPunctuation {#setHangingPunctuation}

| Nom | Description |
| --- | --- |
| setHangingPunctuation (byte) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---


### setIndent {#setIndent}

| Nom | Description |
| --- | --- |
| setIndent (float) | Renvoie ou définit le retrait de première ligne ou le retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture float. |

 **Renvoie :**
void


---


### setLatinLineBreak {#setLatinLineBreak}

| Nom | Description |
| --- | --- |
| setLatinLineBreak (byte) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---


### setMarginLeft {#setMarginLeft}

| Nom | Description |
| --- | --- |
| setMarginLeft (float) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture float. |

 **Renvoie :**
void


---


### setMarginRight {#setMarginRight}

| Nom | Description |
| --- | --- |
| setMarginRight (float) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture float. |

 **Renvoie :**
void


---


### setRightToLeft {#setRightToLeft}

| Nom | Description |
| --- | --- |
| setRightToLeft (byte) | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture NullableBool. |

 **Renvoie :**
void


---


### setSpaceAfter {#setSpaceAfter}

| Nom | Description |
| --- | --- |
| setSpaceAfter (float) | Renvoie ou définit la quantité d’espace après la dernière ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture float. |

 **Renvoie :**
void


---


### setSpaceBefore {#setSpaceBefore}

| Nom | Description |
| --- | --- |
| setSpaceBefore (float) | Renvoie ou définit la quantité d’espace avant la première ligne d’un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l’espace blanc. Une valeur négative indique la taille de l’espace blanc en points. Lecture/écriture float. |

 **Renvoie :**
void


---


### setSpaceWithin {#setSpaceWithin}

| Nom | Description |
| --- | --- |
| setSpaceWithin (float) | Renvoie ou définit la quantité d’espace entre les lignes de base d’un paragraphe. Une valeur positive signifie pourcentage, négative – taille en points. Aucun héritage appliqué. Lecture/écriture float. |

 **Renvoie :**
void


---