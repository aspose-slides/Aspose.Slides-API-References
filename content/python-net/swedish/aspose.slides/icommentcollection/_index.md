---
title: ICommentCollection class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icommentcollection/
---
## ICommentCollection klass

Representerar en samling kommentarer från en författare.

ICommentCollection-typen exponerar följande medlemmar:

Hämtar elementet på det angivna indexet.  
Skrivskyddad [`IComment`](/slides/python-net/sv/aspose.slides/icomment).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides/icommentcollection/__getitem__/) |  |

## Metoder

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/sv/aspose.slides/icommentcollection/to_array/#) | Skapar och returnerar en array med alla kommentarer. |
| [`to_array(self, start_index, count)`](/slides/python-net/sv/aspose.slides/icommentcollection/to_array/#int-int) | Skapar och returnerar en array med alla kommentarer från det angivna intervallet. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/sv/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Lägger till en ny kommentar i slutet av en samling. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/sv/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Lägger till en ny modern kommentar i slutet av en samling. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/sv/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Infogar en ny kommentar i en samling på det angivna indexet. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/sv/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Infogar en ny modern kommentar i en samling på det angivna indexet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides/icommentcollection/remove_at/#int) | Tar bort elementet på det angivna indexet i en samling. |
| [`remove(self, comment)`](/slides/python-net/sv/aspose.slides/icommentcollection/remove/#icomment) | Tar bort den första förekomsten av den angivna kommentaren i en samling. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides/icommentcollection/clear/#) | Tar bort alla kommentarer från en samling. |


### Se också
* klass [`IComment`](/slides/python-net/sv/aspose.slides/icomment)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)