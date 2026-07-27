---
title: Remove()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina la primera aparición de una fuente FallBack específica de la lista.
type: docs
weight: 118
url: /es/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) método


Elimina la primera aparición de una fuente FallBack específica de la lista.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | El nombre de la fuente a eliminar de la lista. |
## Comentarios



```cpp
// Crear una regla que contiene una lista de fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Eliminar Tahoma de la lista.
newRule->Remove(u"Tahoma");
```


## Ver también

* Clase [String](../../../system/string/)
* Clase [FontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)