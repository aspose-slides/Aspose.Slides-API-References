---
title: IVbaProject
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un projet VBA avec des macros de présentation.
type: docs
url: /fr/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Représente un projet VBA avec des macros de présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Renvoie le nom du projet VBA. |
| [getModules()](#getModules--) | Renvoie la liste de tous les modules contenus dans le projet VBA. |
| [getReferences()](#getReferences--) | Renvoie la liste de toutes les références contenues dans le projet VBA. |
| [toBinary()](#toBinary--) | Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. |
### getName() {#getName--}
```
public abstract String getName()
```

Renvoie le nom du projet VBA. Lecture seule String.

**Renvoie :**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Renvoie la liste de tous les modules contenus dans le projet VBA. Lecture seule [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Renvoie :**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Renvoie la liste de toutes les références contenues dans le projet VBA. Lecture seule [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Renvoie :**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE. Lecture seule byte[].

**Renvoie :**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
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