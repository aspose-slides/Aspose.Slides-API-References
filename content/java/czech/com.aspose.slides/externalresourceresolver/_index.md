---
title: ExternalResourceResolver
second_title: Aspose.Slides pro referenci API Javy
description: Třída Callback používaná k řešení externích zdrojů během importu dokumentů Html a Svg.
type: docs
url: /cs/com.aspose.slides/externalresourceresolver/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Třída Callback používaná k řešení externích zdrojů během importu dokumentů Html, Svg.

--------------------

Použití tohoto resolveru může vytvořit zranitelnost, když klient poskytne soubor HTML nebo SVG, který způsobí, že serverový software získá lokální nebo síťový soubor. Používejte opatrně. Doporučuje se vůbec nespecifikovat ExternalResourceResolver (budou čteny pouze vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je zadané uri platné.
## Konstruktory

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metody

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Rozpozná absolutní URI ze základního a relativního URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na objekt obsahující skutečný zdroj. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Rozpozná absolutní URI ze základního a relativního URI.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | Základní URI pro propojující objekty |
| relativeUri | java.lang.String | Relativní URI k propojenému objektu. |

**Návratová hodnota:**
java.lang.String - Absolutní URI nebo null, pokud nelze rozpoznat relativní URI.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapuje URI na objekt obsahující skutečný zdroj.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | |
| absoluteUri | java.lang.String | Absolutní URI k objektu. |

**Návratová hodnota:**
java.io.InputStream - Objekt InputStream nebo null, pokud zdroj nelze streamovat.