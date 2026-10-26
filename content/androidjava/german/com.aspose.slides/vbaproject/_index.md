---
title: VbaProject
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein VBA-Projekt mit Präsentationsmakros dar.
type: docs
url: /de/com.aspose.slides/vbaprojekt/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Stellt ein VBA-Projekt mit Präsentationsmakros dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VbaProject()](#VbaProject--) | Dieser Konstruktor erstellt ein neues VBA-Projekt von Grund auf. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Dieser Konstruktor lädt ein VBA-Projekt aus der Binärdarstellung des OLE-Containers. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Gibt den Namen des VBA-Projekts zurück. |
| [getModules()](#getModules--) | Gibt die Liste aller Module zurück, die im VBA-Projekt enthalten sind. |
| [getReferences()](#getReferences--) | Gibt die Liste aller Referenzen zurück, die im VBA-Projekt enthalten sind. |
| [toBinary()](#toBinary--) | Gibt die Binärdarstellung des VBA-Projekts als OLE-Container zurück |
| [isPasswordProtected()](#isPasswordProtected--) | Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Dieser Konstruktor erstellt ein neues VBA-Projekt von Grund auf. Das Projekt wird in der Codepage 1252 Windows Latin 1 (ANSI) erstellt.

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Dieser Konstruktor lädt ein VBA-Projekt aus der Binärdarstellung des OLE-Containers.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Gibt den Namen des VBA-Projekts zurück. Nur-Lese String.

**Rückgabe:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Gibt die Liste aller Module zurück, die im VBA-Projekt enthalten sind. Nur-Lese [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Rückgabe:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Gibt die Liste aller Referenzen zurück, die im VBA-Projekt enthalten sind. Nur-Lese [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Rückgabe:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Gibt die Binärdarstellung des VBA-Projekts als OLE-Container zurück

**Rückgabe:**
byte[] - Binärdarstellung des VBA-Projekts als OLE-Container
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. Nur-Lese boolean .

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

**Rückgabe:**
boolean