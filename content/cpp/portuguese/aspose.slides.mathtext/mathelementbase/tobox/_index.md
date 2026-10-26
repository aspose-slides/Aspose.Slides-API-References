---
title: ToBox()
second_title: Aspose.Slides para C++ Referência da API
description: Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem um ponto de alinhamento, servir como um ponto de quebra de linha ou ser agrupado de forma a não permitir quebras de linha dentro dele.
type: docs
weight: 261
url: /pt/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() método

Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Valor de Retorno

Logical box with this element placed inside

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBox](../../imathbox/)
* Classe [MathElementBase](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)