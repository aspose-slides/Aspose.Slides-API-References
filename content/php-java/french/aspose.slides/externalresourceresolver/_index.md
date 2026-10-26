---
title: ExternalResourceResolver
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/externalresourceresolver/
---
## ExternalResourceResolver classe

 Classe de rappel utilisée pour résoudre les ressources externes lors de l’import de documents Html, Svg.  
 L’utilisation de ce résolveur peut créer une vulnérabilité lorsqu’un fichier HTML ou SVG fourni par le client permet au logiciel serveur d’accéder à un fichier local ou réseau. Utilisez-le avec prudence. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie si l’URI spécifié est valide.
### ExternalResourceResolver {#ExternalResourceResolver}

| Nom | Description |
| --- | --- |
| ExternalResourceResolver() |  |

 **Retourne :**
ExternalResourceResolver


---


### getEntity {#getEntity}

| Nom | Description |
| --- | --- |
| getEntity (String) | Associe un URI à un objet contenant la ressource réelle. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| absoluteUri | String | URI absolu vers l’objet. |

 **Retourne :**
InputStream


---


### resolveUri {#resolveUri}

| Nom | Description |
| --- | --- |
| resolveUri (String, String) | Résout l’URI absolu à partir des URI de base et relatif. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| baseUri | String | URI de base des objets de liaison |
| relativeUri | String | URI relatif vers l’objet lié. |

 **Retourne :**
String


---