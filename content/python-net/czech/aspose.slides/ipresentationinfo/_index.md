---
title: IPresentationInfo class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ipresentationinfo/
---
## IPresentationInfo třída

Informace o souboru prezentace

Typ IPresentationInfo vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_encrypted`](/slides/python-net/cs/aspose.slides/ipresentationinfo/is_encrypted/) | Vrací True, pokud je svázaná prezentace zašifrována, jinak False.<br/>            Pouze pro čtení **bool**. |
| [`is_password_protected`](/slides/python-net/cs/aspose.slides/ipresentationinfo/is_password_protected/) | Vrací hodnotu, která udává, zda je svázaná prezentace chráněna heslem pro otevření. |
| [`is_write_protected`](/slides/python-net/cs/aspose.slides/ipresentationinfo/is_write_protected/) | Vrací hodnotu, která udává, zda je svázaná prezentace chráněna proti zápisu. |
| [`load_format`](/slides/python-net/cs/aspose.slides/ipresentationinfo/load_format/) | Vrací formát svázané prezentace.<br/>            Pouze pro čtení [`LoadFormat`](/slides/python-net/cs/aspose.slides/loadformat). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Zapíše svázanou prezentaci do proudu. |
| [`write_binded_presentation(self, file)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Zapíše svázanou prezentaci do souboru. |
| [`check_password(self, password)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/check_password/#str) | Kontroluje, zda je heslo správné pro prezentaci chráněnou heslem pro otevření. |
| [`check_write_protection(self, password)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/check_write_protection/#str) | Kontroluje, zda je heslo pro úpravu správné pro prezentaci chráněnou proti zápisu. |
| [`read_document_properties(self)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/read_document_properties/#) | Vrací vlastnosti dokumentu svázané prezentace. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/cs/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Aktualizuje vlastnosti svázané prezentace. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)