---
title: get_PathTypes()
second_title: Aspose.Slides C++ API Referencia
description: Egy byte értékekből álló tömböt ad vissza, amely meghatározza az elem útvonalának minden pontjának típusát.
type: docs
weight: 27
url: /hu/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() method

Egy byte értékekből álló tömböt ad vissza, amely meghatározza az elem útvonalának minden pontjának típusát.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Megjegyzések

**0** Jelzi, hogy a pont a figura kezdetét jelöli.

**1** Jelzi, hogy a pont egy vonal két végpontjának egyike.

**3** Jelzi, hogy a pont egy végpont vagy egy irányító pont egy köbös Bézier görbében.

**7** Maszkolja az összes bitet kivéve a három legalacsonyabb sorrendű bitet, amelyek a pont típusát jelzik.

**16** A megfelelő szegmens szaggatott.

**32** A pont egy jelző.

**128** A pont a zárt alútvonal (figura) utolsó pontja.

**129** Egy olyan adatpontot jelöl, amely egyszerre egy vonal szegmens végpontja és egy zárt alútvonal utolsó pontja.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)