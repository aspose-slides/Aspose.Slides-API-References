---
title: Convert
second_title: Référence de l'API Java d'Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/convert/
---
## Classe Convert

 Représente un groupe de méthodes destiné à convertir Presentation.
 
### Convert {#Convert}

| Name | Description |
| --- | --- |
| Convert() |  |

 **Renvoie :**
Convert


---


### autoByExtension {#autoByExtension}

| Name | Description |
| --- | --- |
| autoByExtension (String, String) | Convertit Presentation en utilisant l'extension du chemin de sortie fournie pour déterminer le format d'exportation requis. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presPath | String | Chemin de la présentation d'entrée |
| outPath | String | Chemin de sortie |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Si le format est inconnu ou non pris en charge |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, Dimension) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée |
| outputFileName | String | Le nom de fichier de sortie. |
| imageSize | Dimension | La taille de chaque image générée. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |
| scale | float | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille de la diapositive originale. |
| options | [RenderingOptions](../renderingoptions) | Les options de rendu. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf (String, String) | Convertit Presentation en PDF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presPath | String | Chemin de la présentation d'entrée |
| outPath | String | Chemin de sortie |

 **Renvoie :**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf (String, String, [PdfOptions](../pdfoptions)) | Convertit Presentation en PDF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presPath | String | Chemin de la présentation d'entrée |
| outPath | String | Chemin de sortie |
| options | [PdfOptions](../pdfoptions) | Les options de sortie PDF |

 **Renvoie :**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf ([Presentation](../presentation), String) | Convertit Presentation en PDF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Présentation d'entrée |
| outPath | String | Chemin de sortie |

 **Renvoie :**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf ([Presentation](../presentation), String, [PdfOptions](../pdfoptions)) | Convertit Presentation en PDF. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Présentation d'entrée |
| outPath | String | Chemin de sortie |
| options | [PdfOptions](../pdfoptions) | Les options de sortie PDF |

 **Renvoie :**
void


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String, Dimension) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée |
| outputFileName | String | Le nom de fichier de sortie. |
| imageSize | Dimension | La taille de chaque image générée. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |
| scale | float | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille de la diapositive originale. |
| options | [RenderingOptions](../renderingoptions) | Les options de rendu. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg (String) | Convertit Presentation en SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presPath | String | Chemin de la présentation d'entrée |

 **Renvoie :**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg (String, [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Convertit Presentation en SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| presPath | String | Chemin de la présentation d'entrée |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

 **Renvoie :**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Convertit Presentation en SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Présentation d'entrée |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

 **Renvoie :**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [SVGOptions](../svgoptions)) | Convertit Presentation en SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Présentation d'entrée |
| options | [SVGOptions](../svgoptions) | Options d'exportation SVG |

 **Renvoie :**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback), [SVGOptions](../svgoptions)) | Convertit Presentation en SVG. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Présentation d'entrée |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |
| options | [SVGOptions](../svgoptions) | Options d'exportation SVG |

 **Renvoie :**
void


---


### toTiff {#toTiff}

| Name | Description |
| --- | --- |
| toTiff ([Presentation](../presentation), String) | Convertit la présentation d'entrée en un ensemble d'images au format TIFF. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.tiff", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro de la diapositive. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toTiff {#toTiff}

| Name | Description |
| --- | --- |
| toTiff ([Presentation](../presentation), String, [TiffOptions](../tiffoptions), boolean) | Convertit la présentation d'entrée au format TIFF avec des options personnalisées. Si le nom de fichier de sortie est donné sous la forme "myPath/myFilename.tiff" et que multipage est false, le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro de la diapositive. Sinon, si multipage est true, le résultat sera un document multi-pages "myPath/myFilename.tiff". |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | La présentation d'entrée. |
| outputFileName | String | Le nom de fichier de sortie. |
| options | [TiffOptions](../tiffoptions) | Les options d'enregistrement TIFF. |
| multipage | boolean | Spécifie si le document TIFF généré doit être multi-pages. |

 **Renvoie :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | null | ArgumentException |


---