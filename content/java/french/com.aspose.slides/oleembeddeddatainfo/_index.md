---
title: OleEmbeddedDataInfo
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les informations de données intégrées pour l'objet OLE.
type: docs
url: /fr/com.aspose.slides/oleembeddeddatainfo/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Représente les informations de données intégrées pour l'objet OLE.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Crée de nouvelles informations de données intégrées pour l'objet OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Crée une nouvelle instance d'informations de données intégrées pour l'objet OLE. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Renvoie les données du fichier d'un objet OLE intégré en lecture seule byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Renvoie l'extension du fichier pour l'objet OLE intégré actuel en lecture seule String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Crée de nouvelles informations de données intégrées pour l'objet OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Crée une nouvelle instance d'informations de données intégrées pour l'objet OLE.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| embeddedFileData | byte[] | Données du fichier d'un objet OLE intégré byte[]. |
| embeddedFileExtension | java.lang.String | Extension du fichier pour l'objet OLE intégré actuel String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Renvoie les données du fichier d'un objet OLE intégré en lecture seule byte[].

**Renvoie :**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Renvoie l'extension du fichier pour l'objet OLE intégré actuel en lecture seule String.

**Renvoie :**
java.lang.String