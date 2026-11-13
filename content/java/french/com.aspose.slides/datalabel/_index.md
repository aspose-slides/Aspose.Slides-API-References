---
title: DataLabel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les étiquettes de série.
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

Représente les étiquettes de série.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Crée une nouvelle instance de la classe DataLabel. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [isVisible()](#isVisible--) | False signifie que l'étiquette de données n'est pas visible (et que tous les indicateurs Show*-flags (ShowValue, ...) sont faux). |
| [hide()](#hide--) | Masque l'étiquette de données en réglant tous les indicateurs Show*-flags (ShowValue, ...) sur l'état faux. |
| [getActualLabelText()](#getActualLabelText--) | Renvoie le texte réel de l'étiquette en fonction des paramètres de DataLabelFormat ou de la valeur Text de TextFrameForOverriding. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialise TextFrameForOverriding avec le texte du paramètre "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Peut contenir un texte richement formaté. |
| [getTextFormat()](#getTextFormat--) | Renvoie le format du texte. |
| [getX()](#getX--) | Renvoie ou définit la coordonnée x d'un titre en fraction de la largeur du graphique. |
| [setX(float value)](#setX-float-) | Renvoie ou définit la coordonnée x d'un titre en fraction de la largeur du graphique. |
| [getY()](#getY--) | Renvoie ou définit la coordonnée y d'un titre en fraction de la hauteur du graphique. |
| [setY(float value)](#setY-float-) | Renvoie ou définit la coordonnée y d'un titre en fraction de la hauteur du graphique. |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d'un titre en fraction de la largeur du graphique. |
| [setWidth(float value)](#setWidth-float-) | Renvoie ou définit la largeur d'un titre en fraction de la largeur du graphique. |
| [getHeight()](#getHeight--) | Renvoie ou définit la hauteur d'un titre en fraction de la hauteur du graphique. |
| [setHeight(float value)](#setHeight-float-) | Renvoie ou définit la hauteur d'un titre en fraction de la hauteur du graphique. |
| [getRight()](#getRight--) | Droite. |
| [getBottom()](#getBottom--) | Bas. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Renvoie le format de l'étiquette de données. |
| [getValueFromCell()](#getValueFromCell--) | Obtient ou définit la cellule de données du classeur. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtient ou définit la cellule de données du classeur. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtient ou définit le type de forme de l'étiquette de données. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtient ou définit le type de forme de l'étiquette de données. |
| [getActualX()](#getActualX--) | Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualY()](#getActualY--) | Spécifie le sommet réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. |
| [getActualWidth()](#getActualWidth--) | Spécifie la largeur réelle de l'élément du graphique. |
| [getActualHeight()](#getActualHeight--) | Spécifie la hauteur réelle de l'élément du graphique. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d'un FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Crée une nouvelle instance de la classe DataLabel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Parent ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False signifie que l'étiquette de données n'est pas visible (et que tous les indicateurs Show*-flags (ShowValue, ...) sont faux). Lecture seule boolean.

**Renvoie :**
boolean
--------------------

Si l'étiquette de données est visible, vous pouvez la masquer avec la méthode Hide(). Mais si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les indicateurs Show*-flags (ShowValue, ...) sur l'état vrai.

**Renvoie :**
boolean
### hide() {#hide--}
```
public final void hide()
```

Masque l'étiquette de données en réglant tous les indicateurs Show*-flags (ShowValue, ...) sur l'état faux. IsVisible sera false après cela.

--------------------

Si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les indicateurs Show*-flags (ShowValue, ...) sur l'état vrai.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Renvoie le texte réel de l'étiquette en fonction des paramètres de DataLabelFormat ou de la valeur Text de TextFrameForOverriding.

**Renvoie :**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Initialise TextFrameForOverriding avec le texte du paramètre "text". Si TextFrameForOverriding est déjà initialisé, il modifie simplement son texte.

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

Peut contenir un texte richement formaté. Si cette propriété n'est pas nulle, alors cette valeur de texte formaté remplace le texte auto-généré de l'étiquette de données. Le texte auto-généré de l'étiquette de données signifie le texte géré par les propriétés ShowSeriesName, ShowValue, ... et est formaté avec la propriété TextFormat du TextFormatManager. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

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

Renvoie ou définit la coordonnée x d'un titre en fraction de la largeur du graphique. Lecture/écriture float.

**Renvoie :**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Renvoie ou définit la coordonnée x d'un titre en fraction de la largeur du graphique. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Renvoie ou définit la coordonnée y d'un titre en fraction de la hauteur du graphique. Lecture/écriture float.

**Renvoie :**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Renvoie ou définit la coordonnée y d'un titre en fraction de la hauteur du graphique. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Renvoie ou définit la largeur d'un titre en fraction de la largeur du graphique. Lecture/écriture float.

**Renvoie :**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Renvoie ou définit la largeur d'un titre en fraction de la largeur du graphique. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Renvoie ou définit la hauteur d'un titre en fraction de la hauteur du graphique. Lecture/écriture float.

**Renvoie :**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Renvoie ou définit la hauteur d'un titre en fraction de la hauteur du graphique. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Droite. Lecture seule float.

**Renvoie :**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Bas. Lecture seule float.

**Renvoie :**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Renvoie le format de l'étiquette de données. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

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
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Obtient ou définit le type de forme de l'étiquette de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n'est définie.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Définir le type de forme de la première étiquette de données sur Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Obtient ou définit le type de forme de l'étiquette de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n'est définie.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Définir le type de forme de la première étiquette de données sur Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Spécifie la position x réelle (gauche) de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Renvoie :**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Spécifie le sommet réel de l'élément du graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Renvoie :**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Spécifie la largeur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Renvoie :**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Spécifie la hauteur réelle de l'élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant de récupérer les valeurs réelles. Lecture float.

**Renvoie :**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)