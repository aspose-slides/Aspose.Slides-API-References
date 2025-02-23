---
title: AddFallBackFonts
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agrega unas nuevas fuentes a la lista de fuentes FallBack.
type: docs
weight: 50
url: /es/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## AddFallBackFonts(string) {#addfallbackfonts}

Agrega una(s) nueva(s) fuente(s) a la lista de fuentes FallBack.

```csharp
public void AddFallBackFonts(string fontName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Nombre o nombres de la fuente (delimitados por comas) para FallBack |

### Ejemplos

```csharp
[C#]
//Crear una nueva instancia de FantFallBackRule
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");

//Añadir una segunda fuente a la regla 
newRule.AddFallBackFonts("MS Gothic");
//Agregue una tercera y cuarta fuente a la regla 
newRule.AddFallBackFonts("Tahoma, Times New Roman");
```

### Ver también

* interface [IFontFallBackRule](../../ifontfallbackrule)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrule)
* asamblea [Aspose.Slides](../../../)

---

## AddFallBackFonts(string[]) {#addfallbackfonts_1}

Agrega una nueva fuente a la lista de fuentes FallBack.

```csharp
public void AddFallBackFonts(string[] fontNames)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontNames | String[] | Nombre o nombres de la fuente (delimitados por comas) para FallBack |

### Ejemplos

```csharp
[C#]
//Crear una nueva instancia de FontFallBackRule
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");

//Añadir otras tres fuentes a la regla 
newRule.AddFallBackFonts(new string [] {"MS Gothic","Tahoma, Times New Roman"});
```

### Ver también

* interface [IFontFallBackRule](../../ifontfallbackrule)
* espacio de nombres [Aspose.Slides](../../ifontfallbackrule)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
