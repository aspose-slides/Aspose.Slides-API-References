---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: Le graphique fonctionne avec un ensemble restreint de propriétés de format de texte.
type: docs
url: /fr/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Le graphique fonctionne avec un ensemble restreint de propriétés de format de texte. Les interfaces IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat décrivent cet ensemble restreint.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Renvoie le format des éléments de texte du graphique. |
| [getParagraphFormat()](#getParagraphFormat--) | Renvoie le format du paragraphe. |
| [getPortionFormat()](#getPortionFormat--) | Renvoie le format de la portion. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copie le format du texte vers le cadre de texte spécifié. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copie le format du texte depuis le cadre de texte spécifié. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Renvoie le format des éléments de texte du graphique. Lecture seule [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Renvoie :**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Renvoie le format du paragraphe. Lecture seule [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Renvoie :**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Renvoie le format de la portion. Lecture seule [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Renvoie :**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Copie le format du texte vers le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte vers lequel le format du texte sera copié. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Copie le format du texte depuis le cadre de texte spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Cadre de texte dont le format du texte sera copié. |