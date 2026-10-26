---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /cs/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Reprezentuje projekt VBA s makry prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Vrací název projektu VBA. |
| [getModules()](#getModules--) | Vrací seznam všech modulů, které jsou součástí projektu VBA. |
| [getReferences()](#getReferences--) | Vrací seznam všech odkazů, které jsou součástí projektu VBA. |
| [toBinary()](#toBinary--) | Vrací binární reprezentaci projektu VBA jako kontejner OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. |
### getName() {#getName--}
```
public abstract String getName()
```


Vrací název projektu VBA. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Vrací seznam všech modulů, které jsou součástí projektu VBA. Pouze pro čtení [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Vrací:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Vrací seznam všech odkazů, které jsou součástí projektu VBA. Pouze pro čtení [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Vrací:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Vrací binární reprezentaci projektu VBA jako kontejner OLE. Pouze pro čtení byte[].

**Vrací:**
byte[] - Binární reprezentace projektu VBA jako kontejner OLE
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