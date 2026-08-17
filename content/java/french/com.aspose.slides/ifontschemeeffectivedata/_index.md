---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objet immuable contenant les propriétés effectives du schéma de police.
type: docs
url: /fr/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Objet immuable contenant les propriétés effectives du schéma de police.

--------------------

Cette interface est utilisée dans le cadre de [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMinor()](#getMinor--) | Renvoie la collection de polices pour la partie « corps » de la diapositive. |
| [getMajor()](#getMajor--) | Renvoie la collection de polices pour la partie « titre » de la diapositive. |
| [getName()](#getName--) | Renvoie le nom du schéma de police. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Renvoie la collection de polices pour la partie « corps » de la diapositive. Lecture seule [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Renvoie:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Renvoie la collection de polices pour la partie « titre » de la diapositive. Lecture seule [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Renvoie:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Renvoie le nom du schéma de police. Lecture seule String.

**Renvoie:**
java.lang.String