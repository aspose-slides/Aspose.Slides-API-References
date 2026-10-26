---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de rappel utilisée pour déterminer comment l'objet doit être traité lors de l'enregistrement.
type: docs
url: /fr/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Interface de rappel utilisée pour déterminer comment l'objet doit être traité lors de l'enregistrement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Détermine où l'objet doit être stocké. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Retourne une URL vers un objet externe. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Enregistre l'objet externe. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Détermine où l'objet doit être stocké. Cette méthode est appelée une fois pour chaque identifiant d'objet. Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec des identifiants différents.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Identifiant de l'objet. Cet identifiant est unique pour l'ensemble de l'opération d'enregistrement. |
| entityData | byte[] | Données binaires de l'objet. Ce paramètre peut être nul si les données binaires de l'objet ne sont pas encore générées. |
| semanticName | java.lang.String | Texte court décrivant la signification de l'objet. Le contrôleur peut l'utiliser comme partie du nom de l'objet externe, mais il revient au répartiteur de garantir que les noms seront uniques et ne contiendront que les caractères autorisés. |
| contentType | java.lang.String | Type MIME de l'objet. |
| recomendedExtension | java.lang.String | Extension de nom de fichier recommandée pour ce type MIME. |

**Retour :**
int - Décision
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Retourne une URL vers un objet externe. Cette méthode est toujours appelée si \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) a renvoyé [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) et peut être appelée si \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) a renvoyé [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) mais l'intégration est impossible. Elle peut être appelée plusieurs fois pour le même identifiant d'objet.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Identifiant de l'objet. Cet identifiant est unique pour l'ensemble de l'opération d'enregistrement. |
| referrer | int | Identifiant de l'objet référent ou 0 si l'objet est référencé par le document racine. Peut être utilisé pour générer un lien relatif. |

**Retour :**
java.lang.String - URL de l'objet externe ou null si cet objet doit être ignoré.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Enregistre l'objet externe.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | int | Identifiant de l'objet. Cet identifiant est unique pour l'ensemble de l'opération d'enregistrement. |
| entityData | byte[] | Données binaires de l'objet. Ce paramètre ne peut pas être nul. |