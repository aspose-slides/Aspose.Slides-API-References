---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /de/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Unveränderliches Objekt, das effektive Font-Schema-Eigenschaften enthält.

--------------------

Dieses Interface wird als Teil von [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) verwendet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMinor()](#getMinor--) | Gibt die Font-Sammlung für einen "body"-Teil der Folie zurück. |
| [getMajor()](#getMajor--) | Gibt die Font-Sammlung für einen "heading"-Teil der Folie zurück. |
| [getName()](#getName--) | Gibt den Namen des Font-Schemas zurück. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Gibt die Font-Sammlung für einen "body"-Teil der Folie zurück. Nur-Lese [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Rückgabe:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Gibt die Font-Sammlung für einen "heading"-Teil der Folie zurück. Nur-Lese [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Rückgabe:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen des Font-Schemas zurück. Nur-Lese String.

**Rückgabe:**
java.lang.String