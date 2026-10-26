---
title: ParagraphFormat
second_title: "Référence de l'API Aspose.Slides pour Java"
description: "Cette classe contient les propriétés de formatage du paragraphe."
type: docs
url: /fr/com.aspose.slides/paragraphformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Cette classe contient les propriétés de formatage du paragraphe. Contrairement à [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage du paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, si bien que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris celles héritées, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) qui renvoie une instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialise une nouvelle instance de la classe [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie le format de la puce du paragraphe. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur du paragraphe. |
| [setDepth(short value)](#setDepth-short-) | Renvoie ou définit la profondeur du paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. |
| [setAlignment(int value)](#setAlignment-int-) | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie ou définit la quantité d'espace entre les lignes de base d'un paragraphe. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Renvoie ou définit la quantité d'espace entre les lignes de base d'un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [setMarginRight(float value)](#setMarginRight-float-) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [getIndent()](#getIndent--) | Renvoie ou définit l'indentation de première ligne/indentation suspendue du paragraphe sans héritage. |
| [setIndent(float value)](#setIndent-float-) | Renvoie ou définit l'indentation de première ligne/indentation suspendue du paragraphe sans héritage. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie ou définit la taille de tabulation par défaut sans héritage. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Renvoie ou définit la taille de tabulation par défaut sans héritage. |
| [getTabs()](#getTabs--) | Renvoie les tabulations d'un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d'un paragraphe. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de paragraphe effectives avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initialise une nouvelle instance de la classe [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Renvoie le format de la puce du paragraphe. Lecture seule [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Renvoie :**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie une valeur indéfinie. Lecture/écriture  short .

**Renvoie :**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie une valeur indéfinie. Lecture/écriture  short .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> Le code d'exemple suivant montre comment aligner les paragraphes de texte dans une présentation PowerPoint.
>  
>  // Instancie un objet Presentation qui représente un fichier PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accès à la première diapositive
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accès aux premier et deuxième espaces réservés de la diapositive et conversion type en AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifie le texte des deux espaces réservés
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Récupère le premier paragraphe des espaces réservés
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligne le paragraphe de texte au centre
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Enregistre la présentation au format PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> Le code d'exemple suivant montre comment aligner les paragraphes de texte dans une présentation PowerPoint.
>  
>  // Instancie un objet Presentation qui représente un fichier PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accès à la première diapositive
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accès aux premier et deuxième espaces réservés de la diapositive et conversion type en AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifie le texte des deux espaces réservés
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Récupère le premier paragraphe des espaces réservés
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Aligne le paragraphe de texte au centre
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Enregistre la présentation au format PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Renvoie ou définit la quantité d'espace entre les lignes de base d'un paragraphe. Une valeur positive indique un pourcentage, une valeur négative la taille en points. Aucun héritage appliqué. Lecture/écriture  float .

**Renvoie :**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Renvoie ou définit la quantité d'espace entre les lignes de base d'un paragraphe. Une valeur positive indique un pourcentage, une valeur négative la taille en points. Aucun héritage appliqué. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture  float .

**Renvoie :**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture  float .

**Renvoie :**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative spécifie la taille de l'espace blanc en points. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture  float .

**Renvoie :**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture  float .

**Renvoie :**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

Renvoie ou définit l'indentation de première ligne/indentation suspendue du paragraphe sans héritage. L'indentation suspendue peut être définie avec des valeurs négatives. Lecture/écriture  float .

**Renvoie :**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Renvoie ou définit l'indentation de première ligne/indentation suspendue du paragraphe sans héritage. L'indentation suspendue peut être définie avec des valeurs négatives. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture  float .

**Renvoie :**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule [ITabCollection](../../com.aspose.slides/itabcollection).

**Renvoie :**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Renvoie :**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Renvoie le format de portion par défaut d'un paragraphe. Aucun héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Obtient les données de formatage de paragraphe effectives avec l'héritage appliqué.

--------------------

> ```
> Cet exemple montre la récupération de certaines propriétés de format de paragraphe effectives.
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


**Renvoie :**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long