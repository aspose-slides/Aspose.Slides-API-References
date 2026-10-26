---
title: ExternalResourceResolver
second_title: Odwołanie do API Aspose.Slides dla Javy
description: Klasa wywołania zwrotnego używana do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html i Svg.
type: docs
url: /pl/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Klasa wywołania zwrotnego używana do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html i Svg.

--------------------

Użycie tego rozwiązania może stworzyć podatność, gdy dostarczony przez klienta plik HTML lub SVG spowoduje, że oprogramowanie serwera uzyska dostęp do lokalnego lub sieciowego pliku. Należy stosować ostrożnie. Zaleca się nie podawać w ogóle ExternalResourceResolver (odczytane zostaną tylko osadzone obiekty) lub utworzyć podklasę, która sprawdzi, czy podany uri jest prawidłowy.

## Konstruktorzy

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
| baseUri | java.lang.String | Bazowy URI obiektów powiązanych |
| relativeUri | java.lang.String | Względny URI do obiektu powiązanego. |

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