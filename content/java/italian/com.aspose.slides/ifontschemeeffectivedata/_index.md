---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides per Java API Reference
description: Oggetto immutabile che contiene le proprietà effettive dello schema dei font.
type: docs
url: /it/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive dello schema dei font.

--------------------

Questa interfaccia è utilizzata come parte di [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Methods

| Metodo | Descrizione |
| --- | --- |
| [getMinor()](#getMinor--) | Restituisce la collezione di font per la parte "body" della diapositiva. |
| [getMajor()](#getMajor--) | Restituisce la collezione di font per la parte "heading" della diapositiva. |
| [getName()](#getName--) | Restituisce il nome dello schema dei font. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Restituisce la collezione di font per la parte "body" della diapositiva. Solo lettura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Restituisce:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Restituisce la collezione di font per la parte "heading" della diapositiva. Solo lettura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Restituisce:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce il nome dello schema dei font. Solo lettura String.

**Restituisce:**
java.lang.String