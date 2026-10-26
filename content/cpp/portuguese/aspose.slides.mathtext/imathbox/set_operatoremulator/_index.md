---
title: set_OperatorEmulator()
second_title: Referência da API Aspose.Slides para C++
description: "Emulador de Operador. Quando true, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos combinam para formar um operador, como '=='. Valor padrão: false"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) method


Emulador de Operador. Quando true, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos combinam para formar um operador, como '=='. Valor padrão: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Ver Também

* Classe [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)