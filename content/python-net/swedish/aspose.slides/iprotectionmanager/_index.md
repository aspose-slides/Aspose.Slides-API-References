---
title: IProtectionManager class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iprotectionmanager/
---
## IProtectionManager klass

Presentation password protection management.

The IProtectionManager type exposes the following members:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/sv/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad.<br/>If true then document properties is encrypted in presentation file.<br/>If false then document properties is public while presentation is encrypted.<br/>Läs/skriv **bool**. |
| [`is_encrypted`](/slides/python-net/sv/aspose.slides/iprotectionmanager/is_encrypted/) | Hämtar ett värde som indikerar om den här instansen är krypterad.<br/>Endast läsning **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/sv/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna i den här filen är offentliga.<br/>Värdet true betyder att endast dokumentegenskaper laddas från en krypterad presentationsfil utan att använda lösenord.<br/>Värdet false betyder att hela den krypterade presentationen laddas med rätt lösenord, inte bara dokumentegenskaper laddas.<br/>Om presentationen inte är krypterad är egenskapsvärdet alltid false.<br/>Om dokumentegenskaperna i en krypterad fil inte är offentliga är egenskapsvärdet alltid false.<br/>Om PresentationEx.EncryptDocumentProperties är true är värdet för IsOnlyDocumentPropertiesLoaded alltid false.<br/>Endast läsning **bool**. |
| [`is_write_protected`](/slides/python-net/sv/aspose.slides/iprotectionmanager/is_write_protected/) | Hämtar ett värde som indikerar om denna presentation är skrivskyddad.<br/>Endast läsning **bool**. |
| [`encryption_password`](/slides/python-net/sv/aspose.slides/iprotectionmanager/encryption_password/) | Returnerar krypteringslösenordet.<br/>Endast läsning **str**. |
| [`read_only_recommended`](/slides/python-net/sv/aspose.slides/iprotectionmanager/read_only_recommended/) | Hämtar eller anger rekommendation för skrivskydd.<br/>Läs/skriv **bool**. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/sv/aspose.slides/iprotectionmanager/encrypt/#str) | Krypterar presentationen med angivet lösenord. |
| [`remove_encryption(self)`](/slides/python-net/sv/aspose.slides/iprotectionmanager/remove_encryption/#) | Tar bort krypteringen. |
| [`set_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/iprotectionmanager/set_write_protection/#str) | Sätter skrivskydd för denna presentation med angivet lösenord. |
| [`remove_write_protection(self)`](/slides/python-net/sv/aspose.slides/iprotectionmanager/remove_write_protection/#) | Tar bort skrivskyddet för denna presentation. |
| [`check_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/iprotectionmanager/check_write_protection/#str) | Bestämmer om en presentation är lösenordsskyddad för att modifieras. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)