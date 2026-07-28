---
title: ToArray()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza.
type: docs
weight: 92
url: /hu/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() metódus

Létrehoz és visszaad egy tömböt, amely az összes diát tartalmazza.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Visszatérési érték

A(z) [ISlide](../../islide/) tömbje

## ISlideCollection::ToArray(int32_t, int32_t) metódus

Létrehoz és visszaad egy tömböt, amely a megadott tartományból származó összes diát tartalmazza.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első hozzáadandó dia indexe. |
| count | **int32_t** | A hozzáadandó diák száma. |

### Visszatérési érték

A(z) [ISlide](../../islide/) tömbje

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [ISlideCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)