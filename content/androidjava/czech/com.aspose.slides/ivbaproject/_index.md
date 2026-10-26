---
title: IVbaProject
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje VBA projekt s makry prezentace.
type: docs
url: /cs/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Reprezentuje VBA projekt s makry prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Vrací název VBA projektu. |
| [getModules()](#getModules--) | Vrací seznam všech modulů, které jsou obsaženy ve VBA projektu. |
| [getReferences()](#getReferences--) | Vrací seznam všech referencí, které jsou obsaženy ve VBA projektu. |
| [toBinary()](#toBinary--) | Vrací binární reprezentaci VBA projektu jako OLE kontejner. |
| [isPasswordProtected()](#isPasswordProtected--) | Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. |
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název VBA projektu. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Vrací seznam všech modulů, které jsou obsaženy ve VBA projektu. Pouze pro čtení [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Vrací:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Vrací seznam všech referencí, které jsou obsaženy ve VBA projektu. Pouze pro čtení [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Vrací:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Vrací binární reprezentaci VBA projektu jako OLE kontejner. Pouze pro čtení byte[].

**Vrací:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze pro čtení boolean.

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


**Vrací:**
boolean