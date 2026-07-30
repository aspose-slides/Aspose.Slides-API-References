---
title: MathRadical()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathRadical.
type: docs
weight: 53
url: /it/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) costruttore

Inizializza una nuova istanza della classe [MathRadical](../).

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Grado |
## Osservazioni

Esempio: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)