---
title: HtmlExternalResolver
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Objekt zpětného volání používaný rutinou importu HTML k získání odkazovaných objektů, například obrázků.
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

Objekt zpětného volání používaný rutinou importu HTML k získání odkazovaných objektů, například obrázků.

--------------------

Použití tohoto řešiče může vytvořit zranitelnost, když klient poskytne HTML soubor, který přiměje serverový software získat lokální nebo síťový soubor. Používejte s opatrností. Doporučuje se vůbec neuvádět HtmlExternalResolver (budou načteny jen vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je zadané URI platné.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Získá absolutní URI z základního a relativního URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Přiřadí URI k objektu obsahujícímu skutečný zdroj. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Získá absolutní URI z základního a relativního URI.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseUri | java.lang.String | Základní URI odkazujících objektů |
| relativeUri | java.lang.String | Relativní URI k odkazovanému objektu. |

**Vrací:**
java.lang.String - Absolutní URI nebo null, pokud nelze relativní URI vyřešit.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Přiřadí URI k objektu obsahujícímu skutečný zdroj.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolutní URI k objektu. |

**Vrací:**
java.io.InputStream - Objekt InputStream nebo null, pokud není možné zdroj streamovat.