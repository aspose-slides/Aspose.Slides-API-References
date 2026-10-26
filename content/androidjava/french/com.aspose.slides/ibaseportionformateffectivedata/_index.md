---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de base pour les objets immuables contenant les propriétés de formatage effectif des portions de texte.
type: docs
url: /fr/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Interface de base pour les objets immuables contenant les propriétés de formatage effectif des portions de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Renvoie les propriétés LineFormat pour le contour du texte. |
| [getFillFormat()](#getFillFormat--) | Renvoie les propriétés FillFormat du texte. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie les propriétés EffectFormat du texte. |
| [getHighlightColor()](#getHighlightColor--) | Renvoie la couleur utilisée pour mettre en évidence un texte. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Renvoie les propriétés FillFormat de la ligne de soulignement. |
| [getFontBold()](#getFontBold--) | Détermine si la police est en gras. |
| [getFontItalic()](#getFontItalic--) | Détermine si la police est en italique. |
| [getKumimoji()](#getKumimoji--) | Détermine si les chiffres doivent ignorer la disposition verticale du texte spécifique aux langues orientales. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Détermine si la hauteur d'un texte doit être normalisée. |
| [getProofDisabled()](#getProofDisabled--) | Détermine si le texte ne doit pas être vérifié. |
| [getFontUnderline()](#getFontUnderline--) | Renvoie le type de soulignement du texte. |
| [getTextCapType()](#getTextCapType--) | Renvoie le type de capitalisation du texte. |
| [getStrikethroughType()](#getStrikethroughType--) | Renvoie le type de barré d'un texte. |
| [getSmartTagClean()](#getSmartTagClean--) | Détermine si la balise intelligente doit être nettoyée. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. |
| [getFontHeight()](#getFontHeight--) | Renvoie la hauteur de la police de la portion de texte, en points. |
| [getLatinFont()](#getLatinFont--) | Renvoie les informations de la police Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Renvoie les informations de la police Est-asiatique. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Renvoie les informations de la police script complexe. |
| [getSymbolFont()](#getSymbolFont--) | Renvoie les informations de la police symbolique. |
| [getEscapement()](#getEscapement--) | Renvoie le texte en exposant ou en indice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Renvoie la taille minimale de police pour laquelle le crénage doit être activé. |
| [getLanguageId()](#getLanguageId--) | Renvoie l'Id d'une langue. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Renvoie l'Id d'une langue alternative. |
| [getSpacing()](#getSpacing--) | Renvoie l'incrément d'espacement inter-caractères, en points. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Renvoie les propriétés LineFormat pour le contour du texte. Lecture seule [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Renvoie:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Renvoie les propriétés FillFormat du texte. Lecture seule [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Renvoie:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Renvoie les propriétés EffectFormat du texte. Lecture seule [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Renvoie:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)

### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

Renvoie la couleur utilisée pour mettre en évidence un texte. Lecture seule java.lang.Integer.

**Renvoie:**
java.lang.Integer

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Lecture seule [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Renvoie:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Renvoie les propriétés FillFormat de la ligne de soulignement. Lecture seule [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Renvoie:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)

### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Détermine si la police est en gras. Lecture seule boolean.

**Renvoie:**
boolean

### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Détermine si la police est en italique. Lecture seule boolean.

**Renvoie:**
boolean

### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Détermine si les chiffres doivent ignorer la disposition verticale du texte spécifique aux langues orientales. Lecture seule boolean.

**Renvoie:**
boolean

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Détermine si la hauteur d'un texte doit être normalisée. Lecture seule boolean.

**Renvoie:**
boolean

### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Détermine si le texte ne doit pas être vérifié. Lecture seule boolean.

**Renvoie:**
boolean

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Renvoie le type de soulignement du texte. Lecture seule [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Renvoie:**
byte

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Renvoie le type de capitalisation du texte. Lecture seule [TextCapType](../../com.aspose.slides/textcaptype).

**Renvoie:**
byte

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Renvoie le type de barré d'un texte. Lecture seule [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Renvoie:**
byte

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Détermine si la balise intelligente doit être nettoyée. Lecture seule boolean.

**Renvoie:**
boolean

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture seule boolean.

**Renvoie:**
boolean

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture seule boolean.

**Renvoie:**
boolean

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Renvoie la hauteur de la police de la portion de texte, en points. Lecture seule float.

**Renvoie:**
float

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Renvoie les informations de la police Latin. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Renvoie les informations de la police Est-asiatique. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Renvoie les informations de la police script complexe. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Renvoie les informations de la police symbolique. Lecture seule [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie:**
[IFontData](../../com.aspose.slides/ifontdata)

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Renvoie le texte en exposant ou en indice. Valeur de -100 % (indice) à 100 % (exposant). Lecture seule float.

**Renvoie:**
float

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Renvoie la taille minimale de police pour laquelle le crénage doit être activé. Lecture seule float.

**Renvoie:**
float

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Renvoie l'Id d'une langue. Lecture seule String.

**Renvoie:**
java.lang.String

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Renvoie l'Id d'une langue alternative. Lecture seule String.

**Renvoie:**
java.lang.String

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Renvoie l'incrément d'espacement inter-caractères, en points. Lecture seule float.

**Renvoie:**
float