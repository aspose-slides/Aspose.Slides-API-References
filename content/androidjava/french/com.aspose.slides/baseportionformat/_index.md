---
title: BasePortionFormat
second_title: Aspose.Slides pour Android via la Référence de l'API Java
description: Propriétés communes de mise en forme des portions de texte.
type: docs
url: /fr/com.aspose.slides/baseportionformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Propriétés de mise en forme de portion de texte communes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Renvoie les propriétés LineFormat pour le contour du texte. |
| [getFillFormat()](#getFillFormat--) | Renvoie les propriétés FillFormat du texte. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie les propriétés EffectFormat du texte. |
| [getHighlightColor()](#getHighlightColor--) | Renvoie la couleur utilisée pour mettre en évidence un texte. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Renvoie les propriétés FillFormat de la ligne de soulignement. |
| [getFontBold()](#getFontBold--) | Détermine si la police est en gras. |
| [setFontBold(byte value)](#setFontBold-byte-) | Détermine si la police est en gras. |
| [getFontItalic()](#getFontItalic--) | Détermine si la police est italique. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Détermine si la police est italique. |
| [getKumimoji()](#getKumimoji--) | Détermine si les chiffres doivent ignorer la disposition verticale du texte propre aux langues orientales. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Détermine si les chiffres doivent ignorer la disposition verticale du texte propre aux langues orientales. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Détermine si la hauteur d'un texte doit être normalisée. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Détermine si la hauteur d'un texte doit être normalisée. |
| [getProofDisabled()](#getProofDisabled--) | Détermine si le texte ne doit pas être vérifié. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Détermine si le texte ne doit pas être vérifié. |
| [getFontUnderline()](#getFontUnderline--) | Renvoie ou définit le type de soulignement du texte. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Renvoie ou définit le type de soulignement du texte. |
| [getTextCapType()](#getTextCapType--) | Renvoie ou définit le type de capitalisation du texte. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Renvoie ou définit le type de capitalisation du texte. |
| [getStrikethroughType()](#getStrikethroughType--) | Renvoie ou définit le type de barré d'un texte. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Renvoie ou définit le type de barré d'un texte. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. |
| [getFontHeight()](#getFontHeight--) | Renvoie ou définit la hauteur de police d'une portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Renvoie ou définit la hauteur de police d'une portion. |
| [getLatinFont()](#getLatinFont--) | Renvoie ou définit les informations de police Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Renvoie ou définit les informations de police Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Renvoie ou définit les informations de police Est-Asiatique. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Renvoie ou définit les informations de police Est-Asiatique. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Renvoie ou définit les informations de police de script complexe. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Renvoie ou définit les informations de police de script complexe. |
| [getSymbolFont()](#getSymbolFont--) | Renvoie ou définit les informations de police symbolique. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Renvoie ou définit les informations de police symbolique. |
| [getEscapement()](#getEscapement--) | Renvoie ou définit le texte en exposant ou indice. |
| [setEscapement(float value)](#setEscapement-float-) | Renvoie ou définit le texte en exposant ou indice. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. |
| [getLanguageId()](#getLanguageId--) | Renvoie ou définit l'Id d'une langue de vérification. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Renvoie ou définit l'Id d'une langue de vérification. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Renvoie ou définit l'Id d'une langue alternative. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Renvoie ou définit l'Id d'une langue alternative. |
| [getSpacing()](#getSpacing--) | Renvoie ou définit l'incrément d'espacement inter-caractères. |
| [setSpacing(float value)](#setSpacing-float-) | Renvoie ou définit l'incrément d'espacement inter-caractères. |
| [getSpellCheck()](#getSpellCheck--) | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Détermine si les chiffres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Détermine si les chiffres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Détermine si le texte ne doit pas être vérifié. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Détermine si le texte ne doit pas être vérifié. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Renvoie :**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [TextCapType](../../com.aspose.slides/textcaptype).

**Renvoie :**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [TextCapType](../../com.aspose.slides/textcaptype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Renvoie ou définit le type de barré d'un texte. Aucun héritage appliqué. Lecture/écriture [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Renvoie :**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Renvoie ou définit le type de barré d'un texte. Aucun héritage appliqué. Lecture/écriture [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Renvoie ou définit la hauteur de police d'une portion. **Float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Renvoie :**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Renvoie ou définit la hauteur de police d'une portion. **Float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Renvoie ou définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Renvoie ou définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Renvoie ou définit les informations de police Est-Asiatique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Renvoie ou définit les informations de police Est-Asiatique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Renvoie ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Renvoie ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Renvoie ou définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Renvoie :**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Renvoie ou définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Renvoie :**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Renvoie ou définit l'Id d'une langue de vérification. Utilisé pour la vérification orthographique et grammaticale. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Renvoie ou définit l'Id d'une langue de vérification. Utilisé pour la vérification orthographique et grammaticale. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Renvoie ou définit l'Id d'une langue alternative. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Renvoie ou définit l'Id d'une langue alternative. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Renvoie ou définit l'incrément d'espacement inter-caractères. **Float.NaN** signifie que la valeur est indéfinie et doit être hérité du Master. Lecture/écriture  float .

**Renvoie :**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Renvoie ou définit l'incrément d'espacement inter-caractères. **Float.NaN** signifie que la valeur est indéfinie et doit être hérité du Master. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Accéder à la première portion de texte à l'intérieur de la première forme de la première diapositive
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Activer la vérification orthographique pour cette portion de texte
>      portion.getPortionFormat().setSpellCheck(true);
>      // Enregistrer la présentation modifiée
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public final void setSpellCheck(boolean value)

Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |