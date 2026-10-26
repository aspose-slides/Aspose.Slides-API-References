---
title: Equals< float, float >()
second_title: Aspose.Slides voor C++ API-referentie
description: "Specialisatie voor enkelprecisie zwevendekommagetallen. Hoewel twee zwevendekomma-NaNs volgens IEC 60559:1989 altijd als ongelijk worden vergeleken, vereist het contract voor System.Object.Equals dat overschrijvingen moeten voldoen aan de eisen voor een equivalentie-operator. Daarom geven System.Double.Equals en System.Single.Equals True terug bij het vergelijken van twee NaNs, terwijl de gelijkheidsoperator in dat geval False retourneert, zoals de standaard voorschrijft."
type: docs
weight: 2705
url: /nl/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) functie

Specialisatie voor enkelprecisie zwevendekommagetallen. Hoewel twee zwevendekomma-NaNs volgens IEC 60559:1989 altijd als ongelijk worden vergeleken, vereist het contract voor [System.Object.Equals](../object/equals/) dat overschrijvingen moeten voldoen aan de eisen voor een equivalentie-operator. Daarom geven System.Double.Equals en System.Single.Equals True terug bij het vergelijken van twee NaNs, terwijl de gelijkheidsoperator in dat geval False retourneert, zoals de standaard voorschrijft.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | const **float**\& | De eerste te vergelijken waarde |
| b | const **float**\& | De tweede te vergelijken waarde |

### Retourwaarde

True als beide waarden NaN zijn of gelijk zijn, anders - false

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)