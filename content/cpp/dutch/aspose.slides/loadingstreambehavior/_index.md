---
title: LoadingStreamBehavior
second_title: Aspose.Slides voor C++ API-referentie
description: "De System::IO::Stream die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB) (zie IBlobManagementOptions beschrijving). De waarden van deze enumeratie geven aan hoe de System::IO::Stream moet worden behandeld wanneer deze aan de methode wordt doorgegeven. Afhankelijk van de eisen kunnen verschillende beslissingen worden genomen om het meest efficiënte gedrag te bieden."
type: docs
weight: 6735
url: /nl/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

De [System::IO::Stream](../../system.io/stream/) die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB) (zie [IBlobManagementOptions](../iblobmanagementoptions/) beschrijving). De waarden van deze enumeratie geven aan hoe de [System::IO::Stream](../../system.io/stream/) moet worden behandeld wanneer deze aan de methode wordt doorgegeven. Afhankelijk van de vereisten kunnen verschillende beslissingen worden genomen om het meest efficiënte gedrag te bieden.

```cpp
enum class LoadingStreamBehavior
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | De stream wordt tot het einde gelezen en daarna vrijgegeven - d.w.z. er wordt gegarandeerd dat deze stream in de toekomst niet meer door een [IPresentation](../ipresentation/) instantie zal worden gebruikt. Hij kan door de clientcode worden gesloten of op een andere manier worden gebruikt. |
| KeepLocked | 1 | De stream wordt vergrendeld binnen het [IPresentation](../ipresentation/) object, d.w.z. het eigendom van de stream wordt overgedragen. Het [IPresentation](../ipresentation/) object is verantwoordelijk om de stream correct te verwijderen wanneer dit object zelf wordt verwijderd. Dit gedrag is uiterst nuttig wanneer u een groot BLOB-bestand moet serialiseren (zoals een grote video of audio - zie [IBlobManagementOptions](../iblobmanagementoptions/) beschrijving) en wilt voorkomen dat dit bestand in het geheugen wordt geladen of andere prestatieproblemen veroorzaakt. U kunt eenvoudig de [System::IO::FileStream](../../system.io/filestream/) voor dit bestand openen en aan een methode doorgeven, waarbij u [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior kiest. |

## Zie ook

* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)