---
title: DataLabel
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les étiquettes d'une série.
type: docs
url: /fr/com.aspose.slides/datalabel/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Représente des étiquettes de série.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Crée une nouvelle instance de la classe DataLabel. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Renvoie le diagramme parent. |
| [isVisible()](#isVisible--) | False signifie que l’étiquette de données n’est pas visible (et que tous les indicateurs Show\*-flags (ShowValue, …) sont à false). |
| [hide()](#hide--) | Rend l’étiquette de données cachée en définissant tous les indicateurs Show\*-flags (ShowValue, …) à l’état false. |
| [getActualLabelText()](#getActualLabelText--) | Renvoie le texte réel de l’étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialise TextFrameForOverriding avec le texte du paramètre « text ». |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Peut contenir un texte richement formaté. |
| [getTextFormat()](#getTextFormat--) | Renvoie le format du texte. |
| [getX()](#getX--) | Renvoie ou définit la coordonnée x d’un titre en tant que fraction de la largeur du diagramme. |
| [setX(float value)](#setX-float-) | Renvoie ou définit la coordonnée x d’un titre en tant que fraction de la largeur du diagramme. |
| [getY()](#getY--) | Renvoie ou définit la coordonnée y d’un titre en tant que fraction de la hauteur du diagramme. |
| [setY(float value)](#setY-float-) | Renvoie ou définit la coordonnée y d’un titre en tant que fraction de la hauteur du diagramme. |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d’un titre en tant que fraction de la largeur du diagramme. |
| [setWidth(float value)](#setWidth-float-) | Renvoie ou définit la largeur d’un titre en tant que fraction de la largeur du diagramme. |
| [getHeight()](#getHeight--) | Renvoie ou définit la hauteur d’un titre en tant que fraction de la hauteur du diagramme. |
| [setHeight(float value)](#setHeight-float-) | Renvoie ou définit la hauteur d’un titre en tant que fraction de la hauteur du diagramme. |
| [getRight()](#getRight--) | Droite. |
| [getBottom()](#getBottom--) | Bas. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Renvoie le format d’étiquette de données. |
| [getValueFromCell()](#getValueFromCell--) | Obtient ou définit la cellule de données du classeur. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtient ou définit la cellule de données du classeur. |
| [getActualX()](#getActualX--) | Spécifie la position x réelle (gauche) de l’élément du diagramme par rapport au coin supérieur gauche du diagramme. |
| [getActualY()](#getActualY--) | Spécifie le haut réel de l’élément du diagramme par rapport au coin supérieur gauche du diagramme. |
| [getActualWidth()](#getActualWidth--) | Spécifie la largeur réelle de l’élément du diagramme. |
| [getActualHeight()](#getActualHeight--) | Spécifie la hauteur réelle de l’élément du diagramme. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d’un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d’un FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Crée une nouvelle instance de la classe DataLabel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint parent. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le diagramme parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False signifie que l’étiquette de données n’est pas visible (et que tous les indicateurs Show\*-flags (ShowValue, …) sont à false). Lecture seule  boolean .

**Renvoie :**
boolean
### hide() {#hide--}
```
public final void hide()
```

Rend l’étiquette de données cachée en définissant tous les indicateurs Show\*-flags (ShowValue, …) à l’état false. IsVisible sera false après cela.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Renvoie le texte réel de l’étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text.

**Renvoie :**
java.lang.String - L’objet java.lang.String.
### addTextFrameForOverriding(java.lang.String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialise TextFrameForOverriding avec le texte du paramètre « text ». Si TextFrameForOverriding est déjà initialisé, alors il modifie simplement son texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte pour un nouveau TextFrameForOverriding. |

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Peut contenir un texte richement formaté. Si cette propriété n’est pas nulle, alors cette valeur de texte formaté remplace le texte auto-généré de l’étiquette de données. Le texte auto-généré de l’étiquette de données désigne le texte géré par les propriétés ShowSeriesName, ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Renvoie le format du texte. Lecture seule [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Renvoie :**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Renvoie ou définit la coordonnée x d’un titre en tant que fraction de la largeur du diagramme. Lecture/écriture  float .

**Renvoie :**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Renvoie ou définit la coordonnée x d’un titre en tant que fraction de la largeur du diagramme. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Renvoie ou définit la coordonnée y d’un titre en tant que fraction de la hauteur du diagramme. Lecture/écriture  float .

**Renvoie :**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Renvoie ou définit la coordonnée y d’un titre en tant que fraction de la hauteur du diagramme. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Renvoie ou définit la largeur d’un titre en tant que fraction de la largeur du diagramme. Lecture/écriture  float .

**Renvoie :**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Renvoie ou définit la largeur d’un titre en tant que fraction de la largeur du diagramme. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Renvoie ou définit la hauteur d’un titre en tant que fraction de la hauteur du diagramme. Lecture/écriture  float .

**Renvoie :**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Renvoie ou définit la hauteur d’un titre en tant que fraction de la hauteur du diagramme. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Droite. Lecture seule  float .

**Renvoie :**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Bas. Lecture seule  float .

**Renvoie :**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Renvoie le format d’étiquette de données. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie :**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Renvoie :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Spécifie la position x réelle (gauche) de l’élément du diagramme par rapport au coin supérieur gauche du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture  float .

**Renvoie :**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Spécifie le haut réel de l’élément du diagramme par rapport au coin supérieur gauche du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture  float .

**Renvoie :**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Spécifie la largeur réelle de l’élément du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture  float .

**Renvoie :**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Spécifie la hauteur réelle de l’élément du diagramme. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture  float .

**Renvoie :**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente d’un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d’un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)