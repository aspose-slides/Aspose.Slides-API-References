---
title: BrowsedByIndividual
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fenêtre parcourue par individu
type: docs
url: /fr/com.aspose.slides/browsedbyindividual/
---
**Héritage:**
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
## Constructors

| Constructor | Description |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initializes a new instance of the BrowsedByIndividual class. |
## Methods

| Method | Description |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Show Scroll Bar in Window |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Show Scroll Bar in Window |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Initializes a new instance of the BrowsedByIndividual class.

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

Show Scroll Bar in Window

**Returns:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)

Afficher la barre de défilement dans la fenêtre

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |