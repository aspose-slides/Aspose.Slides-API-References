---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/loadingstreambehavior/
---
## Wyliczenie LoadingStreamBehavior

**io.RawIOBase** przekazywany do metody jest traktowany jako duży obiekt binarny (BLOB) (zobacz opis [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)). Wartości tego wyliczenia określają, jak **io.RawIOBase** powinien być obsługiwany, gdy zostanie przekazany do metody. W zależności od wymagań można podjąć różne decyzje, aby zapewnić najbardziej efektywne zachowanie.

Typ LoadingStreamBehavior udostępnia następujące elementy:

## Pola

| Field | Description |
| :- | :- |
| READ_STREAM_AND_RELEASE | Strumień zostanie odczytany do końca i następnie zwolniony – tzn. zapewnione będzie, że ten strumień <br/>            nie będzie używany przez instancję [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) w przyszłości. Może być zamknięty przez kod klienta <br/>            lub użyty w inny sposób. |
| KEEP_LOCKED | Strumień zostanie zablokowany wewnątrz obiektu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation), tzn. zostanie przeniesiona własność <br/>            strumienia. Obiekt [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) będzie odpowiedzialny za prawidłowe zwolnienie strumienia, gdy ten obiekt zostanie sam zwolniony. <br/>            To zachowanie jest niezwykle przydatne, gdy trzeba serializować duży plik BLOB (np. duży <br/>            plik wideo lub audio – zobacz opis [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)) i chce się zapobiec wczytywaniu <br/>            tego pliku do pamięci lub innym problemom wydajnościowym. Można po prostu otworzyć **System.IO.FileStream** <br/>            dla tego pliku i przekazać go do metody, wybierając [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/pl/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Zobacz także
* klasa [`IBlobManagementOptions`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions)
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)