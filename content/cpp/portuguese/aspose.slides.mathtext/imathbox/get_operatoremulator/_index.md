---
title: get_OperatorEmulator()
second_title: Referência da API Aspose.Slides para C++
description: "Operator Emulator. Quando verdadeiro, a caixa e seu conteúdo se comportam como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Operator Emulators são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false"
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() método

Operator Emulator. Quando verdadeiro, a caixa e seu conteúdo se comportam como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Os Operator Emulators são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Ver também

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)