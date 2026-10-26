---
title: IPptxOptions
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje opcje zapisywania prezentacji OpenXml w formatach PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /pl/com.aspose.slides/ipptxoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Reprezentuje opcje zapisywania prezentacji OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Metody

| Metoda | Opis |
| --- | --- |
| [getConformance()](#getConformance--) | Określa klasę zgodności, do której dokument Presentation jest zgodny. |
| [setConformance(int value)](#setConformance-int-) | Określa klasę zgodności, do której dokument Presentation jest zgodny. |
| [getZip64Mode()](#getZip64Mode--) | Określa, czy format ZIP64 jest używany dla dokumentu Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Określa, czy format ZIP64 jest używany dla dokumentu Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Określa, czy miniatura prezentacji zostanie odświeżona. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Określa, czy miniatura prezentacji zostanie odświeżona. |
| [getCompressionLevel()](#getCompressionLevel--) | Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Określa klasę zgodności, do której dokument Presentation jest zgodny. Domyślna wartość to [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Zwraca:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Określa klasę zgodności, do której dokument Presentation jest zgodny. Domyślna wartość to [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
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
public abstract void setZip64Mode(int value)
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
public abstract boolean getRefreshThumbnail()
```

Określa, czy miniatura prezentacji zostanie odświeżona. Boolean odczyt/zapis. Domyślna wartość to **true**.

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

Gdy wartość opcji jest **true**, nowa miniatura zostanie wygenerowana.

Gdy wartość opcji jest **false**, bieżąca miniatura zostanie zapisana bez zmian.

**Zwraca:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Określa, czy miniatura prezentacji zostanie odświeżona. Boolean odczyt/zapis. Domyślna wartość to **true**.

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

Gdy wartość opcji jest **true**, nowa miniatura zostanie wygenerowana.

Gdy wartość opcji jest **false**, bieżąca miniatura zostanie zapisana bez zmian.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Wyższe poziomy kompresji powodują mniejsze pliki, ale wymagają więcej czasu przetwarzania. Rzeczywisty współczynnik kompresji zależy od zawartości prezentacji.

**Zwraca:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Określa poziom kompresji używany podczas zapisywania dokumentu prezentacji. Domyślna wartość to [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Wyższe poziomy kompresji powodują mniejsze pliki, ale wymagają więcej czasu przetwarzania. Rzeczywisty współczynnik kompresji zależy od zawartości prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |