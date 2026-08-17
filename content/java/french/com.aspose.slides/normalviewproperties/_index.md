---
title: NormalViewProperties
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés de la vue normale.
type: docs
url: /fr/com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Représente les propriétés de la vue normale. La vue normale comprend trois régions de contenu : la diapositive elle-même, une région de contenu latérale et une région de contenu inférieure.

--------------------

> ```
> L'exemple suivant montre comment configurer les propriétés ViewProperties.NormalViewProperties d'une présentation PowerPoint.
>  
>  //Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Spécifie si l'application doit afficher des icônes lors de l'affichage du contenu du plan dans l'une des régions de contenu du mode de vue normale. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Spécifie si l'application doit afficher des icônes lors de l'affichage du contenu du plan dans l'une des régions de contenu du mode de vue normale. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Spécifie si le séparateur vertical doit s'enclencher à l'état réduit lorsque la région latérale est suffisamment petite. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Spécifie si le séparateur vertical doit s'enclencher à l'état réduit lorsque la région latérale est suffisamment petite. |
| [getVerticalBarState()](#getVerticalBarState--) | Spécifie l'état dans lequel la barre du séparateur vertical doit être affichée. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Spécifie l'état dans lequel la barre du séparateur vertical doit être affichée. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Spécifie l'état dans lequel la barre du séparateur horizontal doit être affichée. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Spécifie l'état dans lequel la barre du séparateur horizontal doit être affichée. |
| [getPreferSingleView()](#getPreferSingleView--) | Spécifie si l'utilisateur préfère voir une région à contenu unique plein écran plutôt que la vue normale standard avec trois régions de contenu. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Spécifie si l'utilisateur préfère voir une région à contenu unique plein écran plutôt que la vue normale standard avec trois régions de contenu. |
| [getRestoredLeft()](#getRestoredLeft--) | Cet élément spécifie la taille de la région de contenu latérale de la vue normale, lorsque la région a une taille restaurée variable (ni réduite ni agrandie). |
| [getRestoredTop()](#getRestoredTop--) | Cet élément spécifie la taille de la région supérieure de la diapositive de la vue normale, lorsque la région a une taille restaurée variable (ni réduite ni agrandie). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Spécifie si l'application doit afficher des icônes lors de l'affichage du contenu du plan dans l'une des régions de contenu du mode de vue normale. Lecture/écriture booléen.

**Renvoie :**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Spécifie si l'application doit afficher des icônes lors de l'affichage du contenu du plan dans l'une des régions de contenu du mode de vue normale. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Spécifie si le séparateur vertical doit s'enclencher à l'état réduit lorsque la région latérale est suffisamment petite. Lecture/écriture booléen.

**Renvoie :**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Spécifie si le séparateur vertical doit s'enclencher à l'état réduit lorsque la région latérale est suffisamment petite. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Spécifie l'état dans lequel la barre du séparateur vertical doit être affichée. Un séparateur vertical sépare la diapositive de la région de contenu latérale.

**Renvoie :**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Spécifie l'état dans lequel la barre du séparateur vertical doit être affichée. Un séparateur vertical sépare la diapositive de la région de contenu latérale.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Spécifie l'état dans lequel la barre du séparateur horizontal doit être affichée. Un séparateur horizontal sépare la diapositive de la région de contenu située sous la diapositive.

**Renvoie :**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Spécifie l'état dans lequel la barre du séparateur horizontal doit être affichée. Un séparateur horizontal sépare la diapositive de la région de contenu située sous la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Spécifie si l'utilisateur préfère voir une région à contenu unique plein écran plutôt que la vue normale standard avec trois régions de contenu. Si activé, l'application peut choisir d'afficher l'une des régions de contenu sur toute la fenêtre. Lecture/écriture booléen.

**Renvoie :**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Spécifie si l'utilisateur préfère voir une région à contenu unique plein écran plutôt que la vue normale standard avec trois régions de contenu. Si activé, l'application peut choisir d'afficher l'une des régions de contenu sur toute la fenêtre. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Cet élément spécifie la taille de la région de contenu latérale de la vue normale, lorsque la région a une taille restaurée variable (ni réduite ni agrandie). Lecture seule [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Renvoie :**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Cet élément spécifie la taille de la région supérieure de la diapositive de la vue normale, lorsque la région a une taille restaurée variable (ni réduite ni agrandie). Lecture seule [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Renvoie :**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)