---
title: get_IsVisible()
second_title: Aspose.Slides C++ API referencia
description: A False azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). Csak olvasható bool.
type: docs
weight: 27
url: /hu/aspose.slides.charts/idatalabelcollection/get_isvisible/
---
## IDataLabelCollection::get_IsVisible() metódus

False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Csak olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelCollection::get_IsVisible()=0
```

## Megjegyzések

Ha az adatcímke alapértelmezés szerint látható, akkor a [Hide()](../hide/) metódussal alapértelmezés szerint elrejtheti. De ha az adatcímke alapértelmezés szerint nem látható (IsVisible is false), akkor a Show*-flags (ShowValue, ...) a DefaultDataLabelFormat property beállításával true állapotba hozva teheti a data labelt „visible 
by default”.

## Lásd még

* Osztály [IDataLabelCollection](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)