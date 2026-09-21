---
title: IPresentationInfo class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipresentationinfo/
---
## IPresentationInfo klasse

Informatie over presentatiebestand

Het type IPresentationInfo geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`is_encrypted`](/slides/python-net/nl/aspose.slides/ipresentationinfo/is_encrypted/) | Geeft True terug als de gekoppelde presentatie versleuteld is, anders False.<br/>            Alleen-lezen **bool**. |
| [`is_password_protected`](/slides/python-net/nl/aspose.slides/ipresentationinfo/is_password_protected/) | Geeft een waarde terug die aangeeft of de gekoppelde presentatie beschermd is met een wachtwoord om te openen. |
| [`is_write_protected`](/slides/python-net/nl/aspose.slides/ipresentationinfo/is_write_protected/) | Geeft een waarde terug die aangeeft of de gekoppelde presentatie schrijfbeveiligd is. |
| [`load_format`](/slides/python-net/nl/aspose.slides/ipresentationinfo/load_format/) | Geeft het formaat van de gekoppelde presentatie terug.<br/>            Alleen-lezen [`LoadFormat`](/slides/python-net/nl/aspose.slides/loadformat). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Schrijft de gekoppelde presentatie naar een stream. |
| [`write_binded_presentation(self, file)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Schrijft de gekoppelde presentatie naar een bestand. |
| [`check_password(self, password)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/check_password/#str) | Controleert of een wachtwoord correct is voor een presentatie beschermd met een open wachtwoord. |
| [`check_write_protection(self, password)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/check_write_protection/#str) | Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie. |
| [`read_document_properties(self)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/read_document_properties/#) | Geeft de documenteigenschappen van de gekoppelde presentatie terug. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/nl/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Werk de eigenschappen van de gekoppelde presentatie bij. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)