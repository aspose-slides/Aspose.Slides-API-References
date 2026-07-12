---
title: HtmlExternalResolver
second_title: Aspose.Slides Androidhoz a Java API hivatkozás segítségével
description: A HTML importálási rutin által használt visszahívási objektum, amely a hivatkozott objektumokat, például képeket szerzi be.
type: docs
url: /hu/com.aspose.slides/htmlexternalresolver/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

A HTML importálási rutin által használt visszahívási objektum, amely a hivatkozott objektumokat, például képeket szerzi be.

--------------------

Ennek a feloldónak a használata sebezhetőséget okozhat, ha a kliens által biztosított HTML fájl a szerver szoftvert helyi vagy hálózati fájl lekérésére készteti. Óvatosan használja. Ajánlott, hogy ne adja meg a HtmlExternalResolver-t egyáltalán (csak a beágyazott objektumok lesznek beolvasva), vagy hozzon létre egy alosztályt, amely ellenőrzi, hogy a megadott uri érvényes-e.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Az abszolút URI-t a bázis- és relatív URI-kból állapítja meg. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Egy URI-t egy tényleges erőforrást tartalmazó objektumhoz rendel. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Az abszolút URI-t a bázis- és relatív URI-kból állapítja meg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | java.lang.String | A hivatkozó objektumok alap-URI-ja |
| relativeUri | java.lang.String | A hivatkozott objektum relatív URI-ja. |

**Visszatérési érték:**
java.lang.String - Absólút URI vagy null, ha a relatív URI nem oldható fel.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Egy URI-t egy tényleges erőforrást tartalmazó objektumhoz rendel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | java.lang.String | Az objektum abszolút URI-ja. |

**Visszatérési érték:**
java.io.InputStream - Egy InputStream objektum vagy null, ha az erőforrás nem olvasható streamként.