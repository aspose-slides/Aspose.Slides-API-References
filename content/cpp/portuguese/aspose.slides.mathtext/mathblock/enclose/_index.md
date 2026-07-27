---
title: Enclose()
second_title: Referência da API Aspose.Slides for C++
description: Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres, como enquadramento
type: docs
weight: 222
url: /pt/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) método


Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres, como enquadramento

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |

### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os caracteres especificados como enquadramento

## Observações



Exemplo: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) método


Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros, como enquadramento e delimita com um caractere separador

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |
| separatorCharacter | char16_t | Caractere separador |

### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os caracteres especificados como enquadramento e delimitador

## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)