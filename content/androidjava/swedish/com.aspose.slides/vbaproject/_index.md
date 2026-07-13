---
title: VbaProject
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar VBA-projekt med presentationsmakron.
type: docs
url: /sv/com.aspose.slides/vbaproject/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Representerar VBA-projekt med presentationsmakron.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [VbaProject()](#VbaProject--) | Den här konstruktorn skapar ett nytt VBA-projekt från grunden. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Den här konstruktorn läser in VBA-projekt från den binära representationen av en OLE-container. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Returnerar namnet på VBA-projektet. |
| [getModules()](#getModules--) | Returnerar listan över alla moduler som finns i VBA-projektet. |
| [getReferences()](#getReferences--) | Returnerar listan över alla referenser som finns i VBA-projektet. |
| [toBinary()](#toBinary--) | Returnerar den binära representationen av VBA-projektet som OLE-container |
| [isPasswordProtected()](#isPasswordProtected--) | Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Den här konstruktorn skapar ett nytt VBA-projekt från grunden. Projektet kommer att skapas i 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Den här konstruktorn läser in VBA-projekt från den binära representationen av en OLE-container.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Returnerar namnet på VBA-projektet. Endast läsning String.

**Returnerar:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Returnerar listan över alla moduler som finns i VBA-projektet. Endast läsning [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returnerar:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Returnerar listan över alla referenser som finns i VBA-projektet. Endast läsning [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returnerar:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Returnerar den binära representationen av VBA-projektet som OLE-container

**Returnerar:**
byte[] - Binär representation av VBA-projektet som OLE-container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Endast läsning boolean .

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


**Returnerar:**
boolean