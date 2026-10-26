---
title: Enclose()
second_title: Referência da API Aspose.Slides para C++
description: Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros, como moldura e delimita com um caractere separador
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) método


Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros, como moldura e delimita com um caractere separador

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |
| separatorCharacter | char16_t | Caractere separador |

### Valor de Retorno

O elemento matemático do tipo [IMathDelimiter](../../imathdelimiter/) que inclui os caracteres especificados como moldura e delimitador
## Observações



Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)