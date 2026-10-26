---
title: IChartTextFormat
second_title: Aspose.Slides pour Android via Java – Référence API
description: Le graphique fonctionne avec un ensemble restreint de propriétés de format de texte.
type: docs
url: /fr/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Le graphique fonctionne avec un ensemble restreint de propriétés de format de texte. Les interfaces IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat décrivent cet ensemble limité.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Retourne le format des éléments de texte du graphique. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourne le format du paragraphe. |
| [getPortionFormat()](#getPortionFormat--) | Retourne le format de la portion. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copie le format de texte dans le cadre de texte spécifié. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copie le format de texte depuis le cadre de texte spécifié. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Retourne le format des éléments de texte du graphique. Lecture seule [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retourne :**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Retourne le format du paragraphe. Lecture seule [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retourne :**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Retourne le format de la portion. Lecture seule [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retourne :**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Copie le format de texte dans le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte dans lequel copier le format de texte. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Copie le format de texte depuis le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte dont copier le format de texte. |