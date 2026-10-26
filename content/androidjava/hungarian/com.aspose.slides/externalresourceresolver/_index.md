---
title: ExternalResourceResolver
second_title: Aspose.Slides Androidhoz a Java API hivatkozás szerint
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

A HTML vagy SVG dokumentumok importálása során külső erőforrások feloldására használt Callback osztály.

--------------------

Ennek a feloldónak a használata sebezhetőséget eredményezhet, ha a kliens által biztosított HTML vagy SVG fájl a szerver szoftvert helyi vagy hálózati fájl elérésére készteti. Óvatosan használja. Javasolt, hogy ne adja meg az ExternalResourceResolver-t egyáltalán (csak a beágyazott objektumok lesznek beolvasva), vagy hozzon létre egy olyan alosztályt, amely ellenőrzi, hogy a megadott uri érvényes-e.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metódusok

| Metódus | Leírás |
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


A bázis- és relatív URI-kból állítja elő az abszolút URI-t.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | java.lang.String | A hivatkozó objektumok bázis URI-ja |
| relativeUri | java.lang.String | A hivatkozott objektum relatív URI-ja. |

**Visszatérési érték:**
java.lang.String - Abszolút URI vagy null, ha a relatív URI nem oldható fel.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


URI-t képez le egy olyan objektumra, amely a tényleges erőforrást tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatérési érték:**
java.io.InputStream - InputStream objektum vagy null, ha az erőforrás nem streamelhető.