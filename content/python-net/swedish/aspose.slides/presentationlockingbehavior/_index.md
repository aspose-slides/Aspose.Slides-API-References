---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior-enumeration

Representerar beteendet för hur [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-källan (fil eller **io.RawIOBase**) behandlas vid inläsning och arbete med en instans av [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation).

PresentationLockingBehavior-typen exponerar följande medlemmar:

## Fält

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | Källan kommer endast att låsas under tiden för [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-konstruktorns körning.<br/>            Om [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) är satt till false kommer alla BLOB-objekt <br/>            att läsas in i minnet. Annars kan andra metoder såsom temporära filer användas. Detta beteende är långsammare än [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/sv/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), och om det är möjligt att överföra <br/>            ägandet av källan till [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation), rekommenderas att använda [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/sv/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Källan kommer att låsas under hela livslängden för en [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instans, tills den <br/>            tas bort.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) måste vara satt till true för att använda <br/>            detta beteende, annars kommer ett undantag att kastas. Detta beteende rekommenderas, det är snabbare och använder mindre minne än [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/sv/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Anmärkningar

Källan är den parameter som skickas till [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-konstruktorn. I exemplet nedan är källan filen "pres.pptx":

För detta exempel kommer källan ("pres.pptx"-filen) att låsas för en [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)-instans livslängd, d.v.s. kan inte ändras eller raderas av en annan process.


### Se även
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)