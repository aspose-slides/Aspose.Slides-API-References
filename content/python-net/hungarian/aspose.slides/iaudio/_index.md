---
title: IAudio class
second_title: Aspose.Slides Pythonhoz .NET API referencián keresztül
description: 
type: docs
url: /hu/aspose.slides/iaudio/
---
## IAudio osztály

Beágyazott hangfájlt képvisel.

Az IAudio típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`content_type`](/slides/python-net/hu/aspose.slides/iaudio/content_type/) | Visszaadja egy hang MIME típusát, [`IAudio.binary_data`](/slides/python-net/hu/aspose.slides/iaudio/binary_data) formátumban kódolva.<br/>            Csak olvasható **str**. |
| [`binary_data`](/slides/python-net/hu/aspose.slides/iaudio/binary_data/) | Visszaadja a hang adatainak másolatát. Nagy mennyiségű adat esetén fontolja meg a [`IAudio.get_stream`](/slides/python-net/hu/aspose.slides/iaudio/get_stream) metódus használatát, hogy elkerülje a hang adatának szükségtelen betöltését a memóriába, vagy akár OutOfMemoryException kivételt.<br/>            Csak olvasható **int**[]. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/hu/aspose.slides/iaudio/get_stream/#) | Visszaad egy Stream objektumot olvasáshoz.<br/>            Használja a 'using' kulcsszót, vagy zárja be a streamet a használat után. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)