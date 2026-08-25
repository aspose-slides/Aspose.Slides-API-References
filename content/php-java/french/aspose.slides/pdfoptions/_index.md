---
title: PdfOptions
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/pdfoptions/
---
## PdfOptions classe

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Pdf.

### PdfOptions {#PdfOptions}

| Nom | Description |
| --- | --- |
| PdfOptions() | Fonction par défaut. |

 **Retour :**
PdfOptions


---


### getAccessPermissions {#getAccessPermissions}

| Nom | Description |
| --- | --- |
| getAccessPermissions () | Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir PdfAccessPermissions. |

 **Retour :**
int


---


### getAdditionalCommonFontFamilies {#getAdditionalCommonFontFamilies}

| Nom | Description |
| --- | --- |
| getAdditionalCommonFontFamilies () | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[]. |

 **Retour :**
String


---


### getApplyImageTransparent {#getApplyImageTransparent}

| Nom | Description |
| --- | --- |
| getApplyImageTransparent () | Applique la couleur transparente spécifiée à une image si true. |

 **Retour :**
boolean


---


### getBestImagesCompressionRatio {#getBestImagesCompressionRatio}

| Nom | Description |
| --- | --- |
| getBestImagesCompressionRatio () | Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur true, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant. La sélection du meilleur taux de compression d'image est coûteuse en calcul et consomme de la RAM supplémentaire, et cette option est false par défaut. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getCompliance {#getCompliance}

| Nom | Description |
| --- | --- |
| getCompliance () | Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture PdfCompliance. La valeur par défaut est PdfCompliance#Pdf17. |

 **Retour :**
int


---


### getDrawSlidesFrame {#getDrawSlidesFrame}

| Nom | Description |
| --- | --- |
| getDrawSlidesFrame () | True pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getEmbedFullFonts {#getEmbedFullFonts}

| Nom | Description |
| --- | --- |
| getEmbedFullFonts () | Détermine si tous les caractères de la police doivent être incorporés ou uniquement un sous-ensemble utilisé. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getEmbedTrueTypeFontsForASCII {#getEmbedTrueTypeFontsForASCII}

| Nom | Description |
| --- | --- |
| getEmbedTrueTypeFontsForASCII () | Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture boolean. La valeur par défaut est true. |

 **Retour :**
boolean


---


### getImageTransparentColor {#getImageTransparentColor}

| Nom | Description |
| --- | --- |
| getImageTransparentColor () | Renvoie ou définit la couleur transparente de l'image. Valeur : La couleur transparente de l'image. |

 **Retour :**
Color


---


### getIncludeOleData {#getIncludeOleData}

| Nom | Description |
| --- | --- |
| getIncludeOleData () | True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getInkOptions {#getInkOptions}

| Nom | Description |
| --- | --- |
| getInkOptions () | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule IInkOptions |

 **Retour :**
[InkOptions](../inkoptions)


---


### getJpegQuality {#getJpegQuality}

| Nom | Description |
| --- | --- |
| getJpegQuality () | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte. N'a d'effet que lorsqu'un document contient des images JPEG. Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale. La valeur par défaut est 100. |

 **Retour :**
byte


---


### getPassword {#getPassword}

| Nom | Description |
| --- | --- |
| getPassword () | Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String. |

 **Retour :**
String


---


### getRasterizeUnsupportedFontStyles {#getRasterizeUnsupportedFontStyles}

| Nom | Description |
| --- | --- |
| getRasterizeUnsupportedFontStyles () | Indique si le texte doit être rasterisé en tant que bitmap et enregistré dans le PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getSaveMetafilesAsPng {#getSaveMetafilesAsPng}

| Nom | Description |
| --- | --- |
| getSaveMetafilesAsPng () | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean. La valeur par défaut est true. Un document Pdf peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur true, l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est réglé sur false, le Metafile source est converti en graphiques vectoriels Pdf. Chaque approche a ses avantages et inconvénients. Par exemple, si le Metafile est converti en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si le Metafile est converti en graphiques vectoriels Pdf, des problèmes de performances dans le visualiseur Pdf sont possibles. |

 **Retour :**
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| Nom | Description |
| --- | --- |
| getShowHiddenSlides () | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Retour :**
boolean


---


### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| getSlidesLayoutOptions () | Renvoie ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour :**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)


---


### getSufficientResolution {#getSufficientResolution}

| Nom | Description |
| --- | --- |
| getSufficientResolution () | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. Lecture/écriture float. Valeur : L'effet de ce paramètre dépend de plusieurs facteurs. L'algorithme essaie d'obtenir la meilleure taille d'image de sortie en fonction de la valeur de la propriété, de la taille de l'image source et de la taille du cadre de l'image. L'utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d'utiliser un pas de 16 ou 32 pour obtenir un effet visible. La propriété influence la taille du fichier, le temps d'exportation et la qualité de l'image. La valeur par défaut est 96. |

 **Retour :**
float


---


### getTextCompression {#getTextCompression}

| Nom | Description |
| --- | --- |
| getTextCompression () | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture PdfTextCompression. La valeur par défaut est PdfTextCompression#Flate. |

 **Retour :**
int


---


### setAccessPermissions {#setAccessPermissions}

| Nom | Description |
| --- | --- |
| setAccessPermissions (int) | Contient un ensemble de drapeaux spécifiant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir PdfAccessPermissions. |

 **Retour :**
void


---


### setAdditionalCommonFontFamilies {#setAdditionalCommonFontFamilies}

| Nom | Description |
| --- | --- |
| setAdditionalCommonFontFamilies (java.lang.String[]) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[]. |

 **Retour :**
void


---


### setApplyImageTransparent {#setApplyImageTransparent}

| Nom | Description |
| --- | --- |
| setApplyImageTransparent (boolean) | Applique la couleur transparente spécifiée à une image si true. |

 **Retour :**
void


---


### setBestImagesCompressionRatio {#setBestImagesCompressionRatio}

| Nom | Description |
| --- | --- |
| setBestImagesCompressionRatio (boolean) | Indique si la compression la plus efficace (au lieu de la compression par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé sur true, pour chaque image de la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant. La sélection du meilleur taux de compression d'image est coûteuse en calcul et consomme de la RAM supplémentaire, et cette option est false par défaut. La valeur par défaut est false. |

 **Retour :**
void


---


### setCompliance {#setCompliance}

| Nom | Description |
| --- | --- |
| setCompliance (int) | Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture PdfCompliance. La valeur par défaut est PdfCompliance#Pdf17. |

 **Retour :**
void


---


### setDrawSlidesFrame {#setDrawSlidesFrame}

| Nom | Description |
| --- | --- |
| setDrawSlidesFrame (boolean) | True pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
void


---


### setEmbedFullFonts {#setEmbedFullFonts}

| Nom | Description |
| --- | --- |
| setEmbedFullFonts (boolean) | Détermine si tous les caractères de la police doivent être incorporés ou uniquement un sous-ensemble utilisé. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
void


---


### setEmbedTrueTypeFontsForASCII {#setEmbedTrueTypeFontsForASCII}

| Nom | Description |
| --- | --- |
| setEmbedTrueTypeFontsForASCII (boolean) | Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes comprend les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lecture/écriture boolean. La valeur par défaut est true. |

 **Retour :**
void


---


### setImageTransparentColor {#setImageTransparentColor}

| Nom | Description |
| --- | --- |
| setImageTransparentColor (Color) | Renvoie ou définit la couleur transparente de l'image. Valeur : La couleur transparente de l'image. |

 **Retour :**
void


---


### setIncludeOleData {#setIncludeOleData}

| Nom | Description |
| --- | --- |
| setIncludeOleData (boolean) | True pour convertir toutes les données OLE de la présentation en fichiers incorporés dans le PDF résultant. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
void


---


### setJpegQuality {#setJpegQuality}

| Nom | Description |
| --- | --- |
| setJpegQuality (byte) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écriture byte. N'a d'effet que lorsqu'un document contient des images JPEG. Utilisez cette propriété pour obtenir ou définir la qualité des images dans un document lors de l'enregistrement au format PDF. La valeur peut varier de 0 à 100 où 0 signifie la pire qualité mais la compression maximale et 100 signifie la meilleure qualité mais la compression minimale. La valeur par défaut est 100. |

 **Retour :**
void


---


### setPassword {#setPassword}

| Nom | Description |
| --- | --- |
| setPassword (String) | Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String. |

 **Retour :**
void


---


### setRasterizeUnsupportedFontStyles {#setRasterizeUnsupportedFontStyles}

| Nom | Description |
| --- | --- |
| setRasterizeUnsupportedFontStyles (boolean) | Indique si le texte doit être rasterisé en tant que bitmap et enregistré dans le PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture boolean. La valeur par défaut est false. |

 **Retour :**
void


---


### setSaveMetafilesAsPng {#setSaveMetafilesAsPng}

| Nom | Description |
| --- | --- |
| setSaveMetafilesAsPng (boolean) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean. La valeur par défaut est true. Un document Pdf peut contenir des graphiques vectoriels et des images raster. Si SaveMetafilesAsPng est réglé sur true, l'image Metafile source est convertie au format Png et enregistrée dans le Pdf en tant qu'image raster. Si SaveMetafilesAsPng est réglé sur false, le Metafile source est converti en graphiques vectoriels Pdf. Chaque approche a ses avantages et inconvénients. Par exemple, si le Metafile est converti en PNG, une perte de qualité peut survenir lors du redimensionnement du document résultant. Si le Metafile est converti en graphiques vectoriels Pdf, des problèmes de performances dans le visualiseur Pdf sont possibles. |

 **Retour :**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| Nom | Description |
| --- | --- |
| setShowHiddenSlides (boolean) | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false. |

 **Retour :**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Renvoie ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour :**
void


---


### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| Nom | Description |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | Renvoie ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptions. |

 **Retour :**
void


---


### setSufficientResolution {#setSufficientResolution}

| Nom | Description |
| --- | --- |
| setSufficientResolution (float) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. Lecture/écriture float. Valeur : L'effet de ce paramètre dépend de plusieurs facteurs. L'algorithme essaie d'obtenir la meilleure taille d'image de sortie en fonction de la valeur de la propriété, de la taille de l'image source et de la taille du cadre de l'image. L'utilisation de valeurs de propriété similaires peut donner le même résultat. Il est recommandé d'utiliser un pas de 16 ou 32 pour obtenir un effet visible. La propriété influence la taille du fichier, le temps d'exportation et la qualité de l'image. La valeur par défaut est 96. }

 **Retour :**
void


---


### setTextCompression {#setTextCompression}

| Nom | Description |
| --- | --- |
| setTextCompression (int) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture PdfTextCompression. La valeur par défaut est PdfTextCompression#Flate. |

 **Retour :**
void


---