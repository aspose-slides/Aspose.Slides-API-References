---
title: KeyValuePair
second_title: Aspose.Slides för C++ API-referens
description: "Par av nyckel och värde. Denna typ bör allokeras på stacken och passeras till funktioner per värde eller per referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 378
url: /sv/system.collections.generic/keyvaluepair/
---
## KeyValuePair klass

Par av nyckel och värde. Denna typ bör allokeras på stacken och passeras till funktioner per värde eller per referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Hämtar nyckeln. |
| const TValue\& [get_Value](./get_value/)() const | Hämtar värdet. |
| int [GetHashCode](./gethashcode/)() const | Beräknar nyckel-värde-parhash genom att xora nyckelns och värdets hash. |
| **bool** [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| [KeyValuePair](./keyvaluepair/)() | Noll initierare för nyckel-värde-par. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Typkonverteringskonstruktor. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch för klasser som ärver från IComparer<KeyValuePair<TKey, TValue>>, jämför ingenting. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konverterar nyckel-värde-par till sträng. |

## Se också

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)