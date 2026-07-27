---
title: FontFamily()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase FontFamily que representa una familia de fuentes con el nombre especificado.
type: docs
weight: 1
url: /es/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor

Construye una nueva instancia de la clase [FontFamily](../) que representa una familia de fuentes con el nombre especificado.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Un nombre de familia de fuentes |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor

Construye una nueva instancia de [FontFamily](../) en la FontCollection especificada con el nombre indicado.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Un nombre de familia de fuentes |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | La FontCollection que contiene esta instancia. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor

Construye una nueva instancia de [FontFamily](../) a partir de la familia de fuentes genérica especificada.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | El valor GenericFontFamilies para construir el [FontFamily](../). |

## Ver también

* Enumeración [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [FontFamily](../)
* Clase [FontCollection](../../../system.drawing.text/fontcollection/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)