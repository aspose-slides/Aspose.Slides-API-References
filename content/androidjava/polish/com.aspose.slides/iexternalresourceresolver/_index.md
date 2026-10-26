---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Interfejs wywołania zwrotnego służący do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html i Svg.
type: docs
url: /pl/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interfejs wywołania zwrotnego służący do rozwiązywania zewnętrznych zasobów podczas importu dokumentów Html i Svg.

## Metody

| Metoda | Opis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozwiązuje bezwzględny URI na podstawie URI bazowego i względnego. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Rozwiązuje bezwzględny URI na podstawie URI bazowego i względnego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | java.lang.String | Podstawowy URI obiektów linkujących |
| relativeUri | java.lang.String | Względny URI do połączonego obiektu. |

**Zwraca:**
java.lang.String - Bezwzględny URI lub null, jeśli względny URI nie może być rozwiązany.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Mapuje URI na obiekt zawierający rzeczywisty zasób.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Bezwzględny URI do obiektu. |

**Zwraca:**
java.io.InputStream - Obiekt InputStream lub null, jeśli zasób nie może być strumieniowany.