---
title: VbaProject
second_title: Aspose.Slides pour Android – Référence de l'API Java
description: Représente un projet VBA avec des macros de présentation.
type: docs
url: /fr/com.aspose.slides/vbaproject/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Représente un projet VBA avec des macros de présentation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VbaProject()](#VbaProject--) | Ce constructeur crée un nouveau projet VBA à partir de zéro. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Ce constructeur charge le projet VBA à partir de la représentation binaire du conteneur OLE. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Renvoie le nom du projet VBA. |
| [getModules()](#getModules--) | Renvoie la liste de tous les modules contenus dans le projet VBA. |
| [getReferences()](#getReferences--) | Renvoie la liste de toutes les références contenues dans le projet VBA. |
| [toBinary()](#toBinary--) | Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Ce constructeur crée un nouveau projet VBA à partir de zéro. Le projet sera créé avec la page de code 1252 Windows Latin 1 (ANSI)

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Ce constructeur charge le projet VBA à partir de la représentation binaire du conteneur OLE.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Renvoie le nom du projet VBA. Lecture seule String.

**Renvoie :**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Renvoie la liste de tous les modules contenus dans le projet VBA. Lecture seule [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Renvoie :**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Renvoie la liste de toutes les références contenues dans le projet VBA. Lecture seule [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Renvoie :**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE

**Renvoie :**
byte[] - Représentation binaire du projet VBA sous forme de conteneur OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
boolean