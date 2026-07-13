---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /nl/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Onveranderlijk object dat effectieve lettertype-schema-eigenschappen bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMinor()](#getMinor--) | Retourneert de collectie lettertypen voor het "body"-gedeelte van de dia. |
| [getMajor()](#getMajor--) | Retourneert de collectie lettertypen voor het "heading"-gedeelte van de dia. |
| [getName()](#getName--) | Retourneert de naam van het lettertype-schema. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Retourneert de collectie lettertypen voor het "body"-gedeelte van de dia. Alleen-lezen [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retour:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Retourneert de collectie lettertypen voor het "heading"-gedeelte van de dia. Alleen-lezen [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retour:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Retourneert de naam van het lettertype-schema. Alleen-lezen String.

**Retour:**
java.lang.String