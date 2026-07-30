---
title: JoinBlock()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce un altro blocco matematico a questo
type: docs
weight: 196
url: /it/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) metodo

Unisce un altro blocco matematico a questo

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Il blocco da unire |

### Valore di ritorno

questo blocco matematico dopo l'unione
## Osservazioni



Esempio: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)