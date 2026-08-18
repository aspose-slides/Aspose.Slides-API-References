---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: A VBA projektet képviseli, amely bemutató makrókat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

A VBA projektet képviseli, amely bemutató makrókat tartalmaz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja a VBA projekt nevét. |
| [getModules()](#getModules--) | Visszaadja az összes modult tartalmazó listát, amely a VBA projektben van. |
| [getReferences()](#getReferences--) | Visszaadja az összes hivatkozást tartalmazó listát, amely a VBA projektben van. |
| [toBinary()](#toBinary--) | Visszaadja a VBA projekt bináris reprezentációját OLE tárolóként. |
| [isPasswordProtected()](#isPasswordProtected--) | Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. |
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja a VBA projekt nevét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Visszaadja az összes modult tartalmazó listát, amely a VBA projektben van. Csak olvasható [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Visszatér:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Visszaadja az összes hivatkozást tartalmazó listát, amely a VBA projektben van. Csak olvasható [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Visszatér:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Visszaadja a VBA projekt bináris reprezentációját OLE tárolóként. Csak olvasható byte[].

**Visszatér:**
byte[] - A VBA projekt bináris reprezentációja OLE tárolóként
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható boolean.

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


**Visszatér:**
boolean