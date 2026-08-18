---
title: EmbeddingLevel
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje prawa licencyjne do osadzania czcionki.
type: docs
url: /pl/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Represents the licensing rights for embedding the font.
## Pola

| Pole | Opis |
| --- | --- |
| [Installable](#Installable) | Czcionki z tym ustawieniem wskazują, że mogą być osadzone i trwale zainstalowane na zdalnym systemie przez aplikację. |
| [Restricted](#Restricted) | Czcionki, które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez wcześniejszego uzyskania zgody prawowitego właściciela. |
| [PreviewPrint](#PreviewPrint) | Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo wczytana na zdalnym systemie. |
| [Editable](#Editable) | Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być zainstalowana tylko tymczasowo na innych systemach. |
| [NoSubsetting](#NoSubsetting) | Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. |
| [BitmapOnly](#BitmapOnly) | Gdy ten bit jest ustawiony, tylko bitmapy zawarte w czcionce mogą być osadzone. |
### Installable {#Installable}
```
public static final int Installable
```

Czcionki z tym ustawieniem wskazują, że mogą być osadzone i trwale zainstalowane na zdalnym systemie przez aplikację. Użytkownik zdalnego systemu nabywa takie same prawa, obowiązki i licencje dla tej czcionki, jak pierwotny nabywca czcionki, i podlega tej samej umowie licencyjnej końcowego użytkownika, prawom autorskim, patentowi na wzór oraz/lub znakowi towarowemu, co pierwotny nabywca.

### Restricted {#Restricted}
```
public static final int Restricted
```

Czcionki, które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez wcześniejszego uzyskania zgody prawowitego właściciela.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo wczytana na zdalnym systemie. Dokumenty zawierające czcionki Preview & Print muszą być otwierane w trybie "read-only"; nie można w nich wprowadzać zmian.

### Editable {#Editable}
```
public static final int Editable
```

Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być zainstalowana tylko tymczasowo na innych systemach. W przeciwieństwie do czcionek Preview & Print, dokumenty zawierające czcionki Editable mogą być otwierane do odczytu, edycja jest dozwolona, a zmiany mogą być zapisywane.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. Inne ograniczenia osadzania określone w bitach 0-3 i 9 również mają zastosowanie.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Gdy ten bit jest ustawiony, tylko bitmapy zawarte w czcionce mogą być osadzone. Nie mogą być osadzane żadne dane konturu. Jeśli w czcionce nie ma dostępnych bitmap, czcionka jest uważana za nieosadzalną i usługi osadzania zakończą się niepowodzeniem.