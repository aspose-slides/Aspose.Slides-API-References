---
title: IPptxOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les options de sauvegarde des présentations OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /fr/com.aspose.slides/ipptxoptions/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Représente les options de sauvegarde des présentations OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Spécifie la classe de conformité à laquelle le document Presentation se conforme. |
| [setConformance(int value)](#setConformance-int-) | Spécifie la classe de conformité à laquelle le document Presentation se conforme. |
| [getZip64Mode()](#getZip64Mode--) | Spécifie si le format ZIP64 est utilisé pour le document Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Spécifie si le format ZIP64 est utilisé pour le document Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Spécifie si la miniature de la présentation sera rafraîchie. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Spécifie si la miniature de la présentation sera rafraîchie. |
| [getCompressionLevel()](#getCompressionLevel--) | Spécifie le niveau de compression utilisé lors de la sauvegarde du document Presentation. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Spécifie le niveau de compression utilisé lors de la sauvegarde du document Presentation. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Spécifie la classe de conformité à laquelle le document Presentation se conforme. La valeur par défaut est [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Renvoie :**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Spécifie la classe de conformité à laquelle le document Presentation se conforme. La valeur par défaut est [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Spécifie si le format ZIP64 est utilisé pour le document Presentation. La valeur par défaut est [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
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
public abstract boolean getRefreshThumbnail()
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
public abstract void setRefreshThumbnail(boolean value)
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
public abstract int getCompressionLevel()
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
public abstract void setCompressionLevel(int value)
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

Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le rapport de compression réel dépend du contenu de la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |