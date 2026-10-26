---
title: VbaProject
second_title: Aspose.Slides for Android Java API referencia
description: A prezentáció makrókat tartalmazó VBA projektet ábrázolja.
type: docs
url: /hu/com.aspose.slides/vbaproject/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

A prezentáció makrókat tartalmazó VBA projektet ábrázol.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VbaProject()](#VbaProject--) | Ez a konstruktor új VBA projektet hoz létre a semmiből. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Ez a konstruktor a VBA projektet az OLE konténer bináris ábrázolásából tölti be. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja a VBA projekt nevét. |
| [getModules()](#getModules--) | Visszaadja az összes modult, amely a VBA projektben található. |
| [getReferences()](#getReferences--) | Visszaadja az összes hivatkozást, amely a VBA projektben található. |
| [toBinary()](#toBinary--) | Visszaadja a VBA projekt bináris ábrázolását OLE konténerként |
| [isPasswordProtected()](#isPasswordProtected--) | Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

Ez a konstruktor új VBA projektet hoz létre a semmiből. A projekt a 1252 Windows Latin 1 (ANSI) kódlapon lesz létrehozva

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

Ez a konstruktor a VBA projektet az OLE konténer bináris ábrázolásából tölti be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] |  |
### getName() {#getName--}
```
public final String getName()
```

Visszaadja a VBA projekt nevét. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

Visszaadja a VBA projektben található összes modul listáját. Csak olvasható [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Visszatérési érték:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

Visszaadja a VBA projektben található összes hivatkozás listáját. Csak olvasható [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Visszatérési érték:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

Visszaadja a VBA projekt bináris ábrázolását OLE konténerként

**Visszatérési érték:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható boolean .

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


**Visszatérési érték:**
boolean