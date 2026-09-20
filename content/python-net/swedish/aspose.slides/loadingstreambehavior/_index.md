---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumeration

Den **io.RawIOBase** som skickas till en metod betraktas som ett Binary Large Object (BLOB) (se [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions) description). Värdena i denna enumeration identifierar hur **io.RawIOBase** ska behandlas när den skickas till metoden. Beroende på kraven kan olika beslut fattas för att ge det mest effektiva beteendet.

Typen LoadingStreamBehavior exponerar följande medlemmar:

## Fält

| Fält | Beskrivning |
| :- | :- |
| READ_STREAM_AND_RELEASE | Strömmen kommer att läsas till slutet och sedan släppas – dvs. det kommer att garanteras att denna ström <br/>            inte kommer att användas av [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instansen i framtiden. Den kan stängas av klient-<br/>            koden eller användas på något annat sätt. |
| KEEP_LOCKED | Strömmen kommer att låsas inuti objektet [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation), dvs. äganderätten till <br/>            strömmen kommer att överföras. Objektet [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation) kommer att ansvara för att <br/>            korrekt avyttra strömmen när detta objekt själv avyttras. <br/>            Detta beteende är extremt användbart när du behöver serialisera en stor BLOB-fil (t.ex. en stor <br/>            video- eller ljudfil – se [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions) description) och vill förhindra att <br/>            filen laddas in i minnet eller andra prestandaproblem. Du kan helt enkelt öppna **System.IO.FileStream** <br/>            för den här filen och skicka den till en metod, och välja [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/sv/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Se även
* klass [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)