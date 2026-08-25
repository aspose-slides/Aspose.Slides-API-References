---
title: EmbedAllFontsHtmlController
second_title: Référence de l'API Java Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController classe

 La classe du contrôleur de formatage à utiliser pour incorporer toutes les polices de la présentation au format WOFF.
 
### EmbedAllFontsHtmlController {#EmbedAllFontsHtmlController}

| Nom | Description |
| --- | --- |
| EmbedAllFontsHtmlController() | Crée une nouvelle instance |

 **Valeur de retour :**
EmbedAllFontsHtmlController


---


### EmbedAllFontsHtmlController {#EmbedAllFontsHtmlController}

| Nom | Description |
| --- | --- |
| EmbedAllFontsHtmlController(java.lang.String[]) | Crée une nouvelle instance |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Polices à exclure de l’incorporation |

 **Valeur de retour :**
EmbedAllFontsHtmlController


---


### writeAllFonts {#writeAllFonts}

| Nom | Description |
| --- | --- |
| writeAllFonts ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Écrit toutes les polices contenues dans la Presentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| presentation | [Presentation](../presentation) | Presentation qui est en cours de rendu. |

 **Valeur de retour :**
void


---


### writeDocumentEnd {#writeDocumentEnd}

| Nom | Description |
| --- | --- |
| writeDocumentEnd ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Appelé pour écrire le pied de page du document html. Appelé une fois par conversion de présentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| presentation | [Presentation](../presentation) | Presentation qui est en cours de rendu. |

 **Valeur de retour :**
void


---


### writeDocumentStart {#writeDocumentStart}

| Nom | Description |
| --- | --- |
| writeDocumentStart ([HtmlGenerator](../htmlgenerator), [Presentation](../presentation)) | Appelé pour écrire l’en-tête du document html. Appelé une fois par conversion de présentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| presentation | [Presentation](../presentation) | Presentation qui est en cours de rendu. |

 **Valeur de retour :**
void


---


### writeFont {#writeFont}

| Nom | Description |
| --- | --- |
| writeFont ([HtmlGenerator](../htmlgenerator), [FontData](../fontdata), [FontData](../fontdata), String, String, byte[]) | Écrit les données en base64 dans le document HTML lui-même |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Générateur HTML |
| originalFont | [FontData](../fontdata) | Police originale |
| substitutedFont | [FontData](../fontdata) | Police substituée (si la substitution de police a eu lieu), sinon null |
| fontStyle | String | Style de police |
| fontWeight | String | Poids de police |
| fontData | byte[] | Données de police |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GraphicalObject](../graphicalobject) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Connector](../connector) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Shape](../shape) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SmartArtShape](../smartartshape) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Table](../table)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Table](../table) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Ink](../ink) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GeometryShape](../geometryshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GeometryShape](../geometryshape) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SummaryZoomSection](../summaryzoomsection) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [ZoomFrame](../zoomframe) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [OleObjectFrame](../oleobjectframe) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [VideoFrame](../videoframe) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SmartArt](../smartart) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GroupShape](../groupshape) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [InkActions](../inkactions)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [InkActions](../inkactions) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [AutoShape](../autoshape) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération d’image de la diapositive en cours sera terminée, le fragment html ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [PictureFrame](../pictureframe) | Forme qui est rendue en dernier. |

 **Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ({{...}}) | ... |

| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SectionZoomFrame](../sectionzoomframe) | Forme qui est rendue en dernier. |

**Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Chart](../chart) | Forme qui est rendue en dernier. |

**Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [AudioFrame](../audioframe) | Forme qui est rendue en dernier. |

**Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [ZoomObject](../zoomobject) | Forme qui est rendue en dernier. |

**Valeur de retour :**
void


---


### writeShapeEnd {#writeShapeEnd}

| Nom | Description |
| --- | --- |
| writeShapeEnd ([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [LegacyDiagram](../legacydiagram) | Forme qui est rendue en dernier. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GraphicalObject](../graphicalobject)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GraphicalObject](../graphicalobject) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Connector](../connector)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Connector](../connector) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Shape](../shape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Shape](../shape) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SmartArtShape](../smartartshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SmartArtShape](../smartartshape) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Table](../table)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Table](../table) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Ink](../ink)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Ink](../ink) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SummaryZoomFrame](../summaryzoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GeometryShape](../geometryshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GeometryShape](../geometryshape) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SummaryZoomSection](../summaryzoomsection)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SummaryZoomSection](../summaryzoomsection) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [ZoomFrame](../zoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [ZoomFrame](../zoomframe) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [OleObjectFrame](../oleobjectframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [OleObjectFrame](../oleobjectframe) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [VideoFrame](../videoframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [VideoFrame](../videoframe) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SmartArt](../smartart)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SmartArt](../smartart) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [GroupShape](../groupshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [GroupShape](../groupshape) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [InkActions](../inkactions)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [InkActions](../inkactions) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [AutoShape](../autoshape)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [AutoShape](../autoshape) | Forme qui est sur le point d'être rendue. |

**Valeur de retour :**
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [PictureFrame](../pictureframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |
**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [PictureFrame](../pictureframe) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [SectionZoomFrame](../sectionzoomframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [SectionZoomFrame](../sectionzoomframe) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [Chart](../chart)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [Chart](../chart) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [AudioFrame](../audioframe)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [AudioFrame](../audioframe) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [ZoomObject](../zoomobject)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [ZoomObject](../zoomobject) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeShapeStart {#writeShapeStart}

| Nom | Description |
| --- | --- |
| writeShapeStart ([HtmlGenerator](../htmlgenerator), [LegacyDiagram](../legacydiagram)) | Appelé avant le rendu de la forme. Appelé une fois pour chaque forme. Si cette fonction écrit quoi que ce soit dans le générateur, la génération de l'image de la diapositive en cours sera terminée, le fragment HTML ajouté sera inséré et une nouvelle image sera démarrée au-dessus de la précédente. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| shape | [LegacyDiagram](../legacydiagram) | Forme qui est sur le point d'être rendue. |

**Retour:**  
void


---


### writeSlideEnd {#writeSlideEnd}

| Nom | Description |
| --- | --- |
| writeSlideEnd ([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | Appelé pour écrire le pied de page HTML de la diapositive. Appelé une fois pour chaque diapositive. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| slide | [Slide](../slide) | Diapositive qui est en cours de rendu. |

**Retour:**  
void


---


### writeSlideStart {#writeSlideStart}

| Nom | Description |
| --- | --- |
| writeSlideStart ([HtmlGenerator](../htmlgenerator), [Slide](../slide)) | Appelé pour écrire l'en-tête HTML de la diapositive. Appelé une fois pour chaque diapositive. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| generator | [HtmlGenerator](../htmlgenerator) | Objet de sortie. |
| slide | [Slide](../slide) | Diapositive qui est en cours de rendu. |

**Retour:**  
void


---