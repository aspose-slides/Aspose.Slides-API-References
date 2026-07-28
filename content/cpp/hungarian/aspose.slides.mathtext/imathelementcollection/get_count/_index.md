---
title: get_Count()
second_title: Aspose.Slides C++ API referencia
description: A gyűjteményben ténylegesen található elemek számát adja vissza. Csak olvasható int32_t.
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() metódus

A ténylegesen a gyűjteményben lévő elemek számát adja vissza. Csak olvasható **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Megjegyzések

Példa:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Lásd még

* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)