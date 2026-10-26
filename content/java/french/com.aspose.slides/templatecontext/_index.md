---
title: TemplateContext
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une interface d'objet modèle pour un moteur de modèles.
type: docs
url: /fr/com.aspose.slides/templatecontext/
---
**Héritage:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Représente une interface d'objet modèle pour un moteur de modèles.
## Méthodes

| Méthode | Description |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Crée un contexte de modèle enfant. |
| [getObject()](#getObject--) | Renvoie l'objet modèle. |
| [getOutput()](#getOutput--) | Renvoie la collection d'éléments de sortie du document hôte. |
| [getLocal()](#getLocal--) | Renvoie le stockage local du contexte de modèle actuel. |
| [getGlobal()](#getGlobal--) | Renvoie le stockage global du document hôte. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Crée un contexte de modèle enfant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| subModel | TSubModel | Objet modèle enfant. |

**Renvoie:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Nouveau contexte de modèle avec le modèle fourni et la collection de sortie du parent et le stockage global.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Renvoie l'objet modèle. Lecture seule Object.

**Renvoie:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Renvoie la collection d'éléments de sortie du document hôte. Lecture seule [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Renvoie:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Renvoie le stockage local du contexte de modèle actuel. Lecture seule [Storage](../../com.aspose.slides/storage).

**Renvoie:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Renvoie le stockage global du document hôte. Lecture seule [Storage](../../com.aspose.slides/storage).

**Renvoie:**
[Storage](../../com.aspose.slides/storage)