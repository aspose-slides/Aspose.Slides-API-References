---
title: ProtectionManager class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/protectionmanager/
---
## ProtectionManager klass

Presentation lösenordsskyddshantering.

ProtectionManager-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/sv/aspose.slides/protectionmanager/encrypt_document_properties/) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad.<br/>            Om true är dokumentegenskaperna krypterade i presentationsfilen.<br/>            Om false är dokumentegenskaperna offentliga medan presentationen är krypterad.<br/>            Läs/skriv **bool**. |
| [`is_encrypted`](/slides/python-net/sv/aspose.slides/protectionmanager/is_encrypted/) | Hämtar ett värde som indikerar om detta objekt är krypterat.<br/>            Endast läs **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/sv/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokument<br/>            egenskaper för denna fil är offentliga.<br/>            Värdet true betyder att endast dokumentegenskaper laddas från en krypterad<br/>            presentationsfil utan att använda lösenord.<br/>            Värdet false betyder att hela den krypterade presentationen laddas med rätt<br/>            lösenord, inte bara dokumentegenskaper laddas.<br/>            Om presentationen inte är krypterad är egenskapsvärdet alltid false.<br/>            Om dokumentegenskaper för en krypterad fil inte är offentliga är egenskapsvärdet alltid false.<br/>            Om Presentation.EncryptDocumentProperties är true så är IsOnlyDocumentPropertiesLoaded<br/>            egenskapsvärdet alltid false.<br/>            Endast läs **bool**. |
| [`is_write_protected`](/slides/python-net/sv/aspose.slides/protectionmanager/is_write_protected/) | Hämtar ett värde som indikerar om den här presentationen är skrivskyddad.<br/>            Endast läs **bool**. |
| [`encryption_password`](/slides/python-net/sv/aspose.slides/protectionmanager/encryption_password/) | Hämtar lösenordet som används för presentationens kryptering.<br/>            Endast läs **str**. |
| [`read_only_recommended`](/slides/python-net/sv/aspose.slides/protectionmanager/read_only_recommended/) | Hämtar eller anger rekommendation för skrivskydd.<br/>            Läs/skriv **bool**. |

## Metoder

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/sv/aspose.slides/protectionmanager/encrypt/#str) | Krypterar presentationen med angivet lösenord. |
| [`remove_encryption(self)`](/slides/python-net/sv/aspose.slides/protectionmanager/remove_encryption/#) | Tar bort krypteringen. |
| [`set_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/protectionmanager/set_write_protection/#str) | Ställer in skrivskydd för den här presentationen med angivet lösenord. |
| [`remove_write_protection(self)`](/slides/python-net/sv/aspose.slides/protectionmanager/remove_write_protection/#) | Tar bort skrivskydd för den här presentationen. |
| [`check_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/protectionmanager/check_write_protection/#str) | Avgör om en presentation är lösenordsskyddad för att modifieras. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)