---
title: BrowsedByIndividual
second_title: Référence API Aspose.Slides pour Java
description: Fenêtre parcourue par individu
type: docs
url: /fr/com.aspose.slides/browsedbyindividual/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Parcouru par individu (fenêtre)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initialise une nouvelle instance de la classe BrowsedByIndividual. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Afficher la barre de défilement dans la fenêtre |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Afficher la barre de défilement dans la fenêtre |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Initialise une nouvelle instance de la classe BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Afficher la barre de défilement dans la fenêtre

**Retourne :**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Afficher la barre de défilement dans la fenêtre

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |