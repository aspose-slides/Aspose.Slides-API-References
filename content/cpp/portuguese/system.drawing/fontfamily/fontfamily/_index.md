---
title: FontFamily()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe FontFamily que representa uma família de fontes com o nome especificado.
type: docs
weight: 1
url: /pt/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor

Constrói uma nova instância da classe [FontFamily](../) que representa uma família de fontes com o nome especificado.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Um nome de família de fontes |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor

Constrói uma nova instância de [FontFamily](../) na FontCollection especificada com o nome especificado.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Um nome de família de fontes |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | A FontCollection que contém esta instância. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor

Constrói uma nova instância de [FontFamily](../) a partir da família de fontes genérica especificada.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | O valor GenericFontFamilies para construir o [FontFamily](../). |

## Veja Também

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)