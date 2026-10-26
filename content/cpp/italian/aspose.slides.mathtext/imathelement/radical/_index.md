---
title: Radical()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la radice matematica del grado dato dall'argomento specificato.
type: docs
weight: 131
url: /it/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metodo

Specifica la radice matematica del grado dato dall'argomento specificato.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argomento della radice |

### Valore di ritorno

Nuova istanza del tipo [IMathRadical](../../imathradical/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metodo

Specifica la radice matematica del grado dato dall'argomento specificato.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argomento della radice |

### Valore di ritorno

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
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)