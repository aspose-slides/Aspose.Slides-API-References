---
title: Enclose()
second_title: Referência da API Aspose.Slides para C++
description: Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) método

Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char16_t | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char16_t | Caractere final (geralmente colchete direito) |

### Valor de Retorno

Se *beginningCharacter* e *endingCharacter* são nulos, as propriedades correspondentes recebem valores apenas e nenhum novo objeto é criado (retorna esta instância). Caso contrário, retorna um novo elemento matemático do tipo Delimiter que inclui os caracteres especificados como moldura e esta instância de [MathDelimiter](../) enquadrada dentro.

## Observações



Exemplo: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)