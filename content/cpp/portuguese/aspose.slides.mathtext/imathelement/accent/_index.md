---
title: Accent()
second_title: Aspose.Slides para C++ Referência da API
description: Define um sinal de acento (um caractere na parte superior deste elemento)
type: docs
weight: 209
url: /pt/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) método


Define um sinal de acento (um caractere na parte superior deste elemento)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| accentCharacter | char16_t | Caractere de acento. O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

### Valor de retorno

Nova instância do tipo [IMathAccent](../../imathaccent/)
## Observações



Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathAccent](../../imathaccent/)
* Classe [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)