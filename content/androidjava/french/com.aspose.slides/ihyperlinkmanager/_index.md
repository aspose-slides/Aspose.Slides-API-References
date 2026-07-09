---
title: IHyperlinkManager
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Fournir la gestion des hyperliens, ajout et suppression.
type: docs
url: /fr/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
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
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Définit un hyperlien externe au clic.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du hyperlien. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objet Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Définit un hyperlien interne au clic.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Supprime le hyperlien au clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Définit le hyperlien externe au survol de la souris.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du hyperlien. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objet Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Définit un hyperlien interne au survol de la souris.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

**Retour :**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objet Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Supprime le hyperlien au survol de la souris.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Définit un hyperlien Macro au clic.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objet Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)