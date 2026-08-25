---
title: DataLabel
second_title: Aspose.Slides pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/datalabel/
---
## DataLabel classe

Représente les étiquettes d'une série.

### DataLabel {#DataLabel}

| Name | Description |
| --- | --- |
| DataLabel([ChartDataPoint](../chartdatapoint)) | Crée une nouvelle instance de la classe DataLabel. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint](../chartdatapoint) | Parent ChartDataPoint. |

**Valeur de retour :**
DataLabel


---

### addTextFrameForOverriding {#addTextFrameForOverriding}

| Name | Description |
| --- | --- |
| addTextFrameForOverriding (String) | Initialise TextFrameForOverriding avec le texte du paramètre "text". Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Texte pour un nouveau TextFrameForOverriding. |

**Valeur de retour :**
[TextFrame](../textframe)

---

### getActualHeight {#getActualHeight}

| Name | Description |
| --- | --- |
| getActualHeight () | Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

**Valeur de retour :**
float

---

### getActualLabelText {#getActualLabelText}

| Name | Description |
| --- | --- |
| getActualLabelText () | Renvoie le texte réel de l'étiquette basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text. |

**Valeur de retour :**
String

---

### getActualWidth {#getActualWidth}

| Name | Description |
| --- | --- |
| getActualWidth () | Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

**Valeur de retour :**
float

---

### getActualX {#getActualX}

| Name | Description |
| --- | --- |
| getActualX () | Spécifie la position x réelle (gauche) de l'élément du graphique relative au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

**Valeur de retour :**
float

---

### getActualY {#getActualY}

| Name | Description |
| --- | --- |
| getActualY () | Spécifie le haut réel de l'élément du graphique relatif au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float. |

**Valeur de retour :**
float

---

### getBottom {#getBottom}

| Name | Description |
| --- | --- |
| getBottom () | Bas. Lecture seule float. |

**Valeur de retour :**
float

---

### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Renvoie le graphique parent. Lecture seule IChart. |

**Valeur de retour :**
[Chart](../chart)

---

### getDataLabelFormat {#getDataLabelFormat}

| Name | Description |
| --- | --- |
| getDataLabelFormat () | Renvoie le format d'étiquette de données. Lecture seule IDataLabelFormat. |

**Valeur de retour :**
[DataLabelFormat](../datalabelformat)

---

### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Renvoie ou définit la hauteur d'un titre en fonction de la hauteur du graphique. Lecture/écriture float. |

**Valeur de retour :**
float

---

### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parent d'un FillFormat. Lecture seule IPresentation. |

**Valeur de retour :**
[Presentation](../presentation)

---

### getRight {#getRight}

| Name | Description |
| --- | --- |
| getRight () | Droite. Lecture seule float. |

**Valeur de retour :**
float

---

### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parent d'un FillFormat. Lecture seule BaseSlide. |

**Valeur de retour :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Renvoie le format du texte. Lecture seule IChartTextFormat. |

**Valeur de retour :**
[ChartTextFormat](../charttextformat)

---

### getTextFrameForOverriding {#getTextFrameForOverriding}

| Name | Description |
| --- | --- |
| getTextFrameForOverriding () | Peut contenir un texte richement formaté. Si cette propriété n'est pas nulle, alors cette valeur de texte formaté remplace le texte auto-généré de l'étiquette de données. Le texte auto-généré de l'étiquette de données signifie le texte géré par les propriétés ShowSeriesName, ShowValue, ... et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule ITextFrame. |

**Valeur de retour :**
[TextFrame](../textframe)

---

### getValueFromCell {#getValueFromCell}

| Name | Description |
| --- | --- |
| getValueFromCell () | Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie. |

**Valeur de retour :**
[ChartDataCell](../chartdatacell)

---

### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Renvoie ou définit la largeur d'un titre en fonction de la largeur du graphique. Lecture/écriture float. |

**Valeur de retour :**
float

---

### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | Renvoie ou définit la coordonnée x d'un titre en fonction de la largeur du graphique. Lecture/écriture float. |

**Valeur de retour :**
float

---

### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | Renvoie ou définit la coordonnée y d'un titre en fonction de la hauteur du graphique. Lecture/écriture float. |

**Valeur de retour :**
float

---

### hide {#hide}

| Name | Description |
| --- | --- |
| hide () | Masque l'étiquette de données en définissant tous les indicateurs Show* (ShowValue, ...) à l'état false. IsVisible sera false après cela. Si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en définissant les indicateurs Show* (ShowValue, ...) à l'état true. |

**Valeur de retour :**
void

---

### isVisible {#isVisible}

| Name | Description |
| --- | --- |
| isVisible () | False signifie que l'étiquette de données n'est pas visible (et que donc tous les indicateurs Show* (ShowValue, ...) sont false). Lecture seule boolean. Si l'étiquette de données est visible, vous pouvez la masquer avec la méthode Hide(). Mais si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en définissant les indicateurs Show* (ShowValue, ...) à l'état true. |

**Valeur de retour :**
boolean

---

### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Renvoie ou définit la hauteur d'un titre en fonction de la hauteur du graphique. Lecture/écriture float. |

**Valeur de retour :**
void

---

### setValueFromCell {#setValueFromCell}

| Name | Description |
| --- | --- |
| setValueFromCell ([ChartDataCell](../chartdatacell)) | Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie. |

**Valeur de retour :**
void

---

### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth (float) | Renvoie ou définit la largeur d'un titre en fonction de la largeur du graphique. Lecture/écriture float. |

**Valeur de retour :**
void

---

### setX {#setX}

| Name | Description |
| --- | --- |
| setX (float) | Renvoie ou définit la coordonnée x d'un titre en fonction de la largeur du graphique. Lecture/écriture float. |

**Valeur de retour :**
void

---

### setY {#setY}

| Name | Description |
| --- | --- |
| setY (float) | Renvoie ou définit la coordonnée y d'un titre en fonction de la hauteur du graphique. Lecture/écriture float. |

**Valeur de retour :**
void

---