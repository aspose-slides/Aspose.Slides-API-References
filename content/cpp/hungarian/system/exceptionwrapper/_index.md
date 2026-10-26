---
title: ExceptionWrapper
second_title: Aspose.Slides C++ API referencia
description: Sablon, amely a Exception osztályból származó kivételek csomagolóját képviseli.
type: docs
weight: 833
url: /hu/system/exceptionwrapper/
---
## ExceptionWrapper osztály

Sablon, amely a Exception osztályból származó kivételek csomagolóját képviseli.

```cpp
template<typename T>class ExceptionWrapper
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Létrehozza a(z) [ExceptionWrapper](./) osztály null-példányát, amely nem képvisel semmilyen kivételt. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Létrehozza a(z) [ExceptionWrapper](./) osztály egy példányát, amely a megadott mutatót tartalmazza. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Másoló konstruktor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Mozgató konstruktor. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor, amely továbbítja a paramétereket az Exception osztály konstruktorainak, és intelligens mutatót hoz létre, amely az új Exception osztály példányát tárolja. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Implicit átalakító operátor SharedPtr<Object> típusra |
| T * [operator->](./operator_minus_greater/)() const | Lehetővé teszi az Exception objektum tagjainak elérését. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Értékadási operátor. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Mozgató értékadási operátor. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Rövid út a [System::TypeInfo](../typeinfo/) objektum lekéréséhez az Exception típushoz. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ExceptionType](./exceptiontype/) | A típuskonverziós függvényekhez használatos. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)