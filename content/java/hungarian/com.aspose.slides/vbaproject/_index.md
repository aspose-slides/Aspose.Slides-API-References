---
title: VbaProject
second_title: Aspose.Slides for Java API Referencia
description: VBA projektet reprezentál, amely bemutató makrókat tartalmaz.
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

VBA projektet reprezentál, amely bemutató makrókat tartalmaz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [VbaProject()](#VbaProject--) | Ez a konstruktor új VBA projektet hoz létre a semmiből. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Ez a konstruktor betölti a VBA projektet az OLE tároló bináris ábrázolásából. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getName()](#getName--) | |
| [getModules()](#getModules--) | |
| [getReferences()](#getReferences--) | |
| [toBinary()](#toBinary--) | |
| [isPasswordProtected()](#isPasswordProtected--) | |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Ez a konstruktor új VBA projektet hoz létre a semmiből. A projekt a 1252 Windows Latin 1 (ANSI) kódlapon jön létre

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Ez a konstruktor betölti a VBA projektet az OLE tároló bináris ábrázolásából.

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


Visszaadja az összes modult, amely a VBA projektben van. Csak olvasható [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Visszatérési érték:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Visszaadja az összes hivatkozást, amely a VBA projektben van. Csak olvasható [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Visszatérési érték:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Visszaadja a VBA projekt bináris ábrázolását OLE tárolóként

**Visszatérési érték:**
byte[] - A VBA projekt bináris ábrázolása OLE tárolóként
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Megmutatja, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható boolean.

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