---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface pour les arguments de chargement de ressources externes.
type: docs
url: /fr/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface pour les arguments de chargement de ressources externes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI d'origine de la ressource telle qu'elle est spécifiée dans la présentation importée. |
| [getUri()](#getUri--) | URI de la ressource qui est utilisée pour le téléchargement si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI de la ressource qui est utilisée pour le téléchargement si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Définit les données fournies par l'utilisateur pour la ressource qui sont utilisées si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |

### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

URI d'origine de la ressource telle qu'elle est spécifiée dans la présentation importée.

**Retourne :**
java.lang.String

### getUri() {#getUri--}
```
public abstract String getUri()
```

URI de la ressource qui est utilisée pour le téléchargement si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initialement, il est définie sur l'URI d'origine de la ressource, mais peut être redéfini à n'importe quelle valeur.

**Retourne :**
java.lang.String

### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

URI de la ressource qui est utilisée pour le téléchargement si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Initialement, il est définie sur l'URI d'origine de la ressource, mais peut être redéfini à n'importe quelle valeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Définit les données fournies par l'utilisateur pour la ressource qui sont utilisées si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) renvoie [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Données fournies de la ressource byte[] |