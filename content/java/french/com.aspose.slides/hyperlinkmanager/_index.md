---
title: HyperlinkManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit la gestion des hyperliens (ajout, suppression).
type: docs
url: /fr/com.aspose.slides/hyperlinkmanager/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject  
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Fournir la gestion des hyperliens (ajout, suppression).

## Méthodes

| Méthode | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Définit un hyperlien externe lors du clic.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Instancie une classe Presentation qui représente un PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Récupère la première diapositive de la présentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Ajoute un objet AutoShape avec le type Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Convertit la forme en AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accède à la propriété ITextFrame associée à l'AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Ajoute du texte au cadre
>      portion.setText("Aspose.Slides");
>      // Définit l'hyperlien pour le texte de la portion
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Enregistre la présentation PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL de l'hyperlien. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Définit un hyperlien interne lors du clic.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlien.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Supprime l'hyperlien lors du clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Définit un hyperlien externe au survol de la souris.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL de l'hyperlien. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlien.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Définit un hyperlien interne au survol de la souris.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlien.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Supprime l'hyperlien au survol de la souris.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Définit un hyperlien macro lors d'un clic.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Nom de la macro |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objet Hyperlien [IHyperlink](../../com.aspose.slides/ihyperlink)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retour :**
com.aspose.slides.IDOMObject