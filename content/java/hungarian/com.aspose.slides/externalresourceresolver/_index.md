---
title: ExternalResourceResolver
second_title: Aspose.Slides Java API-referencia
description: Visszahívási osztály, amely a HTML és SVG dokumentumok importálása során külső erőforrások feloldására szolgál.
type: docs
url: /hu/com.aspose.slides/externalresourceresolver/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

A visszahívási osztály, amely külső erőforrások feloldására szolgál HTML és SVG dokumentumok importálása során.

--------------------

Ennek a feloldónak a használata sebezhetőséget okozhat, ha a kliens által biztosított HTML vagy SVG fájl a szerver szoftvert helyi vagy hálózati fájlok megszerzésére készteti. Óvatosan használja. Ajánlott, hogy egyáltalán ne adjon meg ExternalResourceResolver-t (csak a beágyazott objektumok lesznek olvasva), vagy hozzon létre egy almintát, amely ellenőrzi, hogy a megadott URI érvényes-e.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Methods

| Módszer | Leírás |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


A base és relatív URI-kból állít elő abszolút URI-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | java.lang.String | A hivatkozó objektumok alap URI-ja |
| relativeUri | java.lang.String | A kapcsolt objektum relatív URI-ja. |

**Visszatérési érték:**
java.lang.String – Abszolút URI, vagy null, ha a relatív URI nem oldható fel.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


URI-t egy a tényleges erőforrást tartalmazó objektumhoz kapcsol.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatérési érték:**
java.io.InputStream – InputStream objektum, vagy null, ha az erőforrás nem olvasható streamként.