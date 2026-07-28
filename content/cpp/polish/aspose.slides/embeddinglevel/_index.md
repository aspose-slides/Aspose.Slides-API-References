---
title: EmbeddingLevel
second_title: Aspose.Slides for C++ – dokumentacja API
description: Reprezentuje prawa licencyjne do osadzania czcionki.
type: docs
weight: 5786
url: /pl/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Reprezentuje prawa licencyjne do osadzania czcionki.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) z tym ustawieniem wskazują, że może być osadzona i trwale zainstalowana w zdalnym systemie przez aplikację. Użytkownik zdalnego systemu uzyskuje te same prawa, obowiązki i licencje na tę czcionkę co pierwotny nabywca czcionki i podlega tej samej umowie licencyjnej końcowego użytkownika, prawom autorskim, patencie wzoru oraz/lub znakowi towarowemu co pierwotny nabywca. |
| Restricted | 2 | [Fonts](../fonts/) które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez uprzedniego uzyskania zgody prawowitego właściciela. |
| PreviewPrint | 4 | Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo wczytana w zdalnym systemie. Dokumenty zawierające czcionki Preview & Print muszą być otwarte w trybie \"read-only;\" nie można wprowadzać w nich zmian. |
| Editable | 8 | Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być instalowana wyłącznie tymczasowo na innych systemach. W przeciwieństwie do czcionek Preview & Print, dokumenty zawierające czcionki Editable mogą być otwierane do odczytu, edycja jest dozwolona, a zmiany mogą być zapisywane. |
| NoSubsetting | 256 | Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. Inne ograniczenia osadzania określone w bitach 0-3 i 9 również obowiązują. |
| BitmapOnly | 512 | Gdy ten bit jest ustawiony, mogą być osadzane tylko bitmapy zawarte w czcionce. Żadne dane konturu nie mogą być osadzane. Jeśli czcionka nie zawiera bitmap, jest uznawana za nieosadzalną i usługi osadzania zakończą się niepowodzeniem. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)