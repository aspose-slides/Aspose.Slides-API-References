---
title: IBasePortionFormat
second_title: Aspose.Slides pour Android via Java API Reference
description: Cette classe contient les propriétés de mise en forme de la portion de texte.
type: docs
url: /fr/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Cette classe contient les propriétés de mise en forme de la portion de texte. Contrairement à [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour obtenir et manipuler les propriétés de mise en forme de la portion de texte définies pour la portion particulière. Cela signifie qu’aucune héritage n’est appliqué lors de la récupération des valeurs, si bien que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Pour obtenir les valeurs effectives des paramètres de mise en forme, y compris celles héritées, vous devez utiliser la méthode [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) qui renvoie une instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Methods

| Méthode | Description |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat properties for text outlining. |
| [getFillFormat()](#getFillFormat--) | Returns the text FillFormat properties. |
| [getEffectFormat()](#getEffectFormat--) | Returns the text EffectFormat properties. |
| [getHighlightColor()](#getHighlightColor--) | Returns the color used to highlight a text. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Returns the LineFormat properties used to outline underline line. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Returns the underline line FillFormat properties. |
| [getFontBold()](#getFontBold--) | Determines whether the font is bold. |
| [setFontBold(byte value)](#setFontBold-byte-) | Determines whether the font is bold. |
| [getFontItalic()](#getFontItalic--) | Determines whether the font is itallic. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Determines whether the font is itallic. |
| [getKumimoji()](#getKumimoji--) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Determines whether the height of a text should be normalized. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Determines whether the height of a text should be normalized. |
| [getProofDisabled()](#getProofDisabled--) | Determines whether the text shouldn't be proofed. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Determines whether the text shouldn't be proofed. |
| [getFontUnderline()](#getFontUnderline--) | Returns or sets the text underline type. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Returns or sets the text underline type. |
| [getTextCapType()](#getTextCapType--) | Returns or sets the type of text capitalization. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Returns or sets the type of text capitalization. |
| [getStrikethroughType()](#getStrikethroughType--) | Returns or sets the strikethrough type of a text. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Returns or sets the strikethrough type of a text. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. |
| [getFontHeight()](#getFontHeight--) | Returns or sets the font height of a portion. |
| [setFontHeight(float value)](#setFontHeight-float-) | Returns or sets the font height of a portion. |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font info. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font info. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font info. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font info. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font info. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font info. |
| [getSymbolFont()](#getSymbolFont--) | Returns or sets the symbolic font info. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Returns or sets the symbolic font info. |
| [getEscapement()](#getEscapement--) | Returns or sets the superscript or subscript text. |
| [setEscapement(float value)](#setEscapement-float-) | Returns or sets the superscript or subscript text. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Returns or sets the minimal font size, for which kerning should be switched on. |
| [getLanguageId()](#getLanguageId--) | Returns or sets the Id of a proofing language. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Returns or sets the Id of a proofing language. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Returns or sets the Id of an alternative language. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Returns or sets the Id of an alternative language. |
| [getSpacing()](#getSpacing--) | Returns or sets the intercharacter spacing increment. |
| [setSpacing(float value)](#setSpacing-float-) | Returns or sets the intercharacter spacing increment. |
| [getSpellCheck()](#getSpellCheck--) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Gets or sets a value indicating whether spell checking is enabled for the text portion. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Renvoie les propriétés LineFormat pour le contour du texte. Aucun héritage appliqué. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Renvoie les propriétés FillFormat du texte. Aucun héritage appliqué. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Renvoie les propriétés EffectFormat du texte. Aucun héritage appliqué. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Renvoie les propriétés LineFormat utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Renvoie les propriétés FillFormat de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Détermine si la police est en gras. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Détermine si la police est italique. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Détermine si le texte ne doit pas être révisé. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Détermine si le texte ne doit pas être révisé. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Renvoie :**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Renvoie ou définit le type de soulignement du texte. Aucun héritage appliqué. Lecture/écriture [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [TextCapType](../../com.aspose.slides/textcaptype).

**Renvoie :**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Renvoie ou définit le type de capitalisation du texte. Aucun héritage appliqué. Lecture/écriture [TextCapType](../../com.aspose.slides/textcaptype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Renvoie ou définit le type de texte barré. Aucun héritage appliqué. Lecture/écriture [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Renvoie :**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Renvoie ou définit le type de texte barré. Aucun héritage appliqué. Lecture/écriture [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Détermine si le style de soulignement possède ses propres propriétés LineFormat ou les hérite des propriétés LineFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Détermine si le style de soulignement possède ses propres propriétés FillFormat ou les hérite des propriétés FillFormat du texte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Renvoie ou définit la hauteur de la police d’une portion. **Float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Renvoie :**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Renvoie ou définit la hauteur de la police d’une portion. **Float.NaN** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Renvoie ou définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Renvoie ou définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Renvoie ou définit les informations de police Asie orientale. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Renvoie ou définit les informations de police Asie orientale. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Renvoie ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Renvoie ou définit les informations de police de script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Renvoie :**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Renvoie ou définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lecture/écriture [IFontData](../../com.aspose.slides/ifontdata).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Renvoie ou définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Renvoie :**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Renvoie ou définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Renvoie :**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Renvoie ou définit la taille minimale de police pour laquelle le crénage doit être activé. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Renvoie ou définit l’identifiant d’une langue de relecture. Utilisé pour la vérification orthographique et grammaticale. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Renvoie ou définit l’identifiant d’une langue de relecture. Utilisé pour la vérification orthographique et grammaticale. Lecture/écriture String.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Renvoie ou définit l’identifiant d’une langue alternative. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Renvoie ou définit l’identifiant d’une langue alternative. Lecture/écriture String.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Renvoie ou définit l’incrément d’espacement intercaractères. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Renvoie :**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Renvoie ou définit l’incrément d’espacement intercaractères. **Float.NaN** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture/écriture float.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu’elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Accéder à la première portion de texte à l'intérieur de la première forme sur la première diapositive
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
**Returns:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)


Obtient ou définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu’elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |