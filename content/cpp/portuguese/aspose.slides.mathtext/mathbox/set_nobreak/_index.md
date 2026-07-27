---
title: set_NoBreak()
second_title: Referência da API Aspose.Slides para C++
description: "Sem quebra Esta propriedade especifica a propriedade \"unbreakable\" na caixa de objeto. Quando true, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true"
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) método

Sem quebra Esta propriedade especifica a propriedade \"unbreakable\" na caixa de objeto. Quando true, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operadores que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## Veja também

* Classe [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)