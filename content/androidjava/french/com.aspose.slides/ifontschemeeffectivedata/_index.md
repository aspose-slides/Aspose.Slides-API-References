---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Référence
description: Objet immuable qui contient les propriétés effectives du schéma de police.
type: docs
url: /fr/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Objet immuable qui contient les propriétés effectives du schéma de police.

--------------------

Cette interface est utilisée comme partie de [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Retourne la collection de polices pour la partie « body » de la diapositive. |
| [getMajor()](#getMajor--) | Retourne la collection de polices pour la partie « heading » de la diapositive. |
| [getName()](#getName--) | Retourne le nom du schéma de police. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Retourne la collection de polices pour la partie « body » de la diapositive. Lecture seule [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retour :**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Retourne la collection de polices pour la partie « heading » de la diapositive. Lecture seule [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retour :**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Retourne le nom du schéma de police. Lecture seule String.

**Retour :**
java.lang.String