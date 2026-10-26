---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /pl/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interfejs wywołania zwrotnego używany do rozwiązywania zasobów zewnętrznych podczas importu dokumentów Html i Svg.

## Metody

| Metoda | Opis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozwiązuje absolutny URI z podstawowego i względnego URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na obiekt zawierający rzeczywisty zasób. |

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Rozwiązuje absolutny URI z podstawowego i względnego URI.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseUri | java.lang.String | Podstawowy URI obiektów linkujących |
| relativeUri | java.lang.String | Względny URI do powiązanego obiektu. |

**Zwraca:**
java.lang.String - Absolutny URI lub null, jeśli względny URI nie może zostać rozwiązany.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Mapuje URI na obiekt zawierający rzeczywisty zasób.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolutny URI do obiektu. |

**Zwraca:**
java.io.InputStream - Obiekt InputStream lub null, jeśli zasób nie może być strumieniowany.