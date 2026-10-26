---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /nl/com.aspose.slides/ivbaproject/
---``` 
public interface IVbaProject 
```

Stelt een VBA-project met presentatiemacro's voor.
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getName()](#getName--) | Geeft de naam van het VBA-project terug. |
| [getModules()](#getModules--) | Geeft de lijst van alle modules die in het VBA-project zijn opgenomen terug. |
| [getReferences()](#getReferences--) | Geeft de lijst van alle referenties die in het VBA-project zijn opgenomen terug. |
| [toBinary()](#toBinary--) | Geeft de binaire weergave van het VBA-project als OLE-container terug. |
| [isPasswordProtected()](#isPasswordProtected--) | Geeft aan of het VBAProject wordt beschermd door een wachtwoord om projecteigenschappen te bekijken. |
### getName() {#getName--}
```
public abstract String getName()
```


Geeft de naam van het VBA-project terug. Alleen-lezen String.

**Retour:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Geeft de lijst van alle modules die in het VBA-project zijn opgenomen terug. Alleen-lezen [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Retour:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Geeft de lijst van alle referenties die in het VBA-project zijn opgenomen terug. Alleen-lezen [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Retour:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Geeft de binaire weergave van het VBA-project als OLE-container terug. Alleen-lezen byte[].

**Retour:**
byte[] - Binaire representatie van het VBA-project als OLE-container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Geeft aan of het VBAProject wordt beschermd door een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen boolean.

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

**Retour:**
boolean