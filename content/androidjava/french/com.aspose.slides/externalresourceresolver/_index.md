---
title: ExternalResourceResolver
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents HTML et SVG.
type: docs
url: /fr/com.aspose.slides/externalresourceresolver/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.

--------------------

L'utilisation de ce résolveur peut créer une vulnérabilité lorsqu'un fichier HTML ou SVG fourni par le client entraîne le serveur à accéder à un fichier local ou réseau. À utiliser avec prudence. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie la validité de l'URI spécifié.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Résout l'URI absolue à partir des URI de base et relatives. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Associe une URI à un objet contenant la ressource réelle. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Résout l'URI absolue à partir des URI de base et relatives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI de base des objets de liaison |
| relativeUri | java.lang.String | URI relative vers l'objet lié. |

**Retour :**
java.lang.String - URI absolue ou null si l'URI relative ne peut pas être résolue.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Associe une URI à un objet contenant la ressource réelle.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolue de l'objet. |

**Retour :**
java.io.InputStream - Un objet InputStream ou null si la ressource ne peut pas être diffusée.