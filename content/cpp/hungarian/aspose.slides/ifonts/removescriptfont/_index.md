---
title: RemoveScriptFont()
second_title: Aspose.Slides C++ API-referencia
description: Eltávolítja a betűkészlet-beállítást, amely egy adott script címkéhez kapcsolódik a téma betűkészlet-gyűjteményéből.
type: docs
weight: 118
url: /hu/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) metódus


Eltávolítja a betűkészlet-beállítást, amely egy adott script címkéhez kapcsolódik a téma betűkészlet-gyűjteményéből.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 scriptkód, amelynek a betűkészlet-beállítását el kell távolítani. |
## Megjegyzések



Ez a példa bemutatja, hogyan lehet eltávolítani a héber script betűtérképét: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IFonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)