---
title: IPptxOptions
second_title: Référence de l'API Aspose.Slides for Java
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
| [getCompressionLevel()](#getCompressionLevel--) | Spécifie le niveau de compression utilisé lors de la sauvegarde du document de présentation. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Spécifie le niveau de compression utilisé lors de la sauvegarde du document de présentation. |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Spécifie la classe de conformité à laquelle le document Presentation se conforme. La valeur par défaut est [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retourne :**
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

**Retourne :**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

Spécifie si la miniature de la présentation sera rafraîchie. Booléen lecture/écriture. La valeur par défaut est **true**.

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

Lorsque la valeur de l'option est **true**, la nouvelle miniature sera générée.

Lorsque la valeur de l'option est **false**, la miniature actuelle sera enregistrée telle quelle.

**Retourne :**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Spécifie si la miniature de la présentation sera rafraîchie. Booléen lecture/écriture. La valeur par défaut est **true**.

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

Lorsque la valeur de l'option est **true**, la nouvelle miniature sera générée.

Lorsque la valeur de l'option est **false**, la miniature actuelle sera enregistrée telle quelle.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Spécifie le niveau de compression utilisé lors de la sauvegarde du document de présentation. La valeur par défaut est [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le taux de compression réel dépend du contenu de la présentation.

**Retourne :**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Spécifie le niveau de compression utilisé lors de la sauvegarde du document de présentation. La valeur par défaut est [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Des niveaux de compression plus élevés produisent des fichiers plus petits mais nécessitent plus de temps de traitement. Le taux de compression réel dépend du contenu de la présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |