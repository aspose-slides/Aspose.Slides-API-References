---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android Java API hivatkozás
description: Visszahívási interfész, amely külső erőforrások feloldására szolgál HTML és SVG dokumentumok importálása során.
type: docs
url: /hu/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Visszahívási interfész, amely a Html, Svg dokumentumok importálása során külső erőforrások feloldására szolgál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Feloldja a teljes URI-t az alap és relatív URI-kból. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Leképezi az URI-t egy objektumra, amely a tényleges erőforrást tartalmazza. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Feloldja a teljes URI-t az alap és relatív URI-kból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | java.lang.String | A hivatkozó objektumok alap URI-ja |
| relativeUri | java.lang.String | A linkelt objektum relatív URI-ja. |

**Visszatér:**
java.lang.String - Abszolút URI vagy null, ha a relatív URI nem oldható fel.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Leképezi az URI-t egy objektumra, amely a tényleges erőforrást tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatér:**
java.io.InputStream - InputStream objektum vagy null, ha az erőforrás nem streamelhető.