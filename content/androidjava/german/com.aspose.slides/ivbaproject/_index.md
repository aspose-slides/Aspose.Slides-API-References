---
title: IVbaProject
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein VBA-Projekt mit Präsentationsmakros dar.
type: docs
url: /de/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Stellt ein VBA-Projekt mit Präsentationsmakros dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Gibt den Namen des VBA-Projekts zurück. |
| [getModules()](#getModules--) | Gibt die Liste aller Module zurück, die im VBA-Projekt enthalten sind. |
| [getReferences()](#getReferences--) | Gibt die Liste aller Verweise zurück, die im VBA-Projekt enthalten sind. |
| [toBinary()](#toBinary--) | Gibt die binäre Darstellung des VBA-Projekts als OLE-Container zurück. |
| [isPasswordProtected()](#isPasswordProtected--) | Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. |
### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen des VBA-Projekts zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Gibt die Liste aller Module zurück, die im VBA-Projekt enthalten sind. Nur lesbar [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Rückgabe:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Gibt die Liste aller Verweise zurück, die im VBA-Projekt enthalten sind. Nur lesbar [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Rückgabe:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Gibt die binäre Darstellung des VBA-Projekts als OLE-Container zurück. Nur lesbar byte[].

**Rückgabe:**
byte[] - Binäre Darstellung des VBA-Projekts als OLE-Container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Gibt an, ob das VBAProject durch ein Passwort geschützt ist, um Projekteigenschaften anzuzeigen. Nur lesbar boolean.

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