---
title: CreateMathBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un blocco matematico
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() metodo

Crea un blocco matematico

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Valore restituito

nuovo blocco matematico

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) metodo

Crea un blocco matematico e inserisce l'elemento al suo interno

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un elemento matematico |

### Valore restituito

nuovo blocco matematico

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) metodo

Crea un blocco matematico e inserisce gli elementi al suo interno

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | elementi matematici |

### Valore restituito

nuovo blocco matematico

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathBlockFactory](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)