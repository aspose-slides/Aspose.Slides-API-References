---
title: PptxOptions
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje možnosti pro ukládání OpenXml prezentací PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /cs/com.aspose.slides/pptxoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Představuje možnosti pro ukládání OpenXml prezentací (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Vytvoří novou instanci PptxOptions |
## Metody

| Metoda | Popis |
| --- | --- |
| [getConformance()](#getConformance--) | Určuje třídu souladu, ke které dokument Presentation odpovídá. |
| [setConformance(int value)](#setConformance-int-) | Určuje třídu souladu, ke které dokument Presentation odpovídá. |
| [getZip64Mode()](#getZip64Mode--) | Určuje, zda je pro dokument Presentation používán formát ZIP64. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Určuje, zda je pro dokument Presentation používán formát ZIP64. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Určuje, zda bude miniatura prezentace obnovena. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Určuje, zda bude miniatura prezentace obnovena. |
| [getCompressionLevel()](#getCompressionLevel--) | Určuje úroveň komprese používanou při ukládání dokumentu prezentace. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Určuje úroveň komprese používanou při ukládání dokumentu prezentace. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Vytvoří novou instanci PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Určuje třídu souladu, ke které dokument Presentation odpovídá. Výchozí hodnota je [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Vrací:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Určuje třídu souladu, ke které dokument Presentation odpovídá. Výchozí hodnota je [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Určuje, zda je pro dokument Presentation používán formát ZIP64. Výchozí hodnota je [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Určuje, zda je pro dokument Presentation používán formát ZIP64. Výchozí hodnota je [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Určuje, zda bude miniatura prezentace obnovena. Čtení/zápis boolean. Výchozí hodnota je **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Když je hodnota volby **true**, bude vygenerována nová miniatura.

Když je hodnota volby **false**, aktuální miniatura bude uložena tak, jak je.

**Vrací:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Určuje, zda bude miniatura prezentace obnovena. Čtení/zápis boolean. Výchozí hodnota je **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Když je hodnota volby **true**, bude vygenerována nová miniatura.

Když je hodnota volby **false**, aktuální miniatura bude uložena tak, jak je.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Určuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Vyšší úrovně komprese produkují menší soubory, ale vyžadují více času na zpracování. Skutečný kompresní poměr závisí na obsahu prezentace.

**Vrací:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Určuje úroveň komprese používanou při ukládání dokumentu prezentace. Výchozí hodnota je [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Vyšší úrovně komprese produkují menší soubory, ale vyžadují více času na zpracování. Skutečný kompresní poměr závisí na obsahu prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |