---
title: RoundImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter specificeert het gedrag van de functie als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.
type: docs
weight: 287
url: /nl/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) methode

Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter specificeert het gedrag van de functie als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde om af te ronden |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Specificeert hoe het afronden moet worden uitgevoerd als **value** even dicht bij twee dichtstbijzijnde getallen ligt. |

### Returnwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)