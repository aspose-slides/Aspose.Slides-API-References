---  
title: IVbaProject  
second_title: Aspose.Slides for Android via Java API Reference  
description: Stelt een VBA-project voor met presentatiemacro's.  
type: docs  
url: /nl/com.aspose.slides/ivbaproject/  
---```
public interface IVbaProject
```

Stelt een VBA-project voor met presentatiemacro's.  
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Retourneert de naam van het VBA-project. |
| [getModules()](#getModules--) | Retourneert de lijst met alle modules die in het VBA-project zijn opgenomen. |
| [getReferences()](#getReferences--) | Retourneert de lijst met alle referenties die in het VBA-project zijn opgenomen. |
| [toBinary()](#toBinary--) | Retourneert de binaire weergave van het VBA-project als OLE-container. |
| [isPasswordProtected()](#isPasswordProtected--) | Geeft aan of het VBAProject is beschermd met een wachtwoord om projecteigenschappen te bekijken. |
### getName() {#getName--}
```
public abstract String getName()
```

Retourneert de naam van het VBA-project. Alleen-lezen String.

**Retour:**  
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Retourneert de lijst met alle modules die in het VBA-project zijn opgenomen. Alleen-lezen [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Retour:**  
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Retourneert de lijst met alle referenties die in het VBA-project zijn opgenomen. Alleen-lezen [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Retour:**  
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Retourneert de binaire weergave van het VBA-project als OLE-container. Alleen-lezen byte[].

**Retour:**  
byte[] - Binaire weergave van het VBA-project als OLE-container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Geeft aan of het VBAProject is beschermd met een wachtwoord om projecteigenschappen te bekijken. Alleen-lezen boolean.

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