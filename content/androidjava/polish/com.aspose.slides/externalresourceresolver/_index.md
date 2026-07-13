---
title: ExternalResourceResolver
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Klasa wywołania zwrotnego używana do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html i Svg.
type: docs
url: /pl/com.aspose.slides/externalresourceresolver/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Klasa wywołania zwrotnego używana do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html, Svg.

--------------------

Korzystanie z tego resolvera może stworzyć podatność, gdy dostarczony przez klienta plik HTML lub SVG spowoduje, że oprogramowanie serwera uzyska dostęp do lokalnego lub sieciowego pliku. Używać ostrożnie. Zaleca się nie określać ExternalResourceResolver wcale (odczytywane będą tylko osadzone obiekty) lub utworzyć podklasę, która sprawdza, czy podany uri jest prawidłowy.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozwiązuje bezwzględny URI na podstawie bazowego i względnego URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Rozwiązuje bezwzględny URI na podstawie bazowego i względnego URI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | java.lang.String | Bazowy URI obiektów łączących |
| relativeUri | java.lang.String | Względny URI do połączonego obiektu. |

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