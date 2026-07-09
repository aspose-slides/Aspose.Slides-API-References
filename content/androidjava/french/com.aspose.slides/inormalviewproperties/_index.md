---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les propriétés de la vue normale.
type: docs
url: /fr/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Représente les propriétés de la vue normale. La vue normale se compose de trois zones de contenu : la diapositive elle-même, une zone de contenu latérale et une zone de contenu inférieure.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Indique si l'application doit afficher des icônes lors de l'affichage du contenu du contour dans l'une des zones de contenu du mode vue normale. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Indique si l'application doit afficher des icônes lors de l'affichage du contenu du contour dans l'une des zones de contenu du mode vue normale. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Indique si le séparateur vertical doit se placer en position réduite lorsque la zone latérale est suffisamment petite. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Indique si le séparateur vertical doit se placer en position réduite lorsque la zone latérale est suffisamment petite. |
| [getVerticalBarState()](#getVerticalBarState--) | Indique l'état dans lequel la barre du séparateur vertical doit être affichée. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Indique l'état dans lequel la barre du séparateur vertical doit être affichée. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Indique l'état dans lequel la barre du séparateur horizontal doit être affichée. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Indique l'état dans lequel la barre du séparateur horizontal doit être affichée. |
| [getPreferSingleView()](#getPreferSingleView--) | Indique si l'utilisateur préfère voir une zone de contenu unique en plein écran plutôt que la vue normale standard avec trois zones de contenu. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Indique si l'utilisateur préfère voir une zone de contenu unique en plein écran plutôt que la vue normale standard avec trois zones de contenu. |
| [getRestoredLeft()](#getRestoredLeft--) | Cet élément spécifie la taille de la zone de contenu latérale de la vue normale, lorsque la zone a une taille restaurée variable (ni réduite ni maximisée). |
| [getRestoredTop()](#getRestoredTop--) | Cet élément spécifie la taille de la zone supérieure de la diapositive de la vue normale, lorsque la zone a une taille restaurée variable (ni réduite ni maximisée). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Indique si l'application doit afficher des icônes lors de l'affichage du contenu du contour dans l'une des zones de contenu du mode vue normale. Lecture/écriture booléen.

**Renvoie :**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Indique si l'application doit afficher des icônes lors de l'affichage du contenu du contour dans l'une des zones de contenu du mode vue normale. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Indique si le séparateur vertical doit se placer en position réduite lorsque la zone latérale est suffisamment petite. Lecture/écriture booléen.

**Renvoie :**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Indique si le séparateur vertical doit se placer en position réduite lorsque la zone latérale est suffisamment petite. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Indique l'état dans lequel la barre du séparateur vertical doit être affichée. Une barre du séparateur vertical sépare la diapositive de la zone de contenu latérale.

**Renvoie :**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Indique l'état dans lequel la barre du séparateur vertical doit être affichée. Une barre du séparateur vertical sépare la diapositive de la zone de contenu latérale.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Indique l'état dans lequel la barre du séparateur horizontal doit être affichée. Une barre du séparateur horizontal sépare la diapositive de la zone de contenu située sous la diapositive.

**Renvoie :**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Indique l'état dans lequel la barre du séparateur horizontal doit être affichée. Une barre du séparateur horizontal sépare la diapositive de la zone de contenu située sous la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Indique si l'utilisateur préfère voir une zone de contenu unique en plein écran plutôt que la vue normale standard avec trois zones de contenu. Si activé, l'application peut choisir d'afficher l'une des zones de contenu dans toute la fenêtre. Lecture/écriture booléen.

**Renvoie :**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Indique si l'utilisateur préfère voir une zone de contenu unique en plein écran plutôt que la vue normale standard avec trois zones de contenu. Si activé, l'application peut choisir d'afficher l'une des zones de contenu dans toute la fenêtre. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Cet élément spécifie la taille de la zone de contenu latérale de la vue normale, lorsque la zone a une taille restaurée variable (ni réduite ni maximisée). Lecture seule [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Renvoie :**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Cet élément spécifie la taille de la zone supérieure de la diapositive de la vue normale, lorsque la zone a une taille restaurée variable (ni réduite ni maximisée). Lecture seule [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Renvoie :**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)