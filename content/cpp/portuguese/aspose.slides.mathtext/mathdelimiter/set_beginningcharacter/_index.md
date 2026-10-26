---
title: set_BeginningCharacter()
second_title: Referência da API Aspose.Slides para C++
description: "Delimiter Beginning Character especifica o caractere delimitador de início, ou de abertura. Delimitadores matemáticos são caracteres de contorno, como parênteses, colchetes e chaves. O padrão: '('."
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) método

Delimiter Beginning Character especifica o caractere delimitador de início, ou abertura. Delimitadores matemáticos são caracteres que cercam, como parênteses, colchetes e chaves. O padrão: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```


## Ver também

* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)