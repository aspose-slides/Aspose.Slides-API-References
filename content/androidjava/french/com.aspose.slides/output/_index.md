---
title: Output
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection d'éléments de sortie pour IWebDocument.
type: docs
url: /fr/com.aspose.slides/output/
---
**Héritage :**
java.lang.Object
```
public final class Output
```

Représente une collection d'éléments de sortie pour IWebDocument.

## Méthodes

| Méthode | Description |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Ajoute un élément de sortie pour l'objet de contexte. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Ajoute un élément de sortie pour l'image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Ajoute un élément de sortie pour l'image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Ajoute un élément de sortie pour la vidéo. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Crée et ajoute un élément de fichier de sortie pour la police spécifiée. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Ajoute un élément de sortie pour le contenu texte. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Lie la ressource au fichier de sortie. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Renvoie le chemin pour une ressource donnée. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Ajoute un élément de sortie pour l'objet de contexte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin de sortie. |
| templateKey | java.lang.String | La clé du modèle utilisé pour la transformation de l'objet de contexte avant la sortie. |
| contextObject | TContextObject | Objet de contexte. |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objet pour l'objet de contexte.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Ajoute un élément de sortie pour l'image.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin de sortie. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Image à sortir. |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objet pour l'image.

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Ajoute un élément de sortie pour l'image.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin de sortie. |
| image | [IImage](../../com.aspose.slides/iimage) | Image à sortir. |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objet pour l'image.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Ajoute un élément de sortie pour la vidéo.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin de sortie. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vidéo à sortir. |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objet pour la vidéo.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Crée et ajoute un élément de fichier de sortie pour la police spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Le chemin du fichier où la police sera enregistrée. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Les données de la police à écrire dans la sortie. |
| fontStyle | int | Le style de la police (par exemple : Regular, Bold, Italic). |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Une instance [IOutputFile](../../com.aspose.slides/ioutputfile) pour la police générée.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Ajoute un élément de sortie pour le contenu texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin de sortie. |
| textContent | java.lang.String | Contenu à sortir. |

**Retour :**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) objet pour le contenu texte.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Lie la ressource au fichier de sortie.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Fichier de sortie. |
| obj | java.lang.Object | Objet ressource. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Renvoie le chemin pour une ressource donnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet ressource. |

**Retour :**
java.lang.String - Chemin de la ressource.