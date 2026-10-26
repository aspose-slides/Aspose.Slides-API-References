---
title: PPImage
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/ppimage/
---
## PPImage classe

 Représente une image dans une présentation.
 
### dispose {#dispose}

| Nom | Description |
| --- | --- |
| dispose () | Disposes object. |

 **Retourne :**
void


---


### getBinaryData {#getBinaryData}

| Nom | Description |
| --- | --- |
| getBinaryData () | Renvoie une copie des données d'une image. Lecture seule byte[]. |

 **Retourne :**
byte


---


### getContentType {#getContentType}

| Nom | Description |
| --- | --- |
| getContentType () | Renvoie un type MIME d'une image, encodé dans BinaryData( #getBinaryData). Lecture seule String. |

 **Retourne :**
String


---


### getHeight {#getHeight}

| Nom | Description |
| --- | --- |
| getHeight () | Renvoie une hauteur d'une image. Lecture seule int. |

 **Retourne :**
int


---


### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage () | Renvoie une copie d'une image. Lecture seule IImage. |

 **Retourne :**
IImage


---


### getSvgImage {#getSvgImage}

| Nom | Description |
| --- | --- |
| getSvgImage () | Renvoie ou définit l'objet ISvgImage. Cette valeur indique que cette image a été créée à partir de SVG. |

 **Retourne :**
[SvgImage](../svgimage)


---


### getWidth {#getWidth}

| Nom | Description |
| --- | --- |
| getWidth () | Renvoie une largeur d'une image. Lecture seule int. |

 **Retourne :**
int


---


### getX {#getX}

| Nom | Description |
| --- | --- |
| getX () | Renvoie un décalage X d'une image. Lecture seule int. |

 **Retourne :**
int


---


### getY {#getY}

| Nom | Description |
| --- | --- |
| getY () | Renvoie un décalage Y d'une image. Lecture seule int. |

 **Retourne :**
int


---


### hashCode {#hashCode}

| Nom | Description |
| --- | --- |
| hashCode () | Renvoie le code de hachage d'une image. |

 **Retourne :**
int


---


### replaceImage {#replaceImage}

| Nom | Description |
| --- | --- |
| replaceImage (byte[]) | Remplace les données de l'image. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | Les données de la nouvelle image. |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lorsque le paramètre newImageData est nul. |


---


### replaceImage {#replaceImage}

| Nom | Description |
| --- | --- |
| replaceImage ([IImage](../iimage)) | Remplace les données de l'image. Attention : lorsque l'image est un métafichier - elle sera rasterisée. Utilisez ReplaceImage(byte[]) à la place |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../iimage) | La nouvelle image. |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lorsque le paramètre newImage est nul. |


---


### replaceImage {#replaceImage}

| Nom | Description |
| --- | --- |
| replaceImage ([PPImage](../ppimage)) | Remplace les données de l'image. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| newImage | [PPImage](../ppimage) | Le nouvel IPPImage. |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lorsque le paramètre newImage est nul. |


---


### setSvgImage {#setSvgImage}

| Nom | Description |
| --- | --- |
| setSvgImage ([SvgImage](../svgimage)) | Renvoie ou définit l'objet ISvgImage. Cette valeur indique que cette image a été créée à partir de SVG. |

 **Retourne :**
void


---