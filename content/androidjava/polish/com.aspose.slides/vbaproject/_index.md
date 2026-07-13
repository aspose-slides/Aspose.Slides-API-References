---
title: VbaProject
second_title: Aspose.Slides for Android - odniesienie API Java
description: Reprezentuje projekt VBA z makrami prezentacji.
type: docs
url: /pl/com.aspose.slides/vbaproject/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Reprezentuje projekt VBA z makrami prezentacji.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [VbaProject()](#VbaProject--) | Ten konstruktor tworzy nowy projekt VBA od podstaw. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Ten konstruktor wczytuje projekt VBA z binarnej reprezentacji kontenera OLE. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Zwraca nazwę projektu VBA. |
| [getModules()](#getModules--) | Zwraca listę wszystkich modułów, które są zawarte w projekcie VBA. |
| [getReferences()](#getReferences--) | Zwraca listę wszystkich odwołań, które są zawarte w projekcie VBA. |
| [toBinary()](#toBinary--) | Zwraca binarną reprezentację projektu VBA jako kontener OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Ten konstruktor tworzy nowy projekt VBA od podstaw. Projekt zostanie utworzony w kodowaniu 1252 Windows Latin 1 (ANSI)

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Ten konstruktor wczytuje projekt VBA z binarnej reprezentacji kontenera OLE.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Zwraca nazwę projektu VBA. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Zwraca listę wszystkich modułów, które są zawarte w projekcie VBA. Tylko do odczytu [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Zwraca:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Zwraca listę wszystkich odwołań, które są zawarte w projekcie VBA. Tylko do odczytu [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Zwraca:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Zwraca binarną reprezentację projektu VBA jako kontener OLE

**Zwraca:**
byte[] - Binarna reprezentacja projektu VBA jako kontener OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. Tylko do odczytu boolean .

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

**Zwraca:**
boolean