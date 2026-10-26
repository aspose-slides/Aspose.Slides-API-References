---
title: MathBlock()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathBlock.
type: docs
weight: 66
url: /pt/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() construtor

Inicializa uma nova instância da classe [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Observações

Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) construtor

Cria um novo bloco matemático e coloca o elemento especificado nele.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento matemático a ser colocado no bloco |

## Observações

Exemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) construtor

Cria um novo bloco matemático e coloca os elementos especificados nele.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elementos matemáticos a serem colocados no bloco |

## Observações

Exemplo: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [MathBlock](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)