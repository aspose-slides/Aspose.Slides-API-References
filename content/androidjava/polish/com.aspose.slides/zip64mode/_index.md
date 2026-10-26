---
title: Zip64Mode
second_title: Aspose.Slides dla Androida – referencja API Java
description: Określa, kiedy używać rozszerzeń formatu ZIP64 dla pliku OpenXML.
type: docs
url: /pl/com.aspose.slides/zip64mode/
---
**Dziedziczenie:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Określa, kiedy używać rozszerzeń formatu ZIP64 dla pliku OpenXML.

--------------------

Plik OpenXML jest archiwum ZIP, które ma limit 4 GB (2^32 bajtów) na rozmiar niekompresowany pliku, rozmiar skompresowany pliku oraz całkowity rozmiar archiwum, a także limit 65 535 (2^16-1) plików w archiwum. Rozszerzenia formatu ZIP64 zwiększają limity do 2^64.
## Pola

| Pole | Opis |
| --- | --- |
| [Never](#Never) | Nie używaj rozszerzeń formatu ZIP64. |
| [IfNecessary](#IfNecessary) | Użyj rozszerzeń formatu ZIP64 w razie potrzeby. |
| [Always](#Always) | Zawsze używaj rozszerzeń formatu ZIP64. |
### Never {#Never}
```
public static final int Never
```

Nie używaj rozszerzeń formatu ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Użyj rozszerzeń formatu ZIP64 w razie potrzeby.

### Always {#Always}
```
public static final int Always
```

Zawsze używaj rozszerzeń formatu ZIP64.