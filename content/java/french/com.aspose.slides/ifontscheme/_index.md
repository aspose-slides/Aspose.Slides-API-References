---
title: IFontScheme
second_title: Référence de l'API Java d'Aspose.Slides
description: Stocke les polices définies par le thème.
type: docs
url: /fr/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Stocke les polices définies par le thème.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Renvoie la collection de polices pour la partie "corps" de la diapositive. |
| [getMajor()](#getMajor--) | Renvoie la collection de polices pour la partie "en-tête" de la diapositive. |
| [getName()](#getName--) | Renvoie le nom du jeu de polices. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie le nom du jeu de polices. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


Renvoie la collection de polices pour la partie "corps" de la diapositive. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Retour :**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


Renvoie la collection de polices pour la partie "en-tête" de la diapositive. Read-only [IFonts](../../com.aspose.slides/ifonts).

**Retour :**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


Renvoie le nom du jeu de polices. Read/write String.

**Retour :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Renvoie le nom du jeu de polices. Read/write String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |