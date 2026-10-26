---
title: HolderInitializer
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse wordt gebruikt om een persistente referentie naar de objectinstantie te krijgen, of het nu een lvalue of rvalue is. Om zo'n referentie te verkrijgen, gebruik de 'HoldIfTemporary'-methode, die daar drie overloads heeft. Twee daarvan nemen een rvalue als parameter en retourneren simpelweg de referentie ernaar. De derde, in tegenstelling, neemt een lvalue als parameter, maakt een pointer-copy en retourneert vervolgens de referentie naar die copy. Ook heeft de klasse de 'Hold'-methode om de doorgegeven waarde onvoorwaardelijk vast te houden (gebruikt om waarden van lokale on-stack variabelen of diens kind-referenties te kopiëren).
type: docs
weight: 1639
url: /nl/system/holderinitializer/
---
## HolderInitializer struct


Deze klasse wordt gebruikt om een persistente referentie naar het objectinstance te krijgen, of het nu een lvalue of rvalue is. Om zo’n referentie te verkrijgen, gebruik de ‘HoldIfTemporary’-methode, die daar drie overloads heeft. Twee daarvan nemen een rvalue als parameter en retourneren simpelweg de referentie ernaar. De derde, in tegenstelling, neemt een lvalue als parameter, maakt een pointer-copy en retourneert vervolgens de referentie naar die copy. Ook heeft de klasse de ‘Hold’-methode om de doorgegeven waarde onvoorwaardelijk vast te houden (gebruikt om waarden van lokale on-stack variabelen of diens kind-referenties te kopiëren)

```cpp
template<typename T,bool>class HolderInitializer
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het object dat vastgehouden moet worden. |
| R | True, als T een referentietype is ([SmartPtr](../smartptr/) specialisatie of [System::String](../string/) type), en het vasthouden van tijdelijke referenties daadwerkelijk vereist is, false - anders. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) | Kopieert de doorgegeven lvalue naar de houder, en retourneert vervolgens de houderreferentie. De aanroeper moet deze methode gebruiken om de doorgegeven waarde onvoorwaardelijk vast te houden. |
|  [HolderInitializer](./holderinitializer/)(T\&) | Initialiseert de houderreferentie met de doorgegeven. |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) | Retourneert een referentie naar een rvalue (const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&) | Retourneert een referentie naar een rvalue (niet-const) |
| const T\& [HoldIfTemporary](./holdiftemporary/)(T\&&) | Kopieert de doorgegeven lvalue naar de houder, en retourneert vervolgens de houderreferentie. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)