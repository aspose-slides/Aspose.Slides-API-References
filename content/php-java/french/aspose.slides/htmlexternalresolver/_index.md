---
title: HtmlExternalResolver
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/htmlexternalresolver/
---
## HtmlExternalResolver classe

Objet de rappel utilisé par la routine d'importation HTML pour obtenir les objets référencés tels que les images.  
L'utilisation de ce résolveur pourrait créer une vulnérabilité lorsque le fichier HTML fourni par le client oblige le logiciel serveur à obtenir un fichier local ou réseau. À utiliser avec prudence. Il est recommandé de ne pas spécifier HtmlExternalResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie si l'URI spécifié est valide.

### HtmlExternalResolver {#HtmlExternalResolver}

| Nom | Description |
| --- | --- |
| HtmlExternalResolver() |  |

**Renvoie:**  
HtmlExternalResolver


---


### getEntity {#getEntity}

| Nom | Description |
| --- | --- |
| getEntity (String) | Mappe une URI vers un objet contenant la ressource réelle. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| absoluteUri | String | URI absolue vers l'objet. |

**Renvoie:**  
InputStream


---


### resolveUri {#resolveUri}

| Nom | Description |
| --- | --- |
| resolveUri (String, String) | Résout l'URI absolue à partir des URI de base et relative. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| baseUri | String | URI de base des objets de liaison |
| relativeUri | String | URI relative vers l'objet lié. |

**Renvoie:**  
String


---