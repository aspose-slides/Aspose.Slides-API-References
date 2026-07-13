---
title: EmbeddingLevel
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje prawa licencyjne dotyczące osadzania czcionki.
type: docs
url: /pl/com.aspose.slides/embeddinglevel/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Reprezentuje prawa licencyjne dotyczące osadzania czcionki.
## Pola

| Pole | Opis |
| --- | --- |
| [Installable](#Installable) | Czcionki z tym ustawieniem wskazują, że mogą być osadzone i trwale zainstalowane na zdalnym systemie przez aplikację. |
| [Restricted](#Restricted) | Czcionki, które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez uprzedniego uzyskania zgody właściciela praw. |
| [PreviewPrint](#PreviewPrint) | Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo załadowana na zdalnym systemie. |
| [Editable](#Editable) | Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być instalowana wyłącznie tymczasowo na innych systemach. |
| [NoSubsetting](#NoSubsetting) | Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. |
| [BitmapOnly](#BitmapOnly) | Gdy ten bit jest ustawiony, jedynie bitmapy zawarte w czcionce mogą być osadzone. |
### Installable {#Installable}
```
public static final int Installable
```

Czcionki z tym ustawieniem wskazują, że mogą być osadzone i trwale zainstalowane na zdalnym systemie przez aplikację. Użytkownik zdalnego systemu nabywa identyczne prawa, zobowiązania i licencje do tej czcionki, takie same jak pierwotny nabywca czcionki, i podlega tej samej umowie licencyjnej dla użytkownika końcowego, prawom autorskim, patencie wzoru oraz/lub znakowi towarowemu, jak pierwotny nabywca.

### Restricted {#Restricted}
```
public static final int Restricted
```

Czcionki, które mają ustawiony tylko ten bit, nie mogą być modyfikowane, osadzane ani wymieniane w żaden sposób bez uprzedniego uzyskania zgody właściciela praw.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Gdy ten bit jest ustawiony, czcionka może być osadzona i tymczasowo załadowana na zdalnym systemie. Dokumenty zawierające czcionki Preview & Print muszą być otwierane w trybie "tylko do odczytu"; nie można w nich wprowadzać zmian.

### Editable {#Editable}
```
public static final int Editable
```

Gdy ten bit jest ustawiony, czcionka może być osadzona, ale musi być instalowana wyłącznie tymczasowo na innych systemach. W przeciwieństwie do czcionek Preview & Print, dokumenty zawierające czcionki Editable mogą być otwierane do odczytu, edycja jest dozwolona, a zmiany mogą być zapisywane.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Gdy ten bit jest ustawiony, czcionka nie może być podzestawiana przed osadzeniem. Inne ograniczenia osadzania określone w bitach 0-3 i 9 również mają zastosowanie.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Gdy ten bit jest ustawiony, jedynie bitmapy zawarte w czcionce mogą być osadzone. Żadne dane konturów nie mogą być osadzone. Jeśli w czcionce nie ma dostępnych bitmap, czcionka jest uznawana za nieosiągalną i usługi osadzania zakończą się niepowodzeniem.