---
title: OOXMLException
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje standardní interní typ výjimky související s formátem souboru Office Open XML.
type: docs
url: /cs/com.aspose.slides/ooxmlexception/
---
**Dědičnost:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OOXMLException extends System.Exception
```

Reprezentuje standardní interní typ výjimky související s formátem souboru Office Open XML.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OOXMLException()](#OOXMLException--) | Výchozí konstruktor. |
| [OOXMLException(String message)](#OOXMLException-java.lang.String-) | Konstruktor umožňující přidání zprávy k této výjimce. |
| [OOXMLException(String message, RuntimeException exception)](#OOXMLException-java.lang.String-java.lang.RuntimeException-) | Konstruktor pro výjimku obsahující zprávu a vloženou výjimku. |
### OOXMLException() {#OOXMLException--}
```
public OOXMLException()
```


Výchozí konstruktor.

### OOXMLException(String message) {#OOXMLException-java.lang.String-}
```
public OOXMLException(String message)
```


Konstruktor umožňující přidání zprávy k této výjimce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | zpráva |

### OOXMLException(String message, RuntimeException exception) {#OOXMLException-java.lang.String-java.lang.RuntimeException-}
```
public OOXMLException(String message, RuntimeException exception)
```


Konstruktor pro výjimku obsahující zprávu a vloženou výjimku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| message | java.lang.String | zpráva |
| exception | java.lang.RuntimeException | originální výjimka |