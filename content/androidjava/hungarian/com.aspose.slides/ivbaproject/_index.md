---
title: IVbaProject
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: VBA projektet képvisel, amely prezentációs makrókat tartalmaz.
type: docs
url: /hu/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

VBA projektet képvisel, amely prezentációs makrókat tartalmaz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja a VBA projekt nevét. |
| [getModules()](#getModules--) | Visszaadja az összes modult, amely a VBA projektben található. |
| [getReferences()](#getReferences--) | Visszaadja az összes hivatkozást, amely a VBA projektben található. |
| [toBinary()](#toBinary--) | Visszaadja a VBA projekt bináris reprezentációját OLE tárolóként. |
| [isPasswordProtected()](#isPasswordProtected--) | Megmutatja, hogy a VBAProject jelszóval védett-e a projekt tulajdonságok megtekintéséhez. |
### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja a VBA projekt nevét. Csak olvasható String.

**Visszaadja:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Visszaadja az összes modult, amely a VBA projektben található. Csak olvasható [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Visszaadja:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Visszaadja az összes hivatkozást, amely a VBA projektben található. Csak olvasható [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Visszaadja:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Visszaadja a VBA projekt bináris reprezentációját OLE tárolóként. Csak olvasható byte[].

**Visszaadja:**
byte[] - A VBA projekt bináris reprezentációja OLE tárolóként
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Megmutatja, hogy a VBAProject jelszóval védett-e a projekt tulajdonságok megtekintéséhez. Csak olvasható boolean.

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


**Visszaadja:**
boolean