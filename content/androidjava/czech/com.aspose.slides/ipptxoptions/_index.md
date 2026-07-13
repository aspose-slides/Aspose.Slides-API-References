---
title: IPptxOptions
second_title: Aspose.Slides pro Android přes referenční dokumentaci Java API
description: Reprezentuje možnosti pro ukládání OpenXml prezentací PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /cs/com.aspose.slides/ipptxoptions/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Představuje možnosti pro ukládání OpenXml prezentací (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Metody

| Metoda | Popis |
| --- | --- |
| [getConformance()](#getConformance--) | Určuje třídu souladu, ke které dokument Presentation odpovídá. |
| [setConformance(int value)](#setConformance-int-) | Určuje třídu souladu, ke které dokument Presentation odpovídá. |
| [getZip64Mode()](#getZip64Mode--) | Určuje, zda je pro dokument Presentation použit formát ZIP64. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Určuje, zda je pro dokument Presentation použit formát ZIP64. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Určuje, zda bude miniaturka prezentace obnovena. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Určuje, zda bude miniaturka prezentace obnovena. |
| [getCompressionLevel()](#getCompressionLevel--) | Určuje úroveň komprese používanou při ukládání dokumentu prezentace. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Určuje úroveň komprese používanou při ukládání dokumentu prezentace. |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Určuje třídu souladu, ke které dokument Presentation odpovídá. Výchozí hodnota je [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Vrací:**
int

### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Určuje třídu souladu, ke které dokument Presentation odpovídá. Výchozí hodnota je [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Určuje, zda je pro dokument Presentation použit formát ZIP64. Výchozí hodnota je [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

Určuje, zda je pro dokument Presentation použit formát ZIP64. Výchozí hodnota je [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```

Určuje, zda bude miniaturka prezentace obnovena. Čtení/zápis boolean. Výchozí hodnota je **true**.

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

Když je hodnota možnosti **true**, nová miniaturka bude vygenerována.

Když je hodnota možnosti **false**, aktuální miniaturka bude uložena tak, jak je.

**Vrací:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Určuje, zda bude miniaturka prezentace obnovena. Čtení/zápis boolean. Výchozí hodnota je **true**.

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

Když je hodnota možnosti **true**, nová miniaturka bude vygenerována.

Když je hodnota možnosti **false**, aktuální miniaturka bude uložena tak, jak je.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
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
public abstract void setCompressionLevel(int value)
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