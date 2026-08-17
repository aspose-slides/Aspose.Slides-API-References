---
title: ChartTextFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie le formatage de texte par défaut pour les éléments de texte du diagramme.
type: docs
url: /fr/com.aspose.slides/charttextformat/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Spécifie le formatage de texte par défaut pour les éléments de texte du diagramme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copie le format de texte vers le cadre de texte spécifié. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copie le format de texte depuis le cadre de texte spécifié. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Lecture seule [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Renvoie :**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Lecture seule [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Renvoie :**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Lecture seule [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Renvoie :**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Copie le format de texte vers le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte vers lequel copier le format de texte. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Copie le format de texte depuis le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte à partir duquel copier le format de texte. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject