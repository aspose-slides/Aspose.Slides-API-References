---
title: AddFallBackFonts()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una(s) nueva(s) fuente(s) a la lista de fuentes de reserva.
type: docs
weight: 79
url: /es/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) método


Agrega una(s) nueva(s) fuente(s) a la lista de fuentes de reserva.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nombre de la fuente o nombres (separados por coma) para reserva |
## Observaciones



```cpp
// Crear una nueva instancia de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Agregar una segunda fuente a la regla
newRule->AddFallBackFonts(u"MS Gothic");
//Agregar una tercera y una cuarta fuente a la regla
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) método


Agrega nuevas fuentes a la lista de fuentes de reserva.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nombres de la(s) fuente(s) (separados por coma) para reserva |
## Observaciones



```cpp
//Crear una nueva instancia de FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Agregar otras tres fuentes a la regla
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [FontFallBackRule](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)