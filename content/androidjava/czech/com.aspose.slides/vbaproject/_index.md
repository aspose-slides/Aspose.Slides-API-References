---
title: VbaProject
second_title: Aspose.Slides pro Android přes odkaz na Java API
description: Reprezentuje VBA projekt s makry prezentace.
type: docs
url: /cs/com.aspose.slides/vbaproject/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Reprezentuje VBA projekt s makry prezentace.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [VbaProject()](#VbaProject--) | Tento konstruktor vytváří nový VBA projekt od nuly. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Tento konstruktor načítá VBA projekt z binární reprezentace OLE kontejneru. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Vrací název VBA projektu. |
| [getModules()](#getModules--) | Vrací seznam všech modulů obsažených v VBA projektu. |
| [getReferences()](#getReferences--) | Vrací seznam všech referencí obsažených v VBA projektu. |
| [toBinary()](#toBinary--) | Vrací binární reprezentaci VBA projektu jako OLE kontejner |
| [isPasswordProtected()](#isPasswordProtected--) | Indikuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

Tento konstruktor vytváří nový VBA projekt od nuly. Projekt bude vytvořen v kódové stránce 1252 Windows Latin 1 (ANSI).

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

Tento konstruktor načítá VBA projekt z binární reprezentace OLE kontejneru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] |  |
### getName() {#getName--}
```
public final String getName()
```

Vrací název VBA projektu. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

Vrací seznam všech modulů obsažených v VBA projektu. Pouze pro čtení [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Vrací:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

Vrací seznam všech referencí obsažených v VBA projektu. Pouze pro čtení [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Vrací:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

Vrací binární reprezentaci VBA projektu jako OLE kontejner

**Vrací:**
byte[] - Binární reprezentace VBA projektu jako OLE kontejner
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Indikuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze pro čtení  boolean .

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