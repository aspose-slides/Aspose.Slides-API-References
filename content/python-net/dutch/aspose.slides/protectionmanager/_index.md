---
title: ProtectionManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/protectionmanager/
---
## ProtectionManager klasse

Presentation wachtwoordbeveiligingsbeheer.

Het ProtectionManager-type biedt de volgende leden aan:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/nl/aspose.slides/protectionmanager/encrypt_document_properties/) | Deze eigenschap is van betekenis als de presentatie met een wachtwoord is beveiligd.<br/>            Als true dan zijn documenteigenschappen versleuteld in het presentatiebestand.<br/>            Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is.<br/>            Lezen/schrijven **bool**. |
| [`is_encrypted`](/slides/python-net/nl/aspose.slides/protectionmanager/is_encrypted/) | Geeft een waarde die aangeeft of deze instantie versleuteld is.<br/>            Alleen-lezen **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/nl/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Deze eigenschap is van betekenis als het presentatiebestand met een wachtwoord is beveiligd en de document<br/>            eigenschappen van dit bestand openbaar zijn.<br/>            Een waarde van true betekent dat alleen documenteigenschappen worden geladen uit een versleuteld<br/>            presentatiebestand zonder gebruik van een wachtwoord.<br/>            Een waarde van false betekent dat de volledige versleutelde presentatie wordt geladen met gebruik van het juiste<br/>            wachtwoord, niet alleen documenteigenschappen worden geladen.<br/>            Als de presentatie niet versleuteld is, dan is de eigenschapswaarde altijd false.<br/>            Als documenteigenschappen van een versleuteld bestand niet openbaar zijn, dan is de eigenschapswaarde altijd false.<br/>            Als Presentation.EncryptDocumentProperties true is, dan is de IsOnlyDocumentPropertiesLoaded<br/>            eigenschapswaarde altijd false.<br/>            Alleen-lezen **bool**. |
| [`is_write_protected`](/slides/python-net/nl/aspose.slides/protectionmanager/is_write_protected/) | Geeft een waarde die aangeeft of deze presentatie schrijfbeveiligd is.<br/>            Alleen-lezen **bool**. |
| [`encryption_password`](/slides/python-net/nl/aspose.slides/protectionmanager/encryption_password/) | Geeft het wachtwoord dat wordt gebruikt voor presentatieversleuteling.<br/>            Alleen-lezen **str**. |
| [`read_only_recommended`](/slides/python-net/nl/aspose.slides/protectionmanager/read_only_recommended/) | Geeft of stelt de alleen-lezen aanbeveling in.<br/>            Lezen/schrijven **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/nl/aspose.slides/protectionmanager/encrypt/#str) | Versleutelt Presentation met het opgegeven wachtwoord. |
| [`remove_encryption(self)`](/slides/python-net/nl/aspose.slides/protectionmanager/remove_encryption/#) | Verwijdert de versleuteling. |
| [`set_write_protection(self, password)`](/slides/python-net/nl/aspose.slides/protectionmanager/set_write_protection/#str) | Stelt schrijfbeveiliging in voor deze presentatie met het opgegeven wachtwoord. |
| [`remove_write_protection(self)`](/slides/python-net/nl/aspose.slides/protectionmanager/remove_write_protection/#) | Verwijdert de schrijfbeveiliging voor deze presentatie. |
| [`check_write_protection(self, password)`](/slides/python-net/nl/aspose.slides/protectionmanager/check_write_protection/#str) | Bepaalt of een presentatie wachtwoordbeveiligd is om te wijzigen. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)