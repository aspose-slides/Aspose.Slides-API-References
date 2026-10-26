---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la primera aparición de una fuente FallBack específica de la lista.
type: docs
weight: 79
url: /es/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) método


Elimina la primera aparición de una fuente FallBack específica de la lista.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | El nombre de la fuente a eliminar de la lista. |
## Observaciones



```cpp
// Crea una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Eliminando Tahoma de la lista
newRule->Remove(u"Tahoma");
```


## Ver también

* Clase [String](../../../system/string/)
* Clase [IFontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)