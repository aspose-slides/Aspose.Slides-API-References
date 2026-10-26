---
title: IVbaProjectFactory
second_title: Aspose.Slides pour Java Référence API
description: Permet de créer un projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Permet de créer un projet VBA via l'interface COM
## Méthodes

| Method | Description |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Crée un nouveau projet VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lit le projet VBA depuis un conteneur OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Crée un nouveau projet VBA.

**Renvoie:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nouveau projet VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Lit le projet VBA depuis un conteneur OLE.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] | Données Ole byte[] |

**Renvoie:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projet VBA lu