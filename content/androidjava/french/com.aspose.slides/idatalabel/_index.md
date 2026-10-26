---
title: IDataLabel
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente des étiquettes de série.
type: docs
url: /fr/com.aspose.slides/idatalabel/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)  
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Représente des étiquettes de série.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False signifie que l'étiquette de données n'est pas visible (et ainsi tous les indicateurs Show\*-flags (ShowValue, ...) sont false). |
| [hide()](#hide--) | Masquer l'étiquette de données en réglant tous les indicateurs Show\*-flags (ShowValue, ...) à l'état false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Renvoie le format de l'étiquette de données. |
| [getValueFromCell()](#getValueFromCell--) | Obtient ou définit la cellule de données du classeur. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtient ou définit la cellule de données du classeur. |
| [getActualLabelText()](#getActualLabelText--) | Renvoie le texte réel de l'étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False signifie que l'étiquette de données n'est pas visible (et ainsi tous les indicateurs Show\*-flags (ShowValue, ...) sont false). Booléen en lecture seule.

--------------------

Si l'étiquette de données est visible, vous pouvez la masquer avec la méthode Hide(). Mais si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les indicateurs Show\*-flags (ShowValue, ...) à l'état true.

**Renvoie :**  
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Masquer l'étiquette de données en réglant tous les indicateurs Show\*-flags (ShowValue, ...) à l'état false. IsVisible sera false après cela.

--------------------

Si l'étiquette de données n'est pas visible (IsVisible est false), vous pouvez la rendre visible en réglant les indicateurs Show\*-flags (ShowValue, ...) à l'état true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Renvoie le format de l'étiquette de données. En lecture seule [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Renvoie :**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtient ou définit la cellule de données du classeur. Appliqué si la propriété IDataLabelFormat.ShowLabelValueFromCell est vraie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Renvoie le texte réel de l'étiquette en fonction des paramètres DataLabelFormat ou de la valeur TextFrameForOverriding.Text.

**Renvoie :**  
java.lang.String - Texte réel de l'étiquette String