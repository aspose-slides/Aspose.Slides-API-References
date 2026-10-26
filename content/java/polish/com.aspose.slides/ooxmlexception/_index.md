---
title: OOXMLException
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje standardowy wewnętrzny typ wyjątku związany z formatem pliku Office Open XML.
type: docs
url: /pl/com.aspose.slides/ooxmlexception/
---
**Dziedziczenie:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Reprezentuje standardowy wewnętrzny typ wyjątku związany z formatem pliku Office Open XML.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Konstruktor domyślny. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Konstruktor umożliwiający dodanie komunikatu do tego wyjątku. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Konstruktor dla wyjątku zawierającego komunikat i zagnieżdżony wyjątek. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```


Konstruktor domyślny.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```


Konstruktor umożliwiający dodanie komunikatu do tego wyjątku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | komunikat |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```


Konstruktor dla wyjątku zawierającego komunikat i zagnieżdżony wyjątek.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| message | java.lang.String | komunikat |
| exception | java.lang.RuntimeException | oryginalny wyjątek |