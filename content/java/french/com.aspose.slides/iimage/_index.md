---
title: IImage
second_title: Référence de l'API Aspose.Slides for Java
description: Représente une image raster ou vectorielle.
type: docs
url: /fr/com.aspose.slides/iimage/
---
**Toutes les interfaces implémentées :**  
com.aspose.ms.System.IDisposable  
```
public interface IImage extends System.IDisposable
```

Représente une image raster ou vectorielle.

--------------------

Cette interface fournit une abstraction commune pour la gestion des images raster et vectorielles. Les implémentations peuvent varier en fonction du type d’image sous-jacent.

## Méthodes

| Méthode | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Enregistre l’image dans un fichier. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Enregistre l’image dans un fichier au format spécifié. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre l’image dans un flux au format spécifié. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Enregistre l’image dans un fichier au format et à la qualité spécifiés. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Enregistre l’image dans un flux au format et à la qualité spécifiés. |
| [getSize()](#getSize--) | Obtient la taille de l’image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l’image en pixels. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l’image en pixels. |

### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Enregistre l’image dans un fichier.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Le chemin du fichier où l’image sera enregistrée. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Enregistre l’image dans un fichier au format spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Le chemin du fichier où l’image sera enregistrée. |
| format | int | Le format de l’image. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Enregistre l’image dans un flux au format spécifié.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où l’image sera enregistrée. |
| format | int | Le format de l’image. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Enregistre l’image dans un fichier au format et à la qualité spécifiés.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Le chemin du fichier où l’image sera enregistrée. |
| format | int | Le format de l’image. |
| quality | int | La qualité de l’image enregistrée (0 à 100). Ce paramètre n’affecte que l’enregistrement en [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) ; pour tous les autres formats, il est ignoré. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Enregistre l’image dans un flux au format et à la qualité spécifiés.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où l’image sera enregistrée. |
| format | int | Le format de l’image. |
| quality | int | La qualité de l’image enregistrée (0 à 100). Ce paramètre n’affecte que l’enregistrement en [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) ; pour tous les autres formats, il est ignoré. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

Obtient la taille de l’image.

**Renvoie :**  
java.awt.Dimension

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Obtient la largeur de l’image en pixels.

**Renvoie :**  
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Obtient la hauteur de l’image en pixels.

**Renvoie :**  
int