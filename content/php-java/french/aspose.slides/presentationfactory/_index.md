---
title: PresentationFactory
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/presentationfactory/
---
## classe PresentationFactory

 Permet de créer une présentation via l'interface COM

### PresentationFactory {#PresentationFactory}

| Nom | Description |
| --- | --- |
| PresentationFactory() |  |

 **Renvoie :**
PresentationFactory


---


### createPresentation {#createPresentation}

| Nom | Description |
| --- | --- |
| createPresentation () | Crée une nouvelle présentation. |

 **Renvoie :**
[Presentation](../presentation)


---


### createPresentation {#createPresentation}

| Nom | Description |
| --- | --- |
| createPresentation ([LoadOptions](../loadoptions)) | Crée une nouvelle présentation avec des options de chargement supplémentaires |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| options | [LoadOptions](../loadoptions) | Options de chargement |

 **Renvoie :**
[Presentation](../presentation)


---


### getInstance {#getInstance}

| Nom | Description |
| --- | --- |
| getInstance () | Instance statique du fabriquant de présentations. Lecture seule PresentationFactory. |

 **Renvoie :**
PresentationFactory


---


### getPresentationInfo {#getPresentationInfo}

| Nom | Description |
| --- | --- |
| getPresentationInfo (String) | Crée un nouvel objet PresentationInfo à partir d'un fichier et y associe la présentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Fichier de présentation. |

 **Renvoie :**
[PresentationInfo](../presentationinfo)


---


### getPresentationInfo {#getPresentationInfo}

| Nom | Description |
| --- | --- |
| getPresentationInfo (InputStream) | Crée un nouvel objet PresentationInfo à partir d'un flux et y associe la présentation. Obtient des informations sur la présentation dans le flux spécifié. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux de présentation. |

 **Renvoie :**
[PresentationInfo](../presentationinfo)


---


### getPresentationText {#getPresentationText}

| Nom | Description |
| --- | --- |
| getPresentationText (String, int) | Récupère le texte brut des diapositives |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Fichier d'entrée |
| mode | int | Mode d'extraction |

 **Renvoie :**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| Nom | Description |
| --- | --- |
| getPresentationText (InputStream, int) | Récupère le texte brut des diapositives |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |

 **Renvoie :**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| Nom | Description |
| --- | --- |
| getPresentationText (InputStream, int, [LoadOptions](../loadoptions)) | Récupère le texte brut des diapositives |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d'entrée |
| mode | int | Mode d'extraction |
| options | [LoadOptions](../loadoptions) | Options de chargement |

 **Renvoie :**
[PresentationText](../presentationtext)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (byte[]) | Lit une présentation existante à partir d'un tableau |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |

 **Renvoie :**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (byte[], [LoadOptions](../loadoptions)) | Lit une présentation existante à partir d'un tableau avec des options de chargement supplémentaires |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| data | byte[] | Tableau à lire |
| options | [LoadOptions](../loadoptions) | Options de chargement |

 **Renvoie :**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (InputStream) | Lit une présentation existante à partir d'un flux |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d'entrée à lire |

 **Renvoie :**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (InputStream, [LoadOptions](../loadoptions)) | Lit une présentation existante à partir d'un flux avec des options de chargement supplémentaires |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux d'entrée à lire |
| options | [LoadOptions](../loadoptions) | Options de chargement |

 **Renvoie :**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (String) | Lit une présentation existante à partir d'un fichier |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Nom de fichier |

 **Renvoie :**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Nom | Description |
| --- | --- |
| readPresentation (String, [LoadOptions](../loadoptions)) | Lit une présentation existante à partir d'un fichier avec des options de chargement supplémentaires |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| file | String | Nom de fichier |
| options | [LoadOptions](../loadoptions) | Options de chargement |

 **Renvoie :**
[Presentation](../presentation)


---