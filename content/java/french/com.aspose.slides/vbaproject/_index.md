---
title: VbaProject
second_title: Référence de l'API Aspose.Slides pour Java
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
| [VbaProject()](#VbaProject--) | This constructor creates new VBA project from scratch. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | This constructor loads VBA project from binary representation of OLE container. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Returns the name of the VBA project. |
| [getModules()](#getModules--) | Returns the list of all modules that are contained in the VBA project. |
| [getReferences()](#getReferences--) | Returns the list of all references that are contained in the VBA project. |
| [toBinary()](#toBinary--) | Returns the binary representation of the VBA project as OLE container |
| [isPasswordProtected()](#isPasswordProtected--) | Indicates whether the VBAProject is protected by a password to view project properties. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Ce constructeur crée un nouveau projet VBA à partir de zéro. Le projet sera créé dans la page de code Windows Latin 1 (ANSI) 1252.

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

**Valeur de retour :**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Renvoie la liste de tous les modules contenus dans le projet VBA. Lecture seule [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Valeur de retour :**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Renvoie la liste de toutes les références contenues dans le projet VBA. Lecture seule [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Valeur de retour :**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE

**Valeur de retour :**
byte[] - Représentation binaire du projet VBA sous forme de conteneur OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indique si le VBAProject est protégé par un mot de passe pour visualiser les propriétés du projet. Lecture seule boolean .

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


**Retour :**
boolean