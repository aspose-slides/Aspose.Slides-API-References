---
title: CreateMathBlock()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un blocco matematico
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() method

Crea un blocco matematico

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Valore di ritorno

nuovo blocco matematico

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method

Crea un blocco matematico e inserisci l'elemento al suo interno

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un elemento matematico |

### Valore di ritorno

nuovo blocco matematico

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method

Crea un blocco matematico e inserisci gli elementi al suo interno

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementi matematici |

### Valore di ritorno

nuovo blocco matematico

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockFactory](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)