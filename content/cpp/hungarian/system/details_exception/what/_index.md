---
title: what()
second_title: Aspose.Slides C++ API referencia
description: "Megvalósítja a what() metódust, amelyet az ExceptionWrapper osztály hív. Annak ellenére, hogy ez az osztály nem öröklődik a std::exception osztályból, a származtatott osztályok a protected/private tagok használatával valósíthatják meg logikájukat. A metódus implementációjának áthelyezése az ExceptionWrapper-be megtörheti ezt a logikát."
type: docs
weight: 105
url: /hu/system/details_exception/what/
---
## Details_Exception::what() const metódus

[what()](./) metódust valósítja meg, amelyet a [ExceptionWrapper](../../exceptionwrapper/) osztály hív.  
Annak ellenére, hogy ez az osztály nem öröklődik a std::exception-ből, a származtatott osztályok a protected/private tagok használatával valósíthatják meg a logikájukat.  
A metódus implementációjának áthelyezése a [ExceptionWrapper](../../exceptionwrapper/)-ba sértheti a logikát.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### Visszatérési érték

A kivétel leírása.

## Lásd még

* Osztály [Details_Exception](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)