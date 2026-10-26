---
title: what()
second_title: Aspose.Slides voor C++ API-referentie
description: "Implementeert de what() methode die wordt aangeroepen door de ExceptionWrapper klasse. Ondanks het feit dat deze klasse niet is geërfd van std::exception, kunnen afgeleide klassen protected/private members gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de ExceptionWrapper kan die logica breken."
type: docs
weight: 105
url: /nl/system/details_exception/what/
---
## Details_Exception::what() const methode


Implementeert [what()](./) methode die wordt aangeroepen door [ExceptionWrapper](../../exceptionwrapper/) klasse. Ondanks het feit dat deze klasse niet geërfd is van std::exception, kunnen afgeleide klassen protected/private members gebruiken om hun logica te implementeren. Het verplaatsen van deze methode-implementatie naar de [ExceptionWrapper](../../exceptionwrapper/) kan die logica breken.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Returnwaarde

De beschrijving van de uitzondering.

## Zie ook

* Klasse [Details_Exception](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)