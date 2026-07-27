---
title: CreateMathBlock()
second_title: Referência da API Aspose.Slides para C++
description: Criar um bloco de matemática
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() método


Criar um bloco de matemática

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### Valor de retorno

novo bloco de matemática

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) método


Criar um bloco de matemática e colocar o elemento nele

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Um elemento matemático |

### Valor de retorno

novo bloco de matemática

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) método


Criar um bloco de matemática e colocar elementos nele

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementos matemáticos |

### Valor de retorno

novo bloco de matemática

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockFactory](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)