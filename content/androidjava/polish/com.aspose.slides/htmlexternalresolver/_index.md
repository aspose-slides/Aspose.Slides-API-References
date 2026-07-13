---
title: HtmlExternalResolver
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Obiekt wywołania zwrotnego używany przez procedurę importu HTML do uzyskiwania odwoływanych obiektów, takich jak obrazy.
type: docs
url: /pl/com.aspose.slides/htmlexternalresolver/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Obiekt wywołania zwrotnego używany przez procedurę importu HTML do uzyskiwania odwoływanych obiektów, takich jak obrazy.

--------------------

Użycie tego rozwiązania może stworzyć lukę bezpieczeństwa, gdy plik HTML dostarczony przez klienta spowoduje, że oprogramowanie serwera uzyska dostęp do lokalnego lub sieciowego pliku. Stosuj ostrożnie. Zaleca się nie podawać w ogóle HtmlExternalResolver (odczytywane będą tylko osadzone obiekty) lub utworzyć podklasę, która sprawdzi, czy podany URI jest prawidłowy.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozwiązuje bezwzględny URI na podstawie bazowego i względnego URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Rozwiązuje bezwzględny URI na podstawie bazowego i względnego URI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | java.lang.String | Bazowy URI obiektów linkujących |
| relativeUri | java.lang.String | Względny URI do połączonego obiektu. |

**Zwraca:**
java.lang.String - Bezpośredni URI lub null, jeśli nie można rozwiązać względnego URI.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapuje URI na obiekt zawierający rzeczywisty zasób.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Bezpośredni URI do obiektu. |

**Zwraca:**
java.io.InputStream - Obiekt InputStream lub null, jeśli zasób nie może być strumieniowany.