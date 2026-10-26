---
title: VbaProjectFactory
second_title: Référence de l'API Aspose.Slides pour Java
description: Permet de créer un projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/vbaprojectfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Permet de créer un projet VBA via l'interface COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Instance statique de l'usine de projet VBA. |
| [createVbaProject()](#createVbaProject--) | Crée un nouveau projet VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lit le projet VBA depuis le conteneur OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Instance statique de l'usine de projet VBA. Lecture seule [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Retour :**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Crée un nouveau projet VBA.

**Retour :**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nouveau projet VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Lit le projet VBA depuis le conteneur OLE.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Retour :**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projet VBA lu