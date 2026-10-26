---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti schématu písma.
type: docs
url: /cs/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti schématu písma.

--------------------

Toto rozhraní se používá jako součást [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getMinor()](#getMinor--) | Vrací kolekci fontů pro část „body“ snímku. |
| [getMajor()](#getMajor--) | Vrací kolekci fontů pro část „heading“ snímku. |
| [getName()](#getName--) | Vrací název schématu písma. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Vrací kolekci fontů pro část „body“ snímku. Pouze pro čtení [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Vrací:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Vrací kolekci fontů pro část „heading“ snímku. Pouze pro čtení [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Vrací:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Vrací název schématu písma. Pouze pro čtení String.

**Vrací:**
java.lang.String