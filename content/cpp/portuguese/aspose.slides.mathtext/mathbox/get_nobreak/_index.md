---
title: get_NoBreak()
second_title: Referência da API do Aspose.Slides para C++
description: "Sem quebra Esta propriedade especifica a propriedade \"unbreakable\" na caixa de objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true"
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() método

Sem quebra Esta propriedade especifica a propriedade \"unbreakable\" na caixa de objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Ver Também

* Classe [MathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)