---
title: Accent()
second_title: Aspose.Slides para C++ Referência da API
description: Define uma marca de acento (um caractere na parte superior deste elemento)
type: docs
weight: 196
url: /pt/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) método


Define um sinal de acento (um caractere na parte superior deste elemento)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| accentCharacter | char16_t | Caractere de acento. O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

### Valor de Retorno

Nova instância do tipo [IMathAccent](../../imathaccent/)
## Observações



Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)