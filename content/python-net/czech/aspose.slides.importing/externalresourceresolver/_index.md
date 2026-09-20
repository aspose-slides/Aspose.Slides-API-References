---
title: ExternalResourceResolver class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver třída

Třída zpětného volání používaná k řešení externích zdrojů během importu dokumentů Html, Svg.  
Použití tohoto resolveru může vytvořit zranitelnost, když klient poskytne soubor HTML nebo SVG, který přiměje serverový software získat lokální nebo síťový soubor.  
Používejte s opatrností. Doporučuje se vůbec nespecifikovat ExternalResourceResolver (budou čteny jen vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je uvedená URI platná.

Typ ExternalResourceResolver vystavuje následující členy:

## Constructors

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Methods

| Metoda | Popis |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/cs/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Získá absolutní URI z základního a relativního URI. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/cs/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mapuje URI na objekt obsahující skutečný zdroj. |

### Viz také
* modul [`aspose.slides.importing`](/slides/python-net/cs/aspose.slides.importing)
* knihovna [`Aspose.Slides`](/slides/python-net)