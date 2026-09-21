---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeratie

Geeft het gedrag weer met betrekking tot het behandelen van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) bron (bestand of **io.RawIOBase**) tijdens het laden en werken met een instantie van [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation).

Het type PresentationLockingBehavior exposeert de volgende leden:

## Velden

| Veld | Beschrijving |
| :- | :- |
| LOAD_AND_RELEASE | De bron wordt alleen vergrendeld gedurende de uitvoering van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) constructor.<br/>            Als [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) is ingesteld op false, worden alle BLOB's <br/>            in het geheugen geladen. Anders kunnen andere methoden, zoals tijdelijke bestanden, worden gebruikt. Dit gedrag is trager dan [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/nl/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), en als het mogelijk is om het eigendom van de bron over te dragen aan [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation), wordt aanbevolen [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/nl/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) te gebruiken. |
| KEEP_LOCKED | De bron wordt vergrendeld voor de gehele levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) instantie, totdat deze <br/>            wordt afgevoerd.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) moet op true worden gezet om dit gedrag te gebruiken, anders wordt een uitzondering gegooid. Dit gedrag wordt aanbevolen, het is sneller en verbruikt minder geheugen dan [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/nl/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Opmerkingen

De bron is de parameter die aan de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) constructor wordt doorgegeven. In het onderstaande voorbeeld is de bron het bestand "pres.pptx":

Voor dit voorbeeld wordt de bron (bestand "pres.pptx") vergrendeld voor de levensduur van een [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) instantie, d.w.z. kan niet worden gewijzigd of verwijderd door een ander proces.


### Zie ook
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)