---
title: PptxOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje opcje zapisywania prezentacji OpenXml w formatach PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /pl/com.aspose.slides/pptxoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Reprezentuje opcje zapisywania prezentacji OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Tworzy nową instancję PptxOptions |

## Metody

| Metoda | Opis |
| --- | --- |
| [getConformance()](#getConformance--) | Określa klasę zgodności, do której dokument Presentation jest zgodny. |
| [setConformance(int value)](#setConformance-int-) | Określa klasę zgodności, do której dokument Presentation jest zgodny. |
| [getZip64Mode()](#getZip64Mode--) | Określa, czy format ZIP64 jest używany dla dokumentu Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Określa, czy format ZIP64 jest używany dla dokumentu Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Określa, czy miniatura prezentacji zostanie odświeżona. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Określa, czy miniatura prezentacji zostanie odświeżona. |
| [getCompressionLevel()](#getCompressionLevel--) | Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Tworzy nową instancję PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Określa klasę zgodności, do której dokument Presentation jest zgodny. Domyślna wartość to [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Zwraca:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Określa klasę zgodności, do której dokument Presentation jest zgodny. Domyślna wartość to [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Określa, czy format ZIP64 jest używany dla dokumentu Presentation. Domyślna wartość to [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Zwraca:**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Określa, czy format ZIP64 jest używany dla dokumentu Presentation. Domyślna wartość to [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Określa, czy miniatura prezentacji zostanie odświeżona. Zmienna boolean do odczytu i zapisu. Domyślna wartość to **true**.

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

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Zwraca:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Określa, czy miniatura prezentacji zostanie odświeżona. Zmienna boolean do odczytu i zapisu. Domyślna wartość to **true**.

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

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation.

**Zwraca:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |