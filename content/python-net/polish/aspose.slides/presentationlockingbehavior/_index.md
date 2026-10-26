---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides dla Pythona przy użyciu .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/presentationlockingbehavior/
---
## Wyliczenie PresentationLockingBehavior

Reprezentuje zachowanie dotyczące traktowania źródła [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation) (plik lub **io.RawIOBase**) podczas ładowania i pracy z instancją [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation).

Typ PresentationLockingBehavior udostępnia następujące członki:

## Pola

| Field | Description |
| :- | :- |
| LOAD_AND_RELEASE | Źródło będzie zablokowane tylko na czas wykonywania konstruktora [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation).<br/> Jeśli [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) jest ustawione na false, wszystkie BLOBy <br/> zostaną załadowane do pamięci. W przeciwnym razie mogą być użyte inne metody, takie jak pliki tymczasowe. To zachowanie jest wolniejsze niż [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/pl/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), i jeśli możliwe jest przekazanie <br/> własności źródła do [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation), zaleca się użycie [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/pl/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Źródło będzie zablokowane na cały okres życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation), aż zostanie <br/> zwolnione.<br/> [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) musi być ustawione na true, aby używać <br/> tego zachowania, w przeciwnym razie zostanie zgłoszony wyjątek. To zachowanie jest zalecane, jest szybsze i zużywa mniej pamięci niż [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/pl/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Uwaga

Źródło jest parametrem przekazywanym do konstruktora [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). W poniższym przykładzie źródłem jest plik "pres.pptx":

Dla tego przykładu źródło (plik "pres.pptx") będzie zablokowane na cały czas życia instancji [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation), tzn. nie może być zmieniane ani usuwane przez inny proces.


### Zobacz także
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)