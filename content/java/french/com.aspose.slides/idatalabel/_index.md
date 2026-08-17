---
title: IDataLabel
second_title: Aspose.Slides pour Java Référence de l'API
description: Représente les étiquettes d'une série.
type: docs
url: /fr/com.aspose.slides/idatalabel/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Représente les étiquettes d’une série.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False signifie que l’étiquette de données n’est pas visible (et que tous les drapeaux Show*-flags (ShowValue, ...) sont false). |
| [hide()](#hide--) | Masquez l’étiquette de données en définissant tous les drapeaux Show*-flags (ShowValue, ...) à false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Renvoie le format de l’étiquette de données. |
| [getValueFromCell()](#getValueFromCell--) | Obtient ou définit la cellule de données du classeur. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtient ou définit la cellule de données du classeur. |
| [getActualLabelText()](#getActualLabelText--) | Renvoie le texte réel de l’étiquette basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False signifie que l’étiquette de données n’est pas visible (et que tous les drapeaux Show*-flags (ShowValue, ...) sont false). Booléen en lecture seule.

--------------------

Si l’étiquette de données est visible, vous pouvez la masquer avec la méthode Hide(). Mais si l’étiquette de données n’est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les drapeaux Show*-flags (ShowValue, ...) à l’état true.

**Renvoie:**  
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Masquez l’étiquette de données en définissant tous les drapeaux Show*-flags (ShowValue, ...) à false. IsVisible sera false après cela.

--------------------

Si l’étiquette de données n’est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les drapeaux Show*-flags (ShowValue, ...) à l’état true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Renvoie le format de l’étiquette de données. Lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Renvoie:**  
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

Renvoie le texte réel de l’étiquette basé sur les paramètres DataLabelFormat ou la valeur TextFrameForOverriding.Text.

**Renvoie:**  
java.lang.String - Texte réel de l’étiquette String