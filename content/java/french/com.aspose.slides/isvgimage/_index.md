---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
url: /fr/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Représente une image SVG.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Renvoie le contenu SVG. |
| [getSvgData()](#getSvgData--) | Renvoie les données SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Renvoie l'interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents SVG. |
| [getBaseUri()](#getBaseUri--) | Renvoie l'URI de base du SVG spécifié. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Enregistre l'image SVG au format EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Renvoie le contenu SVG. Lecture seule String.

**Renvoie:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Renvoie les données SVG. Lecture seule byte[].

**Renvoie:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Renvoie l'interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents SVG. Lecture seule [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Renvoie:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Renvoie l'URI de base du SVG spécifié. Utilisé pour résoudre les liens relatifs. Lecture seule String.

**Renvoie:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Enregistre l'image SVG au format EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Crée la nouvelle image SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Enregistre l'image SVG en tant que métafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Crée la nouvelle image SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Enregistre l'image SVG en tant que métafile
>      svgImage.writeAsEmf(byteStream);
>      // Ajoute le métafile à la collection d'images
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |