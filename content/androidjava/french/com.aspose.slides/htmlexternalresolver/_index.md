---
title: HtmlExternalResolver
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Objet de rappel utilisé par la routine d'importation HTML pour obtenir les objets référencés tels que les images.
type: docs
url: /fr/com.aspose.slides/htmlexternalresolver/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Objet de rappel utilisé par la routine d’importation HTML pour obtenir les objets référencés tels que les images.

--------------------

L’utilisation de ce résolveur peut créer une vulnérabilité lorsqu’un fichier HTML fourni par le client entraîne le serveur à accéder à un fichier local ou réseau. Utilisez-le avec prudence. Il est recommandé de ne pas spécifier HtmlExternalResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie si l’uri spécifiée est valide.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Résout l’URI absolue à partir des URI de base et relatives. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Associe une URI à un objet contenant la ressource réelle. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Résout l’URI absolue à partir des URI de base et relatives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI de base des objets de liaison |
| relativeUri | java.lang.String | URI relative vers l’objet lié. |

**Retour :**
java.lang.String - URI absolue ou null si l’URI relative ne peut pas être résolue.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Associe une URI à un objet contenant la ressource réelle.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolue vers l’objet. |

**Retour :**
java.io.InputStream - Un objet InputStream ou null si la ressource ne peut pas être diffusée.