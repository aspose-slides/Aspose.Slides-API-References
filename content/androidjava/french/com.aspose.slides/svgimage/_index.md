---
title: SvgImage
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une image SVG.
type: docs
url: /fr/com.aspose.slides/svgimage/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

Représente une image SVG.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Crée un nouvel objet SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Crée un nouvel objet SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crée un nouvel objet SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée un nouvel objet SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée un nouvel objet SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée un nouvel objet SvgImage. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getSvgData()](#getSvgData--) | Renvoie les données SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Renvoie l'interface de rappel utilisée pour résoudre les ressources externes pendant l'importation de documents Svg. |
| [getBaseUri()](#getBaseUri--) | Renvoie l'URI de base du Svg spécifié. |
| [getSvgContent()](#getSvgContent--) | Renvoie le contenu SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Enregistre l'image SVG sous forme de fichier EMF. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Données SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgContent | java.lang.String | Contenu SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Données SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| baseUri | java.lang.String | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgContent | java.lang.String | Contenu SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| baseUri | java.lang.String | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Crée un nouvel objet SvgImage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| baseUri | java.lang.String | URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Renvoie les données SVG. Lecture seule byte[].

**Renvoie:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Renvoie l'interface de rappel utilisée pour résoudre les ressources externes pendant l'importation de documents Svg. Lecture seule [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Renvoie:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Renvoie l'URI de base du Svg spécifié. Utilisé pour résoudre les liens relatifs. Lecture seule String.

**Renvoie:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Renvoie le contenu SVG. Lecture seule String.

**Renvoie:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Enregistre l'image SVG sous forme de fichier EMF.

--------------------

> ```
> // L'exemple suivant montre comment enregistrer l'image SVG dans le métafichier.
> // Crée la nouvelle image SVG
> ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
> // Enregistre l'image SVG sous forme de métafichier
> FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
> svgImage.writeAsEmf(fileStream);
> 
> // Ce sample montre comment ajouter l'image SVG en tant que métafichier à la collection d'images de la présentation.
> Presentation pres = new Presentation();
> try {
>     // Crée la nouvelle image SVG
>     ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>     ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>     // Enregistre l'image SVG sous forme de métafichier
>     svgImage.writeAsEmf(byteStream);
>     // Ajoute le métafichier à la collection d'images
>     pres.getImages().addImage(byteStream.toByteArray());
> } finally {
>     if (pres != null) pres.dispose();
> }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |