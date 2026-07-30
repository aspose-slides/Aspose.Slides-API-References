---
title: what()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Implementuje metodu what(), která je volána třídou ExceptionWrapper. Navzdory tomu, že tato třída není zděděna ze std::exception, odvozené třídy mohou používat chráněné/privátní členy k implementaci své logiky. Přesunutí implementace této metody do ExceptionWrapper může tuto logiku narušit."
type: docs
weight: 105
url: /cs/system/details_exception/what/
---
## Details_Exception::what() const metoda


Implementuje metodu [what()](./), která je volána třídou [ExceptionWrapper](../../exceptionwrapper/). Navzdory tomu, že tato třída není zděděna z std::exception, odvozené třídy mohou používat chráněné/privátní členy k implementaci své logiky. Přesunutí implementace této metody do [ExceptionWrapper](../../exceptionwrapper/) může tuto logiku narušit.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Návratová hodnota

Popis výjimky.

## Viz také

* Třída [Details_Exception](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)