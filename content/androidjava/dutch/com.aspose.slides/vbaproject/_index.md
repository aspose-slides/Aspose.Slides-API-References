---
title: VbaProject
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een VBA-project voor met presentatiemacro’s.
type: docs
url: /nl/com.aspose.slides/vbaproject/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Stelt een VBA-project voor met presentatiemacro’s.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VbaProject()](#VbaProject--) | Deze constructor maakt een nieuw VBA-project vanaf nul. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Deze constructor laadt een VBA-project vanuit de binaire representatie van een OLE-container. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Retourneert de naam van het VBA-project. |
| [getModules()](#getModules--) | Retourneert de lijst van alle modules die in het VBA-project zijn opgenomen. |
| [getReferences()](#getReferences--) | Retourneert de lijst van alle referenties die in het VBA-project zijn opgenomen. |
| [toBinary()](#toBinary--) | Retourneert de binaire representatie van het VBA-project als OLE-container |
| [isPasswordProtected()](#isPasswordProtected--) | Geeft aan of het VBAProject wordt beschermd door een wachtwoord om project-eigenschappen te bekijken. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Deze constructor maakt een nieuw VBA-project vanaf nul. Het project wordt aangemaakt in codepagina 1252 Windows Latin 1 (ANSI)

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Deze constructor laadt een VBA-project vanuit de binaire representatie van een OLE-container.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van het VBA-project. Alleen-lezen String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Retourneert de lijst van alle modules die in het VBA-project zijn opgenomen. Alleen-lezen [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Retourneert de lijst van alle referenties die in het VBA-project zijn opgenomen. Alleen-lezen [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Retourneert de binaire representatie van het VBA-project als OLE-container

**Returns:**
byte[] - Binaire representatie van het VBA-project als OLE-container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Geeft aan of het VBAProject wordt beschermd door een wachtwoord om project-eigenschappen te bekijken. Alleen-lezen boolean .

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


**Returns:**
boolean