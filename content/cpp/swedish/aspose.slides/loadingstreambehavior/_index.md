---
title: LoadingStreamBehavior
second_title: Aspose.Slides för C++ API-referens
description: "System::IO::Stream som skickas till en metod betraktas som ett Binary Large Object (BLOB) (se IBlobManagementOptions beskrivning). Värdena i den här uppräkningen identifierar hur System::IO::Stream ska behandlas när den skickas till metoden. Beroende på kraven kan olika beslut fattas för att ge det mest effektiva beteendet."
type: docs
weight: 6735
url: /sv/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior-enum


Den [System::IO::Stream](../../system.io/stream/) som skickas till en metod betraktas som ett Binary Large Object (BLOB) (se [IBlobManagementOptions](../iblobmanagementoptions/) beskrivning). Värdena i den här uppräkningen identifierar hur [System::IO::Stream](../../system.io/stream/) ska behandlas när den skickas till metoden. Beroende på kraven kan olika beslut fattas för att ge det mest effektiva beteendet.

```cpp
enum class LoadingStreamBehavior
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Strömmen kommer att läsas till slutet och sedan släppas - det vill säga att det garanteras att denna ström inte kommer att användas av [IPresentation](../ipresentation/)-instansen i framtiden. Den kan stängas av klientkoden eller användas på något annat sätt. |
| KeepLocked | 1 | Strömmen kommer att låsas inuti [IPresentation](../ipresentation/)-objektet, det vill säga att äganderätten till strömmen kommer att överföras. [IPresentation](../ipresentation/)-objektet kommer att ansvara för att korrekt avyttra strömmen när detta objekt själv avyttras. Detta beteende är extremt användbart när du behöver serialisera en stor BLOB-fil (t.ex. en stor video eller ljud - se [IBlobManagementOptions](../iblobmanagementoptions/) beskrivning) och vill förhindra att filen läses in i minnet eller andra prestandaproblem. Du kan helt enkelt öppna [System::IO::FileStream](../../system.io/filestream/) för den här filen och skicka den till en metod och välja [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Se även

* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)