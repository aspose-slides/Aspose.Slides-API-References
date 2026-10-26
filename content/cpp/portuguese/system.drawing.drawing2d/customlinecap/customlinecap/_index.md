---
title: CustomLineCap()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe CustomLineCap que representa uma ponta de linha definida pelo usuário com as propriedades especificadas.
type: docs
weight: 1
url: /pt/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) construtor

Constrói uma nova instância da classe [CustomLineCap](../) que representa uma ponta de linha definida pelo usuário com as propriedades especificadas.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Especifica um preenchimento para a ponta personalizada |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Especifica um contorno da ponta personalizada |
| baseCap | [LineCap](../../linecap/) | A ponta de linha base a partir da qual a ponta personalizada é criada |
| baseInset | **float** | Especifica a distância entre a linha e a ponta |

## Ver também

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [GraphicsPath](../../graphicspath/)
* classe [CustomLineCap](../)
* namespace [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)