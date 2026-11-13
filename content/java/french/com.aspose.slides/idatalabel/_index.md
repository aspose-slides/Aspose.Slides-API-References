---
title: IDataLabel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les libellés d’une série.
type: docs
url: /fr/com.aspose.slides/idatalabel/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Représente les libellés d’une série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False signifie que l’étiquette de données n’est pas visible (et que tous les indicateurs Show*- (ShowValue, ...) sont faux). |
| [hide()](#hide--) | Masquer l’étiquette de données en définissant tous les indicateurs Show*- (ShowValue, ...) à l’état faux. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Renvoie le format de l’étiquette de données. |
| [getValueFromCell()](#getValueFromCell--) | Obtient ou définit la cellule de données du classeur. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtient ou définit la cellule de données du classeur. |
| [getActualLabelText()](#getActualLabelText--) | Renvoie le texte réel de l’étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtient ou définit le type de forme de l’étiquette de données. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtient ou définit le type de forme de l’étiquette de données. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False signifie que l’étiquette de données n’est pas visible (et que tous les indicateurs Show*- (ShowValue, ...) sont faux). Booléen en lecture seule.

--------------------

Si l’étiquette de données est visible, vous pouvez la masquer avec la méthode Hide(). Mais si l’étiquette de données n’est pas visible (IsVisible est false) vous pouvez rendre l’étiquette visible en définissant les indicateurs Show*- (ShowValue, ...) à l’état vrai.

**Retourne :**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Masquer l’étiquette de données en définissant tous les indicateurs Show*- (ShowValue, ...) à l’état faux. IsVisible sera false après cela.

--------------------

Si l’étiquette de données n’est pas visible (IsVisible est false) vous pouvez rendre l’étiquette visible en définissant les indicateurs Show*- (ShowValue, ...) à l’état vrai.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Renvoie le format de l’étiquette de données. En lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retourne :**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Retourne :**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Renvoie le texte réel de l’étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text.

**Retourne :**
java.lang.String - Chaîne du texte réel de l’étiquette
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Obtient ou définit le type de forme de l’étiquette de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n’est définie.

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

**Retourne :**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Obtient ou définit le type de forme de l’étiquette de données. Renvoie [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) si aucune forme n’est définie.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |