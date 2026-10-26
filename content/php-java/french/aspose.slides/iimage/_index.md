---
title: IImage
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs
url: /fr/aspose.slides/iimage/
---
## IImage classe

 Représente une image raster ou vectorielle.
 
 Cette interface fournit une abstraction commune pour la gestion des images raster et vectorielles.  
 Les implémentations peuvent varier en fonction du type d'image sous-jacent.
 
### IImage {#IImage}

| Nom | Description |
| --- | --- |
| IImage() |  |

 **Retourne:**
IImage


---


### getHeight {#getHeight}

| Nom | Description |
| --- | --- |
| getHeight () | Obtient la hauteur de l'image en pixels. |

 **Retourne:**
int


---


### getSize {#getSize}

| Nom | Description |
| --- | --- |
| getSize () | Obtient la taille de l'image. |

 **Retourne:**
Dimension


---


### getWidth {#getWidth}

| Nom | Description |
| --- | --- |
| getWidth () | Obtient la largeur de l'image en pixels. |

 **Retourne:**
int


---


### save {#save}

| Nom | Description |
| --- | --- |
| save (String) | Enregistre l'image dans un fichier. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| filename | String | Le chemin du fichier où l'image sera enregistrée. |

 **Retourne:**
void


---


### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int) | Enregistre l'image dans un fichier au format spécifié. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| filename | String | Le chemin du fichier où l'image sera enregistrée. |
| format | int | Le format de l'image. |

 **Retourne:**
void


---


### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int) | Enregistre l'image dans un flux au format spécifié. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Le flux où l'image sera enregistrée. |
| format | int | Le format de l'image. |

 **Retourne:**
void


---


### save {#save}

| Nom | Description |
| --- | --- |
| save (String, int, int) | Enregistre l'image dans un fichier au format spécifié et avec la qualité indiquée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| filename | String | Le chemin du fichier où l'image sera enregistrée. |
| format | int | Le format de l'image. |
| quality | int | La qualité de l'image enregistrée (0 à 100). Ce paramètre n'affecte que l'enregistrement en ImageFormat#Jpeg ; pour tous les autres formats, il est ignoré. |

 **Retourne:**
void


---


### save {#save}

| Nom | Description |
| --- | --- |
| save (OutputStream, int, int) | Enregistre l'image dans un flux au format spécifié et avec la qualité indiquée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Le flux où l'image sera enregistrée. |
| format | int | Le format de l'image. |
| quality | int | La qualité de l'image enregistrée (0 à 100). Ce paramètre n'affecte que l'enregistrement en ImageFormat#Jpeg ; pour tous les autres formats, il est ignoré. |

 **Retourne:**
void


---