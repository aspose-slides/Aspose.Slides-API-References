---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumeratie

De **io.RawIOBase** die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB) (zie [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions) beschrijving). Waarden van deze enumeratie geven aan hoe de **io.RawIOBase** behandeld moet worden wanneer deze aan de methode wordt doorgegeven. Afhankelijk van de eisen kunnen verschillende beslissingen worden genomen om het meest efficiënte gedrag te bieden.

Het LoadingStreamBehavior-type geeft de volgende leden weer:

## Velden

| Veld | Beschrijving |
| :- | :- |
| READ_STREAM_AND_RELEASE | De stream wordt tot het einde gelezen en vervolgens vrijgegeven - d.w.z. het wordt gegarandeerd dat deze stream <br/>            niet door een [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-instantie in de toekomst wordt gebruikt. Hij kan worden gesloten door de clientcode <br/>            of op welke andere manier dan ook worden gebruikt. |
| KEEP_LOCKED | De stream wordt vergrendeld binnen het [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-object, d.w.z. het eigendom van <br/>            de stream wordt overgedragen. Het [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)-object is verantwoordelijk om <br/>            de stream correct te verwijderen wanneer dit object zelf wordt verwijderd. <br/>            Dit gedrag is bijzonder nuttig wanneer u een groot BLOB-bestand moet serialiseren (zoals een grote <br/>            video of audio - zie [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions) beschrijving) en u wilt voorkomen dat dit bestand <br/>            in het geheugen wordt geladen of andere prestatieproblemen ontstaan. U kunt eenvoudig de **System.IO.FileStream** <br/>            voor dit bestand openen en doorgeven aan een methode, waarbij u [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/nl/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior kiest. |

### Zie ook
* klasse [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)