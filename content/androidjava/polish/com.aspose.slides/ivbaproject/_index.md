---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje projekt VBA z makrami prezentacji.
type: docs
url: /pl/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Reprezentuje projekt VBA z makrami prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Zwraca nazwę projektu VBA. |
| [getModules()](#getModules--) | Zwraca listę wszystkich modułów zawartych w projekcie VBA. |
| [getReferences()](#getReferences--) | Zwraca listę wszystkich odwołań zawartych w projekcie VBA. |
| [toBinary()](#toBinary--) | Zwraca binarną reprezentację projektu VBA jako kontener OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. |
### getName() {#getName--}
```
public abstract String getName()
```


Zwraca nazwę projektu VBA. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Zwraca listę wszystkich modułów, które są zawarte w projekcie VBA. Tylko do odczytu [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Zwraca:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Zwraca listę wszystkich odwołań, które są zawarte w projekcie VBA. Tylko do odczytu [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Zwraca:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Zwraca binarną reprezentację projektu VBA jako kontener OLE. Tylko do odczytu byte[].

**Zwraca:**
byte[] - Binarna reprezentacja projektu VBA jako kontener OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. Tylko do odczytu boolean.

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