---
title: IVbaProject
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un progetto VBA con macro di presentazione.
type: docs
url: /it/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Rappresenta un progetto VBA con macro di presentazione.
## Metodi

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Restituisce il nome del progetto VBA. |
| [getModules()](#getModules--) | Restituisce l'elenco di tutti i moduli contenuti nel progetto VBA. |
| [getReferences()](#getReferences--) | Restituisce l'elenco di tutti i riferimenti contenuti nel progetto VBA. |
| [toBinary()](#toBinary--) | Restituisce la rappresentazione binaria del progetto VBA come contenitore OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. |
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce il nome del progetto VBA. Sola lettura String.

**Restituisce:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Restituisce l'elenco di tutti i moduli contenuti nel progetto VBA. Sola lettura [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Restituisce:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Restituisce l'elenco di tutti i riferimenti contenuti nel progetto VBA. Sola lettura [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Restituisce:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Restituisce la rappresentazione binaria del progetto VBA come contenitore OLE. Sola lettura byte[].

**Restituisce:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Sola lettura boolean.

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


**Restituisce:**
boolean