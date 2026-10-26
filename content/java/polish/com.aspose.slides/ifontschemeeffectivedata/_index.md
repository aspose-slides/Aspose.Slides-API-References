---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Niezmienny obiekt zawierający efektywne właściwości schematu czcionek.
type: docs
url: /pl/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Niezmienny obiekt zawierający efektywne właściwości schematu czcionek.

--------------------

Ten interfejs jest używany jako część [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metody

| Metoda | Opis |
| --- | --- |
| [getMinor()](#getMinor--) | Zwraca kolekcję czcionek dla części "body" slajdu. |
| [getMajor()](#getMajor--) | Zwraca kolekcję czcionek dla części "heading" slajdu. |
| [getName()](#getName--) | Zwraca nazwę schematu czcionek. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Zwraca kolekcję czcionek dla części "body" slajdu. Tylko do odczytu [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Zwraca:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Zwraca kolekcję czcionek dla części "heading" slajdu. Tylko do odczytu [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Zwraca:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Zwraca nazwę schematu czcionek. Tylko do odczytu String.

**Zwraca:**
java.lang.String