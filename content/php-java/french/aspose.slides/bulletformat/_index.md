---
title: BulletFormat
second_title: Aspose.Slides pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/bulletformat/
---
## BulletFormat classe

 Représente les propriétés de formatage des puces de paragraphe.
 
### applyDefaultParagraphIndentsShifts {#applyDefaultParagraphIndentsShifts}

| Nom | Description |
| --- | --- |
| applyDefaultParagraphIndentsShifts () | Définit les décalages non nuls par défaut pour l'Indent et le MarginLeft effectifs du paragraphe lorsque les bullets sont activées (comme PowerPoint le fait si la numérotation/puces de paragraphe est activée). Si les bullets sont désactivées, réinitialise simplement l'Indent et le MarginLeft du paragraphe (comme PowerPoint le fait si la numérotation/puces de paragraphe est désactivée). Les décalages d'indentation sont appliqués par rapport au contexte de puce actuel - IBulletFormat.Type, .NumberedBulletStyle et FontHeight de la première portion. Les décalages d'indentation non nuls sont appliqués à l'Indent et au MarginLeft effectifs du paragraphe actuel (les valeurs résultantes deviennent des valeurs locales). |

 **Retourne :**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| InvalidOperationException | L'appel de cette méthode n'a pas d'importance et lance InvalidOperationException dans les cas suivants : si l'objet formaté parent n'est pas un paragraphe (par exemple appeler ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() déclenchera une exception) ; ou si le paragraphe n'a pas été ajouté à la collection ITextFrame.Paragraphs (ajoutez-le d'abord) ; |


---


### getChar {#getChar}

| Nom | Description |
| --- | --- |
| getChar () | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Char en lecture/écriture. |

 **Retourne :**  
char


---


### getColor {#getColor}

| Nom | Description |
| --- | --- |
| getColor () | Renvoie le format de couleur d'une puce d'un paragraphe sans héritage. IColorFormat en lecture seule. |

 **Retourne :**  
[ColorFormat](../colorformat)


---


### getEffective {#getEffective}

| Nom | Description |
| --- | --- |
| getEffective () | Obtient les données de formatage de puce effectives avec l'héritage appliqué. |

 **Retourne :**  
BulletFormatEffectiveData


---


### getFont {#getFont}

| Nom | Description |
| --- | --- |
| getFont () | Renvoie ou définit la police de puce d'un paragraphe sans héritage. IFontData en lecture/écriture. |

 **Retourne :**  
[FontData](../fontdata)


---


### getHeight {#getHeight}

| Nom | Description |
| --- | --- |
| getHeight () | Renvoie ou définit la hauteur de la puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Float en lecture/écriture. Une valeur de hauteur négative signifie que la hauteur est donnée en points et une valeur positive que la hauteur est un pourcentage du texte environnant. |

 **Retourne :**  
float


---


### getNumberedBulletStartWith {#getNumberedBulletStartWith}

| Nom | Description |
| --- | --- |
| getNumberedBulletStartWith () | Renvoie ou définit le premier numéro utilisé pour un groupe de puces numérotées sans héritage. short en lecture/écriture. |

 **Retourne :**  
short


---


### getNumberedBulletStyle {#getNumberedBulletStyle}

| Nom | Description |
| --- | --- |
| getNumberedBulletStyle () | Renvoie ou définit le style d'une puce numérotée sans héritage. NumberedBulletStyle en lecture/écriture. |

 **Retourne :**  
byte


---


### getPicture {#getPicture}

| Nom | Description |
| --- | --- |
| getPicture () | Renvoie l'image utilisée comme puce dans un paragraphe sans héritage. ISlidesPicture en lecture seule. |

 **Retourne :**  
[Picture](../picture)


---


### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Renvoie ou définit le type de puce d'un paragraphe sans héritage. BulletType en lecture/écriture. |

 **Retourne :**  
byte


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Retourne :**  
long


---


### isBulletHardColor {#isBulletHardColor}

| Nom | Description |
| --- | --- |
| isBulletHardColor () | Détermine si la puce a sa propre couleur ou l'hérite de la première portion du paragraphe. NullableBool.True si la puce a sa propre couleur et NullableBool.False si la puce hérite de la couleur de la première portion du paragraphe. NullableBool en lecture/écriture. |

 **Retourne :**  
byte


---


### isBulletHardFont {#isBulletHardFont}

| Nom | Description |
| --- | --- |
| isBulletHardFont () | Détermine si la puce a sa propre police ou l'hérite de la première portion du paragraphe. NullableBool.True si la puce a sa propre police et NullableBool.False si la puce hérite de la police de la première portion du paragraphe. NullableBool en lecture/écriture. |

 **Retourne :**  
byte


---


### setBulletHardColor {#setBulletHardColor}

| Nom | Description |
| --- | --- |
| setBulletHardColor (byte) | Détermine si la puce a sa propre couleur ou l'hérite de la première portion du paragraphe. NullableBool.True si la puce a sa propre couleur et NullableBool.False si la puce hérite de la couleur de la première portion du paragraphe. NullableBool en lecture/écriture. |

 **Retourne :**  
void


---


### setBulletHardFont {#setBulletHardFont}

| Nom | Description |
| --- | --- |
| setBulletHardFont (byte) | Détermine si la puce a sa propre police ou l'hérite de la première portion du paragraphe. NullableBool.True si la puce a sa propre police et NullableBool.False si la puce hérite de la police de la première portion du paragraphe. NullableBool en lecture/écriture. |

 **Retourne :**  
void


---


### setChar {#setChar}

| Nom | Description |
| --- | --- |
| setChar (char) | Renvoie ou définit le caractère de puce d'un paragraphe sans héritage. Char en lecture/écriture. |

 **Retourne :**  
void


---


### setFont {#setFont}

| Nom | Description |
| --- | --- |
| setFont ([FontData](../fontdata)) | Renvoie ou définit la police de puce d'un paragraphe sans héritage. IFontData en lecture/écriture. |

 **Retourne :**  
void


---


### setHeight {#setHeight}

| Nom | Description |
| --- | --- |
| setHeight (float) | Renvoie ou définit la hauteur de la puce d'un paragraphe sans héritage. La valeur Float.NaN indique que la puce hérite de la hauteur de la première portion du paragraphe. Float en lecture/écriture. Une valeur de hauteur négative signifie que la hauteur est donnée en points et une valeur positive que la hauteur est un pourcentage du texte environnant. |

 **Retourne :**  
void


---


### setNumberedBulletStartWith {#setNumberedBulletStartWith}

| Nom | Description |
| --- | --- |
| setNumberedBulletStartWith (short) | Renvoie ou définit le premier numéro utilisé pour un groupe de puces numérotées sans héritage. short en lecture/écriture. |

 **Retourne :**  
void


---


### setNumberedBulletStyle {#setNumberedBulletStyle}

| Nom | Description |
| --- | --- |
| setNumberedBulletStyle (byte) | Renvoie ou définit le style d'une puce numérotée sans héritage. NumberedBulletStyle en lecture/écriture. |

 **Retourne :**  
void


---


### setType {#setType}

| Nom | Description |
| --- | --- |
| setType (byte) | Renvoie ou définit le type de puce d'un paragraphe sans héritage. BulletType en lecture/écriture. |

 **Retourne :**  
void


---