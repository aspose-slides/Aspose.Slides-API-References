---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/embeddinglevel/
---
## Wyliczenie EmbeddingLevel

Reprezentuje prawa licencyjne dotyczące osadzania czcionki.

Typ EmbeddingLevel udostępnia następujące elementy:

## Pola

| Pole | Opis |
| :- | :- |
| INSTALLABLE | Czcionki z tym ustawieniem oznaczają, że mogą być osadzone i trwale zainstalowane na zdalnym systemie przez aplikację. <br/>            Użytkownik zdalnego systemu nabywa te same prawa, obowiązki i licencje dla tej czcionki co pierwotny nabywca czcionki, <br/>            i podlega tej samej umowie licencyjnej użytkownika końcowego, prawom autorskim, patencie wzoru oraz/lub znakowi towarowemu, co pierwotny nabywca. |
| RESTRICTED | Czcionki, które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez uprzedniego uzyskania zgody prawnego właściciela. |
| PREVIEW_PRINT | Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo załadowana na zdalnym systemie. Dokumenty zawierające czcionki Preview & <br/>            Print muszą być otwierane w trybie „tylko do odczytu”; nie można wprowadzać zmian w dokumencie. |
| EDITABLE | Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być instalowana wyłącznie tymczasowo na innych systemach. W przeciwieństwie do czcionek Preview & <br/>            Print, dokumenty zawierające czcionki Editable mogą być otwierane w trybie odczytu, edycja jest dozwolona, a zmiany mogą być zapisywane. |
| NO_SUBSETTING | Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. Inne ograniczenia osadzania określone w bitach 0-3 i 9 również mają zastosowanie. |
| BITMAP_ONLY | Gdy ten bit jest ustawiony, jedynie bitmapy zawarte w czcionce mogą być osadzone. Żadne dane konturowe nie mogą być osadzone. Jeśli w czcionce nie ma dostępnych bitmap, <br/>            czcionka jest uważana za nieosadzalną i usługi osadzania zakończą się niepowodzeniem. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)