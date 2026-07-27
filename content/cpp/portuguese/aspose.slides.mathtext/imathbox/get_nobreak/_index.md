---
title: get_NoBreak()
second_title: Aspose.Slides para C++ Referência da API
description: "Sem quebra. Esta propriedade especifica a propriedade \"unbreakable\" na caixa do objeto. Quando verdadeira, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true"
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() método

Sem quebra. Esta propriedade especifica a propriedade \"unbreakable\" na caixa do objeto. Quando verdadeira, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Ver também

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)