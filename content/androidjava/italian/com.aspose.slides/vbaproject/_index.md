---
title: VbaProject
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta un progetto VBA con macro di presentazione.
type: docs
url: /it/com.aspose.slides/vbaproject/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Rappresenta un progetto VBA con macro di presentazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VbaProject()](#VbaProject--) | Questo costruttore crea un nuovo progetto VBA da zero. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Questo costruttore carica il progetto VBA dalla rappresentazione binaria del contenitore OLE. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Restituisce il nome del progetto VBA. |
| [getModules()](#getModules--) | Restituisce l'elenco di tutti i moduli contenuti nel progetto VBA. |
| [getReferences()](#getReferences--) | Restituisce l'elenco di tutti i riferimenti contenuti nel progetto VBA. |
| [toBinary()](#toBinary--) | Restituisce la rappresentazione binaria del progetto VBA come contenitore OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Questo costruttore crea un nuovo progetto VBA da zero. Il progetto sarà creato nella pagina di codice Windows Latin 1 (ANSI) 1252

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Questo costruttore carica il progetto VBA dalla rappresentazione binaria del contenitore OLE.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Restituisce il nome del progetto VBA. Solo lettura String.

**Restituisce:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Restituisce l'elenco di tutti i moduli contenuti nel progetto VBA. Solo lettura [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Restituisce:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Restituisce l'elenco di tutti i riferimenti contenuti nel progetto VBA. Solo lettura [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Restituisce:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Restituisce la rappresentazione binaria del progetto VBA come contenitore OLE

**Restituisce:**
byte[] - Rappresentazione binaria del progetto VBA come contenitore OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indica se il VBAProject è protetto da una password per visualizzare le proprietà del progetto. Solo lettura boolean .

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