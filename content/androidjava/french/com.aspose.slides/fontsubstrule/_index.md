---
title: FontSubstRule
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente les informations de substitution de police
type: docs
url: /fr/com.aspose.slides/fontsubstrule/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Représente les informations de substitution de police
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Crée une nouvelle instance. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Crée une nouvelle instance. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Police à substituer. |
| [getDestFont()](#getDestFont--) | Police à utiliser pour la substitution. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Règle à appliquer pour la substitution. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

Crée une nouvelle instance.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Police source. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Police de destination. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

Crée une nouvelle instance.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Police source. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Police de destination. |
| fontSubstRule | int | Règle de substitution de police. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

Police à substituer. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

Police à utiliser pour la substitution. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

Règle à appliquer pour la substitution. Lecture seule [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Renvoie:**
int