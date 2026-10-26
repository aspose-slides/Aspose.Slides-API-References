---
title: TiffOptions
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/tiffoptions/
---
## TiffOptions classe

 Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.
 
### TiffOptions {#TiffOptions}

| Name | Description |
| --- | --- |
| TiffOptions() | Fonction par défaut. |

 **Retour:**  
TiffOptions


---


### getBwConversionMode {#getBwConversionMode}

| Name | Description |
| --- | --- |
| getBwConversionMode () | Spécifie l'algorithme de conversion d'une image couleur en une image noir et blanc. Cette option ne sera appliquée que si CompressionType( #getCompressionType/ #setCompressionType(int)) est définie sur TiffCompressionTypes#CCITT4 ou TiffCompressionTypes#CCITT3 Lecture/écriture BlackWhiteConversionMode. La valeur par défaut est BlackWhiteConversionMode#Default. |

 **Retour:**  
int


---


### getCompressionType {#getCompressionType}

| Name | Description |
| --- | --- |
| getCompressionType () | Spécifie le type de compression. Lecture/écriture TiffCompressionTypes. |

 **Retour:**  
int


---


### getDpiX {#getDpiX}

| Name | Description |
| --- | --- |
| getDpiX () | Spécifie la résolution horizontale en points par pouce. Lecture/écriture long. |

 **Retour:**  
long


---


### getDpiY {#getDpiY}

| Name | Description |
| --- | --- |
| getDpiY () | Spécifie la résolution verticale en points par pouce. Lecture/écriture long. |

 **Retour:**  
long


---


### getImageSize {#getImageSize}

| Name | Description |
| --- | --- |
| getImageSize () | Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'images générées seront calculées en fonction de la taille des diapositives de la présentation. Lecture/écriture java.awt.Dimension. |

 **Retour:**  
Dimension


---


### getInkOptions {#getInkOptions}

| Name | Description |
| --- | --- |
| getInkOptions () | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule IInkOptions |

 **Retour:**  
[InkOptions](../inkoptions)


---


### getPixelFormat {#getPixelFormat}

| Name | Description |
| --- | --- |
| getPixelFormat () | Spécifie le format de pixel pour les images générées. Lecture/écriture ImagePixelFormat. |

 **Retour:**  
int


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Name | Description |
| --- | --- |
| getShowHiddenSlides () | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Retour:**  
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| getSlidesLayoutOptions () | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour:**  
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### setBwConversionMode {#setBwConversionMode}

| Name | Description |
| --- | --- |
| setBwConversionMode (int) | Spécifie l'algorithme de conversion d'une image couleur en une image noir et blanc. Cette option ne sera appliquée que si CompressionType( #getCompressionType/ #setCompressionType(int)) est définie sur TiffCompressionTypes#CCITT4 ou TiffCompressionTypes#CCITT3 Lecture/écriture BlackWhiteConversionMode. La valeur par défaut est BlackWhiteConversionMode#Default. |

 **Retour:**  
void


---


### setCompressionType {#setCompressionType}

| Name | Description |
| --- | --- |
| setCompressionType (int) | Spécifie le type de compression. Lecture/écriture TiffCompressionTypes. |

 **Retour:**  
void


---


### setDpiX {#setDpiX}

| Name | Description |
| --- | --- |
| setDpiX (long) | Spécifie la résolution horizontale en points par pouce. Lecture/écriture long. |

 **Retour:**  
void


---


### setDpiY {#setDpiY}

| Name | Description |
| --- | --- |
| setDpiY (long) | Spécifie la résolution verticale en points par pouce. Lecture/écriture long. |

 **Retour:**  
void


---


### setImageSize {#setImageSize}

| Name | Description |
| --- | --- |
| setImageSize (Dimension) | Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'images générées seront calculées en fonction de la taille des diapositives de la présentation. Lecture/écriture java.awt.Dimension. |

 **Retour:**  
void


---


### setPixelFormat {#setPixelFormat}

| Name | Description |
| --- | --- |
| setPixelFormat (int) | Spécifie le format de pixel pour les images générées. Lecture/écriture ImagePixelFormat. |

 **Retour:**  
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Name | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Retour:**  
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour:**  
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Name | Description |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour:**  
void


---