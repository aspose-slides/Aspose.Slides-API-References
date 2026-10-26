---
title: Theme
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un tema.
type: docs
url: /it/com.aspose.slides/theme/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme), com.aspose.slides.IStyleColorOwner, com.aspose.slides.IPVIObject
```
public abstract class Theme implements ITheme, IStyleColorOwner, IPVIObject
```

Rappresenta un tema.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Restituisce lo schema dei colori. |
| [getFontScheme()](#getFontScheme--) | Restituisce lo schema dei caratteri. |
| [getFormatScheme()](#getFormatScheme--) | Restituisce lo schema del formato forma. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre. |
| [getEffective()](#getEffective--) | Ottiene i dati del tema effettivi con l'ereditarietà applicata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Restituisce lo schema dei colori. Solo lettura [IColorScheme](../../com.aspose.slides/icolorscheme).

**Restituisce:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Restituisce lo schema dei caratteri. Solo lettura [IFontScheme](../../com.aspose.slides/ifontscheme).

**Restituisce:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Restituisce lo schema del formato forma. Solo lettura [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Restituisce:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getEffective() {#getEffective--}
```
public final IThemeEffectiveData getEffective()
```

Ottiene i dati del tema effettivi con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting effective theme properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IThemeEffectiveData effectiveTheme  = pres.getSlides().get_Item(0).getThemeManager().getOverrideTheme().getEffective();
>  	System.out.println("Font scheme name: " + effectiveTheme.getFontScheme().getName());
>  	System.out.println("Major latin font: " + effectiveTheme.getFontScheme().getMajor().getLatinFont().getFontName());
>  	System.out.println("Minor latin font: " + effectiveTheme.getFontScheme().getMinor().getLatinFont().getFontName());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Un [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Restituisce il genitore IPresentationComponent. Solo lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getVersion() {#getVersion--}
```
public abstract long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long