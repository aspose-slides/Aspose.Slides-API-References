---
title: what()
second_title: "Aspose.Slides för C++ API-referens"
description: "Implementerar what()-metoden som anropas av ExceptionWrapper-klassen. Trots att den här klassen inte ärver från std::exception kan avledda klasser använda skyddade/privata medlemmar för att implementera sin logik. Att flytta den här metodimplementeringen till ExceptionWrapper kan bryta den logiken."
type: docs
weight: 105
url: /sv/system/details_exception/what/
---
## Details_Exception::what() const metod


Implementerar [what()](./) metod som anropas av [ExceptionWrapper](../../exceptionwrapper/) klass. Trots att den här klassen inte ärver från std::exception kan avledda klasser använda skyddade/privata medlemmar för att implementera sin logik. Att flytta den här metodimplementeringen till [ExceptionWrapper](../../exceptionwrapper/) kan bryta den logiken.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Returvärde

Beskrivning av undantaget.

## Se även

* Klass [Details_Exception](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)