---
title: VbaProject
second_title: Aspose.Slides för Java API-referens
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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VbaProject()](#VbaProject--) | Denna konstruktor skapar ett nytt VBA-projekt från grunden. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Denna konstruktor laddar ett VBA-projekt från den binära representationen av en OLE-behållare. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Returnerar namnet på VBA-projektet. |
| [getModules()](#getModules--) | Returnerar listan över alla moduler som ingår i VBA-projektet. |
| [getReferences()](#getReferences--) | Returnerar listan över alla referenser som ingår i VBA-projektet. |
| [toBinary()](#toBinary--) | Returnerar den binära representationen av VBA-projektet som OLE-behållare |
| [isPasswordProtected()](#isPasswordProtected--) | Anger om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

Denna konstruktor skapar ett nytt VBA-projekt från grunden. Projektet kommer att skapas i kodsidan 1252 Windows Latin 1 (ANSI).

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

Denna konstruktor laddar ett VBA-projekt från den binära representationen av en OLE-behållare.

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

Returnerar listan över alla moduler som ingår i VBA-projektet. Endast läsning [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returnerar:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

Returnerar listan över alla referenser som ingår i VBA-projektet. Endast läsning [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returnerar:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

Returnerar den binära representationen av VBA-projektet som OLE-behållare

**Returnerar:**
byte[] - Binär representation av VBA-projektet som OLE-behållare
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Anger om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Endast läsning boolean.

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