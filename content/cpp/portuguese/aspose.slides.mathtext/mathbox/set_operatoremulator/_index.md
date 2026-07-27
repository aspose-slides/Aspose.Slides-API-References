---
title: set_OperatorEmulator()
second_title: Referência da API Aspose.Slides para C++
description: "Emulador de Operador. Quando true, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) método

Emulador de Operador. Quando true, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Observações

Exemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Veja também

* Classe [MathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)