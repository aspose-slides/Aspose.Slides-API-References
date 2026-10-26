---
title: Span
second_title: Aspose.Slides C++ API hivatkozás
description: "Egy folytonos, tetszőleges memóriaterületet képvisel, amely hasonló a C++20 std::span osztályához."
type: docs
weight: 1262
url: /hu/system/span/
---
## Span osztály


Egy folytonos régiót képvisel tetszőleges memóriában, amely hasonló a C++20 std::span osztályához.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az elemek típusa a span-ben. Ez az osztály típusbiztos módot biztosít a folytonos objektumsorozatok kezelésére. Használható tömbök, verem-tömbök vagy nyers mutatók becsomagolására, miközben a határok ellenőrzését fenntartja. A [Span](./) nem birtokolja a memóriát, amire mutat - ez csak egy nézet a létező memóriára. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [Clear](./clear/)() const | Törli a span tartalmát, az összes elemet alapértelmezett értékre állítva. |
| void [Fill](./fill/)(const T\&) const | Kitölti a span-et a megadott értékkel. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Átalakít egy tömböt [Span](./) típusúvá. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)