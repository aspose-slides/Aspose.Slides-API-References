---
title: IVbaProject
second_title: Aspose.Slides för Android via Java API-referens
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
| [getModules()](#getModules--) | Returnerar listan över alla moduler som finns i VBA-projektet. |
| [getReferences()](#getReferences--) | Returnerar listan över alla referenser som finns i VBA-projektet. |
| [toBinary()](#toBinary--) | Returnerar den binära representationen av VBA-projektet som OLE-behållare. |
| [isPasswordProtected()](#isPasswordProtected--) | Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. |
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar namnet på VBA-projektet. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Returnerar listan över alla moduler som finns i VBA-projektet. Skrivskyddad [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returnerar:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Returnerar listan över alla referenser som finns i VBA-projektet. Skrivskyddad [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returnerar:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Returnerar den binära representationen av VBA-projektet som OLE-behållare. Skrivskyddad byte[].

**Returnerar:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Indikerar om VBAProject är skyddat med ett lösenord för att visa projektets egenskaper. Skrivskyddad boolean.

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