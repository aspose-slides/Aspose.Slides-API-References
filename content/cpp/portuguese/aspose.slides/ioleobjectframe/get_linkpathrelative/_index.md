---
title: get_LinkPathRelative()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. Somente leitura System::String."
type: docs
weight: 118
url: /pt/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() método


Retorna o caminho relativo para um arquivo vinculado, se presente; caso contrário, retorna uma string vazia. Somente leitura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Observações


Nas apresentações Ppt, alguns links de objetos Ole podem ter uma representação relativa. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [IOleObjectFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)