---
title: FontFamily()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe FontFamily che rappresenta una famiglia di caratteri con il nome specificato.
type: docs
weight: 1
url: /it/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) costruttore

Crea una nuova istanza della classe [FontFamily](../) che rappresenta una famiglia di caratteri con il nome specificato.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Un nome di famiglia di caratteri |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) costruttore

Crea una nuova istanza di [FontFamily](../) nella FontCollection specificata con il nome specificato.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Un nome di famiglia di caratteri |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | La FontCollection che contiene questa istanza. |

## FontFamily::FontFamily(Text::GenericFontFamilies) costruttore

Crea una nuova istanza di [FontFamily](../) dalla famiglia di caratteri generica specificata.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Il valore GenericFontFamilies per costruire il [FontFamily](../). |

## Vedi anche

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [FontFamily](../)
* Classe [FontCollection](../../../system.drawing.text/fontcollection/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)