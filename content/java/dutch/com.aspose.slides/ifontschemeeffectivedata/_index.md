---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /nl/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Onveranderlijk object dat de effectieve lettertype-schemagegevens bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMinor()](#getMinor--) | Retourneert de lettertypecollectie voor een "body"-gedeelte van de dia. |
| [getMajor()](#getMajor--) | Retourneert de lettertypecollectie voor een "heading"-gedeelte van de dia. |
| [getName()](#getName--) | Retourneert de naam van het lettertype-schema. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Retourneert de lettertypecollectie voor een "body"-gedeelte van de dia. Alleen-lezen [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retourneert:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Retourneert de lettertypecollectie voor een "heading"-gedeelte van de dia. Alleen-lezen [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Retourneert:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Retourneert de naam van het lettertype-schema. Alleen-lezen String.

**Retourneert:**
java.lang.String