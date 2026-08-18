---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /hu/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Változtathatatlan objektum, amely a tényleges betűkészlet tulajdonságait tartalmaz.

--------------------

Ez a felület a [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) részeként használatos.
## Methods

| Metódus | Leírás |
| --- | --- |
| [getMinor()](#getMinor--) | Visszaadja a betűk gyűjteményét a dia "body" részéhez. |
| [getMajor()](#getMajor--) | Visszaadja a betűk gyűjteményét a dia "heading" részéhez. |
| [getName()](#getName--) | Visszaadja a betűkészlet nevét. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Visszaadja a betűk gyűjteményét a dia "body" részéhez. Csak olvasható [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Visszatér:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Visszaadja a betűk gyűjteményét a dia "heading" részéhez. Csak olvasható [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Visszatér:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja a betűkészlet nevét. Csak olvasható String.

**Visszatér:**
java.lang.String