---
title: PortionFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Cette classe contient les propriétés de mise en forme de la portion de texte.
type: docs
url: /fr/com.aspose.slides/portionformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Cette classe contient les propriétés de mise en forme de la portion de texte. Contrairement à [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instancie un objet présentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides utilise ces identifiants spéciaux (similaires à ceux utilisés dans PowerPoint) :
>      // +mn-lt - Police du corps Latin (Police Latin mineure)
>      // +mj-lt - Police de titre Latin (Police Latin majeure)
>      // +mn-ea - Police du corps asiatique de l'Est (Police asiatique de l'Est mineure)
>      // +mj-ea - Police du corps asiatique de l'Est (Police asiatique de l'Est mineure)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme de la portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris héritées, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/portionformat\#getEffective) qui renvoie une instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initialise une nouvelle instance de la classe [PortionFormat](../../com.aspose.slides/portionformat). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Renvoie ou définit l'identifiant du signet. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Renvoie ou définit l'identifiant du signet. |
| [getSmartTagClean()](#getSmartTagClean--) | Détermine si la smart tag doit être nettoyée. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Détermine si la smart tag doit être nettoyée. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Renvoie ou définit le lien hypertexte défini pour le clic de souris. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le clic de souris. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gestionnaire de liens hypertexte. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme de portion effectives avec l'héritage appliqué. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Initialise une nouvelle instance de la classe [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Renvoie ou définit l'identifiant du signet. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Renvoie ou définit l'identifiant du signet. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Gestionnaire de liens hypertexte. Lecture seule [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Renvoie :**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Obtient les données de mise en forme de portion effectives avec l'héritage appliqué.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).