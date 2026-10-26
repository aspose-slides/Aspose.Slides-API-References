---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Oggetto immutabile che contiene le proprietà effettive dello schema di caratteri.
type: docs
url: /it/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Oggetto immutabile che contiene le proprietà effettive dello schema di caratteri.

--------------------

Questa interfaccia è usata come parte di [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMinor()](#getMinor--) | Restituisce la raccolta di font per la parte "body" della diapositiva. |
| [getMajor()](#getMajor--) | Restituisce la raccolta di font per la parte "heading" della diapositiva. |
| [getName()](#getName--) | Restituisce il nome dello schema di font. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Restituisce la raccolta di font per la parte "body" della diapositiva. Solo lettura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Restituisce:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Restituisce la raccolta di font per la parte "heading" della diapositiva. Solo lettura [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Restituisce:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Restituisce il nome dello schema di font. Solo lettura String.

**Restituisce:**
java.lang.String