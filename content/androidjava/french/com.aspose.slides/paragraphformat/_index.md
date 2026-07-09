---
title: ParagraphFormat
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Cette classe contient les propriétés de mise en forme du paragraphe.
type: docs
url: /fr/com.aspose.slides/paragraphformat/
---
**Héritage:** 
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:** 
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Cette classe contient les propriétés de mise en forme du paragraphe. Contrairement à [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour retourner et manipuler les propriétés de mise en forme du paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucune héritage n’est appliquée lors de l’obtention des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d’obtenir les valeurs des paramètres de mise en forme effectifs, y compris ceux hérités, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) qui renvoie une instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialise une nouvelle instance de la classe [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie le format de puce du paragraphe. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur du paragraphe. |
| [setDepth(short value)](#setDepth-short-) | Renvoie ou définit la profondeur du paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. |
| [setAlignment(int value)](#setAlignment-int-) | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si la rupture de ligne asiatique de l’Est est utilisée dans un paragraphe. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Détermine si la rupture de ligne asiatique de l’Est est utilisée dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si la rupture de ligne latine est utilisée dans un paragraphe. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Détermine si la rupture de ligne latine est utilisée dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [setMarginRight(float value)](#setMarginRight-float-) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [getIndent()](#getIndent--) | Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. |
| [setIndent(float value)](#setIndent-float-) | Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie ou définit la taille d’onglet par défaut sans héritage. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Renvoie ou définit la taille d’onglet par défaut sans héritage. |
| [getTabs()](#getTabs--) | Renvoie les onglets d’un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d’un paragraphe. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme de paragraphe effectives avec l’héritage appliqué. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initialise une nouvelle instance de [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Renvoie le format de puce du paragraphe. Lecture seule [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Renvoie :**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Renvoie ou définit la profondeur du paragraphe. Valeur 0 signifie valeur indéfinie. Lecture/écriture  short .

**Renvoie :**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Renvoie ou définit la profondeur du paragraphe. Valeur 0 signifie valeur indéfinie. Lecture/écriture  short .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instancier un objet Presentation qui représente un fichier PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accéder à la première diapositive
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accéder au premier et au deuxième espace réservé dans la diapositive et le convertir en AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifier le texte dans les deux espaces réservés
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtenir le premier paragraphe des espaces réservés
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligner le paragraphe de texte au centre
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Enregistrer la présentation en tant que fichier PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Returns or sets the text alignment in a paragraph with no inheritance. Read/write [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instancier un objet Presentation qui représente un fichier PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accéder à la première diapositive
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accéder au premier et au deuxième espace réservé dans la diapositive et le convertir en AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifier le texte dans les deux espaces réservés
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtenir le premier paragraphe des espaces réservés
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligner le paragraphe de texte au centre
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Enregistrer la présentation en tant que fichier PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write  float .

**Returns:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Returns:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Returns:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Returns or sets the left margin in a paragraph with no inheritance. Read/write  float .

**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Returns or sets the left margin in a paragraph with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Returns or sets the right margin in a paragraph with no inheritance. Read/write  float .

**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Returns or sets the right margin in a paragraph with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write  float .

**Returns:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Returns or sets default tabulation size with no inheritance. Read/write  float .

**Returns:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Returns or sets default tabulation size with no inheritance. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```
Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule [ITabCollection](../../com.aspose.slides/itabcollection).

**Renvoie:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


Returns or sets a font alignment in a paragraph with no inheritance. Read/write [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Returns default portion format of a paragraph. No inheritance applied. Read-only [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```
Gets effective paragraph formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
Version. Read-only long.

**Returns:**
long