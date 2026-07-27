---
title: MathPhantom()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathPhantom usando o elemento matemático base especificado.
type: docs
weight: 144
url: /pt/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) construtor

Inicializa uma nova instância da classe [MathPhantom](../) usando o elemento matemático base especificado.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O [IMathElement](../../imathelement/) base cuja visibilidade e layout serão controlados pelo fantasma. Este elemento define o conteúdo que pode ser ocultado ou exibido, enquanto ainda afeta o alinhamento geométrico da matemática ao redor. |

## Observações

O elemento fantasma é usado para reservar ou suprimir o espaço visual de sua expressão base sem necessariamente exibí-lo. Corresponde ao elemento OMML **<m:phant>**. 

Exemplo: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathPhantom](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)