---
title: IVbaProject
second_title: Aspose.Slides för Java API-referens
description: Representerar VBA-projekt med presentationsmakron.
type: docs
url: /sv/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Representerar VBA-projekt med presentationsmakron.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Returnerar namnet på VBA-projektet. |
| [getModules()](#getModules--) | Returnerar listan över alla moduler som ingår i VBA-projektet. |
| [getReferences()](#getReferences--) | Returnerar listan över alla referenser som ingår i VBA-projektet. |
| [toBinary()](#toBinary--) | Returnerar den binära representationen av VBA-projektet som OLE-container. |
| [isPasswordProtected()](#isPasswordProtected--) | Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. |
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar namnet på VBA-projektet. Read-only String.

**Returnerar:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Returnerar listan över alla moduler som ingår i VBA-projektet. Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returnerar:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Returnerar listan över alla referenser som ingår i VBA-projektet. Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returnerar:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Returnerar den binära representationen av VBA-projektet som OLE-container. Read-only byte[].

**Returnerar:**
byte[] - Binär representation av VBA-projektet som OLE-container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Read-only boolean.

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