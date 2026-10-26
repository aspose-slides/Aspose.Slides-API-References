---
title: CreateMathBlock()
second_title: Referência da API Aspose.Slides para C++
description: Criar um bloco matemático
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() method


Criar um bloco matemático

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### Valor de Retorno

novo bloco matemático

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method


Criar um bloco matemático e colocar o elemento nele

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Um elemento matemático |

### Valor de Retorno

novo bloco matemático

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method


Criar um bloco matemático e colocar elementos nele

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementos matemáticos |

### Valor de Retorno

novo bloco matemático

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathBlockFactory](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)