---
title: Is()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: 
type: docs
weight: 27
url: /pl/system/details_argumentnullexception/is/
---
## Szczegóły_ArgumentNullException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_ArgumentNullException::Is(const System::TypeInfo &target) const override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktura opisująca typ, przeciwko któremu testowany jest bieżący obiekt. |

### Wartość zwracana

Prawda, jeśli obiekt jest typu oznaczonego lub jego podklasą, w przeciwnym razie fałsz.
## Uwagi

Sprawdź, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is' .
## Zobacz także

* Klasa [TypeInfo](../../typeinfo/)
* Klasa [Details_ArgumentNullException](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)