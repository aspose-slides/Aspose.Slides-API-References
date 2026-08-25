---
title: TextFrame
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/textframe/
---
## TextFrame classe

  Représente un TextFrame.
 
### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries () | Fournit un accès facile aux hyperliens contenus. Lecture seule IHyperlinkQueries. |

 **Renvoie:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs () | Renvoie la liste de tous les paragraphes d'un cadre. Lecture seule IParagraphCollection. |

 **Renvoie:**
[ParagraphCollection](../paragraphcollection)


---


### getParentCell {#getParentCell}

| Name | Description |
| --- | --- |
| getParentCell () | Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface ICell. Lecture seule ICell. |

 **Renvoie:**
[Cell](../cell)


---


### getParentShape {#getParentShape}

| Name | Description |
| --- | --- |
| getParentShape () | Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape. Lecture seule IShape. |

 **Renvoie:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d'un TextFrame. Lecture seule IPresentation. |

 **Renvoie:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d'un TextFrame. Lecture seule IBaseSlide. |

 **Renvoie:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String. Valeur : le texte. |

 **Renvoie:**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| Name | Description |
| --- | --- |
| getTextFrameFormat () | Renvoie l'objet de formatage pour cet objet TextFrame. Lecture seule ITextFrameFormat. |

 **Renvoie:**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| regex | String | Texte de l'expression régulière pour obtenir le texte à mettre en évidence. |
| highlightColor | Color | La couleur pour mettre en évidence le texte. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Options de mise en évidence. |

 **Renvoie:**
void


---


### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à mettre en évidence. |
| highlightColor | Color | La couleur pour mettre en évidence le texte. |
| callback | [IFindResultCallback](../ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |

 **Renvoie:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Texte d'exemple à mettre en évidence. |
| highlightColor | Color | La couleur pour mettre en évidence le texte. |

 **Renvoie:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Le texte à mettre en évidence. |
| highlightColor | Color | La couleur pour mettre en évidence le texte. |
| options | [TextHighlightingOptions](../texthighlightingoptions) | Options de mise en évidence. |

 **Renvoie:**
void


---


### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Le texte à mettre en évidence. |
| highlightColor | Color | La couleur pour mettre en évidence le texte. |
| options | [TextSearchOptions](../textsearchoptions) | Options de recherche de texte ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche IFindResultCallback. |

 **Renvoie:**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Fusionne les portions avec le même formatage dans tous les paragraphes. |

 **Renvoie:**
void


---


### replaceRegex {#replaceRegex}

| Name | Description |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | String | La chaîne pour remplacer toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../ifindresultcallback) | Objet de rappel pour enregistrer le résultat de l'opération de remplacement IFindResultCallback. |

 **Renvoie:**
void


---


### replaceText {#replaceText}

| Name | Description |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| oldText | String | La chaîne à remplacer. |
| newText | String | La chaîne pour remplacer toutes les occurrences d'oldText. |
| options | [TextSearchOptions](../textsearchoptions) | Options de recherche de texte ITextSearchOptions. |
| callback | [IFindResultCallback](../ifindresultcallback) | Objet de rappel pour enregistrer le résultat de l'opération de remplacement IFindResultCallback. |

 **Renvoie:**
void


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String. Valeur : le texte. |

 **Renvoie:**
void


---


### splitTextByColumns {#splitTextByColumns}

| Name | Description |
| --- | --- |
| splitTextByColumns () | Divise le contenu texte de l'ITextFrame en un tableau de chaînes, chaque élément correspondant à une colonne de texte distincte dans le cadre. |

 **Renvoie:**
String


---