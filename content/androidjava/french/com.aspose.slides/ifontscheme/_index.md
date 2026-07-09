---
title: IFontScheme
second_title: Aspose.Slides pour Android via Référence API Java
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
| [getMinor()](#getMinor--) | Renvoie la collection de polices pour la partie "body" de la diapositive. |
| [getMajor()](#getMajor--) | Renvoie la collection de polices pour la partie "heading" de la diapositive. |
| [getName()](#getName--) | Renvoie le nom du jeu de polices. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie le nom du jeu de polices. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

Renvoie la collection de polices pour la partie "body" de la diapositive. Lecture seule [IFonts](../../com.aspose.slides/ifonts).

**Retourne :**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

Renvoie la collection de polices pour la partie "heading" de la diapositive. Lecture seule [IFonts](../../com.aspose.slides/ifonts).

**Retourne :**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

Renvoie le nom du jeu de polices. Lecture/écriture String.

**Retourne :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Renvoie le nom du jeu de polices. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |