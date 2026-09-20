---
title: HtmlExternalResolver class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver třída

Objekt zpětného volání používaný rutinnou importu HTML k získání referencovaných objektů, jako jsou obrázky. Použití tohoto resolveru může vytvořit zranitelnost, když klientem poskytnutý HTML soubor přiměje serverový software získat lokální nebo síťový soubor. Používejte s opatrností. Doporučuje se vůbec neuvádět HtmlExternalResolver (budou čteny jen vložené objekty) nebo vytvořit podtřídu, která kontroluje, zda je uvedená URI platná.

Typ HtmlExternalResolver vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/cs/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Vyřeší absolutní URI ze základní a relativní URI. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/cs/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mapuje URI na objekt obsahující skutečný zdroj. |

### Viz také
* modul [`aspose.slides.importing`](/slides/python-net/cs/aspose.slides.importing)
* knihovna [`Aspose.Slides`](/slides/python-net)