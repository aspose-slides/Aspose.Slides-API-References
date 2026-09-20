---
title: IPresentationInfo class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipresentationinfo/
---
## IPresentationInfo klass

Information om presentationsfilen

IPresentationInfo-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`is_encrypted`](/slides/python-net/sv/aspose.slides/ipresentationinfo/is_encrypted/) | Returnerar True om den binda presentationen är krypterad, annars False.<br/>            Skrivskyddad **bool**. |
| [`is_password_protected`](/slides/python-net/sv/aspose.slides/ipresentationinfo/is_password_protected/) | Returnerar ett värde som indikerar om den binda presentationen är skyddad med ett lösenord för att öppna. |
| [`is_write_protected`](/slides/python-net/sv/aspose.slides/ipresentationinfo/is_write_protected/) | Returnerar ett värde som indikerar om den binda presentationen är skrivskyddad. |
| [`load_format`](/slides/python-net/sv/aspose.slides/ipresentationinfo/load_format/) | Returnerar formatet för den binda presentationen.<br/>            Skrivskyddad [`LoadFormat`](/slides/python-net/sv/aspose.slides/loadformat). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Skriver den binda presentationen till en ström. |
| [`write_binded_presentation(self, file)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Skriver den binda presentationen till en fil. |
| [`check_password(self, password)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/check_password/#str) | Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppningslösenord. |
| [`check_write_protection(self, password)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/check_write_protection/#str) | Kontrollerar om ett lösenord för ändring är korrekt för en skrivskyddad presentation. |
| [`read_document_properties(self)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/read_document_properties/#) | Returnerar dokumentegenskaper för den binda presentationen. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/sv/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Uppdaterar egenskaper för den binda presentationen. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)