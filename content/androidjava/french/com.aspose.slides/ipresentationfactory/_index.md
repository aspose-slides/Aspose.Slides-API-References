---
title: IPresentationFactory
second_title: Aspose.Slides pour Android via Java API Reference
description: Permet de créer une présentation via l'interface COM
type: docs
url: /fr/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Permet de créer une présentation via l'interface COM

## Méthodes

| Méthode | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Crée une nouvelle présentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crée une nouvelle présentation avec des options de chargement supplémentaires |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Obtient des informations sur la présentation dans le fichier spécifié. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Obtient des informations sur la présentation dans le flux spécifié. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lit une présentation existante à partir d'un tableau |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lit une présentation existante à partir d'un flux |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lit une présentation existante à partir d'un fichier |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Récupère le texte brut des diapositives |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Récupère le texte brut des diapositives |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Récupère le texte brut des diapositives |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Crée une nouvelle présentation.

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Nouvelle présentation

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Crée une nouvelle présentation avec des options de chargement supplémentaires

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Nouvelle présentation

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Obtient des informations sur la présentation dans le fichier spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier de présentation. |

**Retour :**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informations sur la présentation

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Obtient des informations sur la présentation dans le flux spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux de présentation. |

**Retour :**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informations sur la présentation.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Lit une présentation existante à partir d'un tableau

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Lit une présentation existante à partir d'un flux

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée à lire |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée à lire |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Lit une présentation existante à partir d'un fichier

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Nom du fichier |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Lit une présentation existante à partir d'un fichier avec des options de chargement supplémentaires

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Nom du fichier |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation) - Présentation lue

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Récupère le texte brut des diapositives

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier d'entrée |
| mode | int | Mode d'extraction |

**Retour :**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Récupère le texte brut des diapositives

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |

**Retour :**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Récupère le texte brut des diapositives

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Options de chargement |

**Retour :**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'instance de PresentationText contenant le tableau SlideText représentant le texte brut des diapositives