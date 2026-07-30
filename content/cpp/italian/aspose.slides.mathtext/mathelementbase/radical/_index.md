---
title: Radical()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la radice matematica del grado fornito dall'argomento specificato.
type: docs
weight: 118
url: /it/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metodo

Specifica la radice matematica del grado fornito dall'argomento specificato.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argomento di Radical |

### Valore restituito

Nuova istanza del tipo [IMathRadical](../../imathradical/)

## Osservazioni

Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metodo

Specifica la radice matematica del grado fornito dall'argomento specificato.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argomento di Radical |

### Valore restituito

Nuova istanza del tipo [IMathRadical](../../imathradical/)

## Osservazioni

Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRadical](../../imathradical/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)