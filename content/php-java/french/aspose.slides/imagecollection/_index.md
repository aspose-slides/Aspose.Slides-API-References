---
title: ImageCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/imagecollection/
---
## ImageCollection classe

 Représente une collection de PPImage.
 
### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([PPImage](../ppimage)) | Ajoute une copie d'une image d'une autre présentation. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| imageSource | [PPImage](../ppimage) | Image source. |

 **Retour:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([IImage](../iimage)) | Ajoute une image à une présentation. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| image | [IImage](../iimage) | Image à ajouter. Cette méthode convertit les métas fichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation. |

 **Retour:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (InputStream) | Ajoute une image à une présentation depuis un flux. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux depuis lequel ajouter l'image. Cette méthode peut ajouter des métas fichiers WMF/EMF à une présentation sans les convertir en image PNG raster. |

 **Retour:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (InputStream, int) | Crée et ajoute une image à une présentation depuis un flux. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux depuis lequel ajouter le fichier image. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

 **Retour:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage (byte[]) | Ajoute une image à une présentation à partir d'un tampon spécifié. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

 **Retour:**
[PPImage](../ppimage)


---


### addImage {#addImage}

| Name | Description |
| --- | --- |
| addImage ([SvgImage](../svgimage)) | Ajoute une image à une présentation à partir d'un objet Svg. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Objet d'image Svg ISvgImage |

 **Retour:**
[PPImage](../ppimage)

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentNullException | Lorsque le paramètre svgImage est nul. |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet lecture seule. |

 **Retour:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. IPPImage lecture seule. |

 **Retour:**
[PPImage](../ppimage)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Booléen lecture seule. |

 **Retour:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour la collection entière. |

 **Retour:**



---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Renvoie le nombre d'images dans la collection. int lecture seule. |

 **Retour:**
int


---



