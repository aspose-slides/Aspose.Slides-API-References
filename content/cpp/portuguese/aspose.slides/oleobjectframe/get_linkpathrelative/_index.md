---
title: get_LinkPathRelative()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna o caminho relativo para um arquivo vinculado, se presente, caso contrário retorna uma string vazia. Somente leitura System::String."
type: docs
weight: 131
url: /pt/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() método

Retorna o caminho relativo para um arquivo vinculado, se presente, caso contrário retorna uma string vazia. Somente leitura [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Observações

Nas apresentações Ppt, alguns vínculos de objetos Ole podem ter uma representação relativa. 

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Ver também

* Classe [String](../../../system/string/)
* Classe [OleObjectFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)