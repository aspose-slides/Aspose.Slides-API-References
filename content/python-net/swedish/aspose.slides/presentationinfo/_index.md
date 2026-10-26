---
title: PresentationInfo class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentationinfo/
---
## PresentationInfo klass

Information om presentationsfil

Typen PresentationInfo exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_encrypted`](/slides/python-net/sv/aspose.slides/presentationinfo/is_encrypted/) | Returnerar True om den bindade presentationen är krypterad, annars False.<br/>            Endast läsning **bool**. |
| [`is_password_protected`](/slides/python-net/sv/aspose.slides/presentationinfo/is_password_protected/) | Returnerar ett värde som indikerar om den bindade presentationen är skyddad med ett lösenord för öppning. |
| [`is_write_protected`](/slides/python-net/sv/aspose.slides/presentationinfo/is_write_protected/) | Returnerar ett värde som indikerar om den bindade presentationen är skrivskyddad. |
| [`load_format`](/slides/python-net/sv/aspose.slides/presentationinfo/load_format/) | Returnerar formatet för den bindade presentationen.<br/>            Endast läsning [`LoadFormat`](/slides/python-net/sv/aspose.slides/loadformat). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/sv/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Skriver den bindade presentationen till en ström. |
| [`write_binded_presentation(self, file)`](/slides/python-net/sv/aspose.slides/presentationinfo/write_binded_presentation/#str) | Skriver den bindade presentationen till en fil. |
| [`check_password(self, password)`](/slides/python-net/sv/aspose.slides/presentationinfo/check_password/#str) | Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppningslösenord. |
| [`check_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/presentationinfo/check_write_protection/#str) | Kontrollerar om ett lösenord för modifiering är korrekt för en skrivskyddad presentation. |
| [`read_document_properties(self)`](/slides/python-net/sv/aspose.slides/presentationinfo/read_document_properties/#) | Returnerar dokumentegenskaper för den bindade presentationen. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/sv/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Uppdaterar egenskaper för den bindade presentationen. |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)