---
title: Delimit()
second_title: Referência da API Aspose.Slides para C++
description: Delimita argumentos usando o caractere delimitador especificado
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) método

Delimita argumentos usando o caractere delimitador especificado

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| separatorCharacter | char16_t | caractere delimitador |

### Valor de Retorno

Este objeto após aplicar o caractere delimitador

## Observações



Exemplo: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)