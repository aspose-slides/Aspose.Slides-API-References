---
title: HtmlExternalResolver
second_title: Aspose.Slides pro Java – reference API
description: Objekt zpětného volání používaný rutinou importu HTML k získání referencovaných objektů, například obrázků.
type: docs
url: /cs/com.aspose.slides/htmlexternalresolver/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Objekt zpětného volání používaný rutinou importu HTML k získání referencovaných objektů, například obrázků.

--------------------

Použití tohoto řešiče může vytvořit zranitelnost, když klientský HTML soubor způsobí, že serverový software získá lokální nebo síťový soubor. Používejte s opatrností. Doporučuje se vůbec nespecifikovat HtmlExternalResolver (budou čteny pouze vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je zadané uri platné.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Vyřeší absolutní URI z základního a relativního URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na objekt obsahující skutečný prostředek. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Vyřeší absolutní URI z základního a relativního URI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | java.lang.String | Základní URI odkazujících objektů |
| relativeUri | java.lang.String | Relativní URI na odkazovaný objekt. |

**Návratová hodnota:**
java.lang.String - Absolutní URI nebo null, pokud nelze relativní URI vyřešit.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapuje URI na objekt obsahující skutečný prostředek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolutní URI na objekt. |

**Návratová hodnota:**
java.io.InputStream - Objekt InputStream nebo null, pokud nelze prostředek streamovat.