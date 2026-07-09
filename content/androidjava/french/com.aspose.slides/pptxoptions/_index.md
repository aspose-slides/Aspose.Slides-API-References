---
title: PptxOptions
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente les options d'enregistrement des présentations OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /fr/com.aspose.slides/pptxoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Représente les options pour enregistrer des présentations OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Crée une nouvelle instance de PptxOptions |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Spécifie la classe de conformité à laquelle le document Presentation se conforme. |
| [setConformance(int value)](#setConformance-int-) | Spécifie la classe de conformité à laquelle le document Presentation se conforme. |
| [getZip64Mode()](#getZip64Mode--) | Indique si le format ZIP64 est utilisé pour le document Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Indique si le format ZIP64 est utilisé pour le document Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Indique si la vignette de la présentation sera actualisée. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Indique si la vignette de la présentation sera actualisée. |
| [getCompressionLevel()](#getCompressionLevel--) | Spécifie le niveau de compression utilisé lors de l’enregistrement du document de présentation. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Spécifie le niveau de compression utilisé lors de l’enregistrement du document de présentation. |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Crée une nouvelle instance de PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Spécifie la classe de conformité à laquelle le document Presentation se conforme. La valeur par défaut est [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retour :**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Spécifie la classe de conformité à laquelle le document Presentation se conforme. La valeur par défaut est [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Indique si le format ZIP64 est utilisé pour le document Presentation. La valeur par défaut est [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Returns:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

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

**Returns:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)


Spécifie le niveau de compression utilisé lors de l’enregistrement du document de présentation. La valeur par défaut est [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Exemple :
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

Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le taux de compression réel dépend du contenu de la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |