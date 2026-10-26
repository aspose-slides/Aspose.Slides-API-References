---
title: DoTryFinally()
second_title: Aspose.Slides voor C++ API-referentie
description: De enkele functie die het gedrag van de try[-catch]-finally-statement van C# emuleert. Bij het vertalen van de try[-catch]-finally-statement van C# met de vertaler-optie finally_statement_as_lambda ingesteld op true, wordt de statement vertaald naar een aanroep van deze methode.
type: docs
weight: 2445
url: /nl/system/dotryfinally/
---
## System::DoTryFinally(T\&&, F\&&) functie


De enkele functie die het gedrag van de try[-catch]-finally-statement van C# emuleert. Bij het vertalen van de try[-catch]-finally-statement van C# met de vertaler-optie finally_statement_as_lambda ingesteld op true, wordt de statement vertaald naar een aanroep van deze methode.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_void<T>::value> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het functie-object dat het try[-catch]-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |
| F | Het type van het functie-object dat het finally-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tryBlock | T\&& | Het functie-object waarvan het lichaam de implementatie van het try[-catch]-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |
| finallyBlock | F\&& | Het functie-object waarvan het lichaam de implementatie van het finally-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |

## System::DoTryFinally(T\&&, F\&&) functie


De enkele functie die het gedrag van de try[-catch]-finally-statement van C# emuleert. Bij het vertalen van de try[-catch]-finally-statement van C# met de vertaler-optie finally_statement_as_lambda ingesteld op true, wordt de statement vertaald naar een aanroep van deze methode. Deze overload behandelt het geval waarin de retourwaarde van het functie-object dat het try[-catch]-deel van de try[-catch]-finally-statement implementeert, bool is.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_void_boolref<T>::value, bool> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het functie-object dat het try[-catch]-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |
| F | Het type van het functie-object dat het finally-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tryBlock | T\&& | Het functie-object waarvan het lichaam de implementatie van het try[-catch]-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |
| finallyBlock | F\&& | Het functie-object waarvan het lichaam de implementatie van het finally-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |

## System::DoTryFinally(T\&&, F\&&) functie


De enkele functie die het gedrag van de try[-catch]-finally-statement van C# emuleert. Bij het vertalen van de try[-catch]-finally-statement van C# met de vertaler-optie finally_statement_as_lambda ingesteld op true, wordt de statement vertaald naar een aanroep van deze methode. Deze overload behandelt het geval waarin de retourwaarde van het functie-object dat het try[-catch]-deel van de try[-catch]-finally-statement implementeert, bool& is.

```cpp
template<typename T,typename F> std::enable_if_t<Details::is_lambda_nonovoid_boolref<T>::value, std::optional<Details::ResultOf<T, bool &>>> System::DoTryFinally(T &&tryBlock, F &&finallyBlock)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het functie-object dat het try[-catch]-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |
| F | Het type van het functie-object dat het finally-deel van de try[-catch]-finally-statement implementeert die wordt nagebootst |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tryBlock | T\&& | Het functie-object waarvan het lichaam de implementatie van het try[-catch]-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |
| finallyBlock | F\&& | Het functie-object waarvan het lichaam de implementatie van het finally-deel van de try[-catch]-finally-statement bevat die wordt nagebootst |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)