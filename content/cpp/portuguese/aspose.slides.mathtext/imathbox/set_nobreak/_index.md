---
title: set_NoBreak()
second_title: Referência da API Aspose.Slides para C++
description: "Sem quebra. Esta propriedade especifica a propriedade \"unbreakable\" na caixa de objeto. Quando true, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true"
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) método

Sem quebra. Esta propriedade especifica a propriedade "unbreakable" na caixa de objeto. Quando true, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## Veja Também

* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)