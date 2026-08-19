---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti schématu písem.
type: docs
url: /cs/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Neměnný objekt, který obsahuje efektivní vlastnosti schématu písem.

--------------------

Toto rozhraní se používá jako součást [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getMinor()](#getMinor--) | Vrací kolekci písem pro část "body" snímku. |
| [getMajor()](#getMajor--) | Vrací kolekci písem pro část "heading" snímku. |
| [getName()](#getName--) | Vrací název schématu písem. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Vrací kolekci písem pro část "body" snímku. Pouze pro čtení [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Vrací:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Vrací kolekci písem pro část "heading" snímku. Pouze pro čtení [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Vrací:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název schématu písem. Pouze pro čtení String.

**Vrací:**
java.lang.String