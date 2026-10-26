---
title: HtmlExternalResolver
second_title: Aspose.Slides Java API-referenciája
description: Visszahívási objektum, amelyet a HTML importálási rutin használ a hivatkozott objektumok, például képek lekérésére.
type: docs
url: /hu/com.aspose.slides/htmlexternalresolver/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Callback-objektum, amelyet a HTML importálási rutin használ a hivatkozott objektumok, például képek megszerzésére.

--------------------

A resolver használata sebezhetőséget okozhat, ha a kliens által biztosított HTML fájl a szerver szoftvert helyi vagy hálózati fájlok lekérésére készteti. Óvatosan használja. Javasolt, hogy egyáltalán ne adja meg a HtmlExternalResolver-t (csak a beágyazott objektumok lesznek beolvasva), vagy hozzon létre egy alosztályt, amely ellenőrzi, hogy a megadott uri érvényes-e.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Megoldja a teljes URI-t az alap és a relatív URI-kból. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Egy URI-t leképez egy objektumra, amely a tényleges erőforrást tartalmazza. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Megoldja a teljes URI-t az alap és a relatív URI-kból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| baseUri | java.lang.String | Hivatkozó objektumok alap URI-ja |
| relativeUri | java.lang.String | A hivatkozott objektum relatív URI-ja. |

**Visszatérési érték:**
java.lang.String - Abszolút URI vagy null, ha a relatív URI nem oldható fel.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Egy URI-t leképez egy objektumra, amely a tényleges erőforrást tartalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatérési érték:**
java.io.InputStream - InputStream objektum vagy null, ha az erőforrás nem áramoltató.