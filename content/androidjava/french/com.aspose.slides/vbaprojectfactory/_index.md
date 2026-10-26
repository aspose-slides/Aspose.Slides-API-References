---
title: VbaProjectFactory
second_title: Référence API Java d'Aspose.Slides pour Android
description: Permet de créer un projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/vbaprojectfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Permet de créer un projet VBA via l'interface COM.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Instance statique du factory de projet VBA. |
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

Instance statique du factory de projet VBA. Lecture seule [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Renvoie :**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)

### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```

Crée un nouveau projet VBA.

**Renvoie :**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nouveau projet VBA

### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```

Lit le projet VBA depuis le conteneur OLE.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

**Renvoie :**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projet VBA lu