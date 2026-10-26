---
title: ReadOnlySpan
second_title: Aspose.Slides C++ API referenciája
description: Használható a Span osztályban.
type: docs
weight: 1210
url: /hu/system/readonlyspan/
---
## ReadOnlySpan osztály


Használható a [Span](../span/) osztályban.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa. Ez az osztály típuskizáró módot biztosít az objektumok folytonos sorozataival csak olvasható módon való munka során. Használható tömbök, verem tömbök vagy nyers mutatók befoglalására, miközben fenntartja a határok ellenőrzését. A [ReadOnlySpan](./) nem birtokolja a memóriát, amelyre mutat - csak egy nézet a meglévő memóriára. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Létrehoz egy csak olvasható span-t egy szabályos span-ból. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Átalakít egy tömböt egy [ReadOnlySpan](./)-re. |
## Megjegyzések


Egy csak olvasható, folytonos memória területet képvisel tetszőleges memóriából.

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)