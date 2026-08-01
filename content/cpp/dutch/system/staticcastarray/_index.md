---
title: StaticCastArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert casting uit van elementen van de opgegeven array naar een ander type. Overschrijf voor gevallen waarin From een SmartPtr obj is.
type: docs
weight: 2978
url: /nl/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) functie

Voert casting uit van elementen van de opgegeven array naar een ander type. Overschrijf voor gevallen waarin From [SmartPtr](../smartptr/) obj is.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| To | Het type waartoe de elementen van de opgegeven array moeten worden gecast |
| From | Het type van de elementen van de array waarvan wordt gecast |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Gedeelde pointer naar de array die de te casten elementen bevat |

### Retourwaarde

Een pointer naar een nieuwe array die elementen van type **To** bevat die gelijk zijn aan de elementen van **from**

Verouderd
:   Toegevoegd voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) functie

Voert casting uit van elementen van de opgegeven array naar een ander type. Overschrijf voor gevallen waarin From Boxable is en To [Object](../object/)[] is.

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| To | Het type waartoe de elementen van de opgegeven array moeten worden gecast |
| From | Het type van de elementen van de array waarvan wordt gecast |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Gedeelde pointer naar de array die de te casten elementen bevat |

### Retourwaarde

Een pointer naar een nieuwe array die elementen van type **To** bevat die gelijk zijn aan de elementen van **from**

Verouderd
:   Toegevoegd voor achterwaartse compatibiliteit. Gebruik ExplicitCast in plaats daarvan.

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [Array](../array/)
* Klasse [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)