---
title: ConvertAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Liste von Elementen, die in einen anderen Typ konvertiert werden.
type: docs
weight: 352
url: /de/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) Methode

Erstellt eine Liste von Elementen, die in einen anderen Typ konvertiert werden.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| OutputType | Typ des Listenelements für die Ausgabe. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Zu verwendender Konverter für die Elementkonvertierung. |

### Rückgabewert

Eine neu erstellte Liste von konvertierten Elementen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Klasse [List](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)