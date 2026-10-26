---
title: RemoveScriptFont()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja a témához tartozó betűkészletgyűjteményből a megadott script címkéhez kapcsolódó betűkészlet beállítást.
type: docs
weight: 118
url: /hu/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metódus


Eltávolítja az adott script címkéhez társított betűkészlet beállítást a téma betűkészletgyűjteményéből.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | A BCP-47 scriptkód, amelynek a betűkészlet beállítását el kell távolítani. |
## Megjegyzések



Ez a példa bemutatja, hogyan lehet eltávolítani a héber script betűkészlet leképezést: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [Fonts](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)