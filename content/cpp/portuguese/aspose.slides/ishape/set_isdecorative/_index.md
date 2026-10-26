---
title: set_IsDecorative()
second_title: Referência da API Aspose.Slides para C++
description: Define a opção 'Mark as decorative' de leitura/gravação bool.
type: docs
weight: 417
url: /pt/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) método

Define a opção 'Marcar como decorativo' Leitura/gravação **bool**.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## Observações


```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Ver também

* Classe [IShape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)