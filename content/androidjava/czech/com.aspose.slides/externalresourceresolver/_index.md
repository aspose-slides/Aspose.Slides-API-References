---
title: ExternalResourceResolver
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Třída Callback používaná k řešení externích zdrojů během importu dokumentů Html a Svg.
type: docs
url: /cs/com.aspose.slides/externalresourceresolver/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Třída Callback používaná k řešení externích zdrojů během importu dokumentů Html a Svg.

--------------------

Použití tohoto řešiče by mohlo vytvořit zranitelnost, když soubor HTML nebo SVG poskytnutý klientem přiměje serverový software získat lokální nebo síťový soubor. Používejte opatrně. Doporučuje se vůbec nespecifikovat ExternalResourceResolver (budou načteny jen vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je určený uri platný.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Řeší absolutní URI ze základního a relativního URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapuje URI na objekt obsahující skutečný zdroj. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Řeší absolutní URI ze základního a relativního URI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | java.lang.String | Základní URI propojujících objektů |
| relativeUri | java.lang.String | Relativní URI k propojenému objektu. |

**Vrací:**
java.lang.String - Absolutní URI nebo null, pokud relativní URI nelze vyřešit.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapuje URI na objekt obsahující skutečný zdroj.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolutní URI k objektu. |

**Vrací:**
java.io.InputStream - Objekt InputStream nebo null, pokud zdroj nelze streamovat.