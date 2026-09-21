---
title: IProtectionManager class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iprotectionmanager/
---
## IProtectionManager klasse

Beheer van presentatiewachtwoordbeveiliging.

Het IProtectionManager-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/nl/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Deze eigenschap is zinvol als de presentatie met wachtwoord beveiligd is.<br/>            Als true dan zijn documenteigenschappen versleuteld in het presentatie-bestand.<br/>            Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is.<br/>            Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/nl/aspose.slides/iprotectionmanager/is_encrypted/) | Haalt een waarde op die aangeeft of deze instantie versleuteld is.<br/>            Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/nl/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Deze eigenschap is zinvol als het presentatiedbestand met wachtwoord beveiligd is en de documenteigenschappen van dit bestand openbaar zijn.<br/>            De waarde true betekent dat alleen documenteigenschappen worden geladen uit een versleuteld presentatiedbestand zonder gebruik van een wachtwoord.<br/>            De waarde false betekent dat de volledige versleutelde presentatie wordt geladen met gebruik van het juiste wachtwoord, niet alleen documenteigenschappen worden geladen.<br/>            Als de presentatie niet versleuteld is, is de eigenschapswaarde altijd false.<br/>            Als documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschapswaarde altijd false.<br/>            Als PresentationEx.EncryptDocumentProperties true is, dan is de eigenschap IsOnlyDocumentPropertiesLoaded altijd false.<br/>            Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/nl/aspose.slides/iprotectionmanager/is_write_protected/) | Haalt een waarde op die aangeeft of deze presentatie schrijfbeschermd is.<br/>            Read-only **bool**. |
| [`encryption_password`](/slides/python-net/nl/aspose.slides/iprotectionmanager/encryption_password/) | Geeft het encryptiewachtwoord terug.<br/>            Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/nl/aspose.slides/iprotectionmanager/read_only_recommended/) | Haalt of stelt de alleen-lezen aanbeveling in.<br/>            Read/write **bool**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/nl/aspose.slides/iprotectionmanager/encrypt/#str) | Versleutelt de presentatie met het opgegeven wachtwoord. |
| [`remove_encryption(self)`](/slides/python-net/nl/aspose.slides/iprotectionmanager/remove_encryption/#) | Verwijdert de encryptie. |
| [`set_write_protection(self, password)`](/slides/python-net/nl/aspose.slides/iprotectionmanager/set_write_protection/#str) | Stelt schrijfbescherming in voor deze presentatie met het opgegeven wachtwoord. |
| [`remove_write_protection(self)`](/slides/python-net/nl/aspose.slides/iprotectionmanager/remove_write_protection/#) | Verwijdert schrijfbescherming voor deze presentatie. |
| [`check_write_protection(self, password)`](/slides/python-net/nl/aspose.slides/iprotectionmanager/check_write_protection/#str) | Bepaalt of een presentatie wachtwoordbeveiligd is voor bewerking. |


### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)