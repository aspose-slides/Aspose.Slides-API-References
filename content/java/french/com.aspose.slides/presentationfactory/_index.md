---
title: PresentationFactory
second_title: Référence de l'API Aspose.Slides pour Java
description: Permet de créer une présentation via l'interface COM
type: docs
url: /fr/com.aspose.slides/presentationfactory/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Permet de créer une présentation via l'interface COM

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Instance statique du factory de présentation. |
| [createPresentation()](#createPresentation--) | Crée une nouvelle présentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crée une nouvelle présentation avec des options de chargement supplémentaires |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Crée un objet PresentationInfo à partir d'un fichier et lie la présentation à celui-ci. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Crée un objet PresentationInfo à partir d'un flux et lie la présentation à celui-ci. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lit une présentation existante à partir d'un tableau |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lit une présentation existante à partir d'un flux |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lit une présentation existante à partir d'un fichier |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Récupère le texte brut des diapositives |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Récupère le texte brut des diapositives |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Récupère le texte brut des diapositives |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Instance statique du factory de présentation. Lecture seule [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Renvoie:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Crée une nouvelle présentation.

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nouvelle présentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Crée une nouvelle présentation avec des options de chargement supplémentaires

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nouvelle présentation
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Crée un nouvel objet PresentationInfo à partir d'un fichier et lie la présentation à celui-ci.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier de présentation. |

**Renvoie:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Info de présentation liée à la présentation.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Crée un nouvel objet PresentationInfo à partir d'un flux et lie la présentation à celui-ci. Obtient des informations sur la présentation dans le flux spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux de présentation. |

**Renvoie:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Info de présentation liée à la présentation.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Lit une présentation existante à partir d'un tableau

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Lit une présentation existante à partir d'un flux

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée à lire |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée à lire |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Lit une présentation existante à partir d'un fichier

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Nom du fichier |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Lit une présentation existante à partir d'un fichier avec des options de chargement supplémentaires

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Nom du fichier |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Récupère le texte brut des diapositives

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier d'entrée |
| mode | int | Mode d'extraction |

**Renvoie:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Récupère le texte brut des diapositives

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |

**Renvoie:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Récupère le texte brut des diapositives

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Renvoie:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives