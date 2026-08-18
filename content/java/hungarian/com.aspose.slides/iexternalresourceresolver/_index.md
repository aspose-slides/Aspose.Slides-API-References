---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /hu/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Callback interfész, amely a külső erőforrások feloldására szolgál HTML és SVG dokumentumok importálása során.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Megoldja az abszolút URI-t a bázis és a relatív URI-k alapján. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Egy URI-t egy olyan objektumhoz rendel, amely a tényleges erőforrást tartalmazza. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Megoldja az abszolút URI-t a bázis és a relatív URI-k alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | java.lang.String | Az összekapcsolt objektumok alap URI-ja |
| relativeUri | java.lang.String | A kapcsolt objektum relatív URI-ja. |

**Visszatérési érték:**
java.lang.String - Az abszolút URI vagy null, ha a relatív URI nem oldható fel.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Egy URI-t egy olyan objektumhoz rendel, amely a tényleges erőforrást tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatérési érték:**
java.io.InputStream - Egy InputStream objektum vagy null, ha az erőforrás nem streamelhető.