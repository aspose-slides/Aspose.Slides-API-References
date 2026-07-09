---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Représente une image SVG.
type: docs
url: /fr/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Représente une image SVG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Retourne le contenu SVG. |
| [getSvgData()](#getSvgData--) | Retourne les données SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Retourne l'interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents SVG. |
| [getBaseUri()](#getBaseUri--) | Retourne l'URI de base du SVG spécifié. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Enregistre l'image SVG en tant que fichier EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Retourne le contenu SVG. Lecture seule String.

**Renvoie :**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Retourne les données SVG. Lecture seule byte[].

**Renvoie :**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Retourne l'interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents SVG. Lecture seule [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Renvoie :**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Retourne l'URI de base du SVG spécifié. Utilisé pour résoudre les liens relatifs. Lecture seule String.

**Renvoie :**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Enregistre l'image SVG en tant que fichier EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafile
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
