---
title: HtmlExternalResolver
second_title: Aspose.Slides dla Java – odniesienie API
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

Użycie tego rozwiązania może spowodować lukę bezpieczeństwa, gdy plik HTML dostarczony przez klienta spowoduje, że oprogramowanie serwera uzyska dostęp do lokalnego lub sieciowego pliku. Należy używać ostrożnie. Zaleca się nie podawać HtmlExternalResolver wcale (odczytywane będą tylko osadzone obiekty) lub utworzyć podklasę, która sprawdza, czy podany uri jest prawidłowy.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozwiązuje bezwzględny URI z bazowego i względnego URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Rozwiązuje bezwzględny URI z bazowego i względnego URI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | java.lang.String | Bazowy URI obiektów łączących |
| relativeUri | java.lang.String | Względny URI do powiązanego obiektu. |

**Zwraca:**
java.lang.String - Bezwzględny URI lub null, jeśli względny URI nie może zostać rozwiązany.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapuje URI na obiekt zawierający rzeczywisty zasób.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Bezwzględny URI do obiektu. |

**Zwraca:**
java.io.InputStream - Obiekt InputStream lub null, jeśli zasób nie może być strumieniowany.