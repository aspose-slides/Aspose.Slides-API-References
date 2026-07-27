---
title: AddFallBackFonts()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack.
type: docs
weight: 40
url: /es/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) método

Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nombre o nombres de la fuente (delimitados por coma) para FallBack |

## Comentarios

```cpp
//Crear una nueva instancia de FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Agregar una segunda fuente a la regla
newRule->AddFallBackFonts(u"MS Gothic");
//Agregar una tercera y cuarta fuente a la regla
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) método

Agrega nuevas fuentes a la lista de fuentes FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nombre o nombres de la fuente (delimitados por coma) para FallBack |

## Comentarios

```cpp
//Crear una nueva instancia de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Añadir otras tres fuentes a la regla
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [IFontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)