---
title: ToBox()
second_title: Referência da API Aspose.Slides para C++
description: Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem um ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele.
type: docs
weight: 274
url: /pt/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() método

Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem um ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Valor de Retorno

Caixa lógica com este elemento colocado dentro
## Observações



Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)