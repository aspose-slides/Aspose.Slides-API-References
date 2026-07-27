---
title: FontFallBackRule()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva instancia.
type: docs
weight: 66
url: /es/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructor

Crea una nueva instancia.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **uint32_t** | Índice inicial del rango unicode |
| endIndex | **uint32_t** | Índice final del rango unicode |
| fontNames | [System::String](../../../system/string/) | Nombre o nombres de la fuente (separados por comas) para FallBack |
## Observaciones

```cpp
// Crea una nueva instancia de FantFallBackRule con una fuente.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Crea una nueva instancia de FantFallBackRule con varias fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructor

Crea una nueva instancia.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | **uint32_t** | Índice inicial del rango unicode |
| endIndex | **uint32_t** | Índice final del rango unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nombre o nombres de la fuente (separados por comas) para FallBack |
## Observaciones

```cpp
// Crea una nueva instancia de FantFallBackRule con dos fuentes
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Crea una nueva instancia de FantFallBackRule con varias fuentes.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [FontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)