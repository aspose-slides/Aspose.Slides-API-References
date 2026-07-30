---
title: CreateMathematicalText()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea elemento di testo matematico vuoto
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() method


Crea elemento di testo matematico vuoto

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Valore di ritorno

nuovo Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) method


Crea elemento di testo matematico con il valore specificato

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathSymbol | char16_t | singolo simbolo da usare come valore di testo |

### Valore di ritorno

nuovo Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) method


Crea elemento di testo matematico vuoto con il valore specificato

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |

### Valore di ritorno

nuovo Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method


Crea elemento di testo matematico vuoto con il valore specificato e le proprietà di formattazione

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | impostazioni di formato del testo |

### Valore di ritorno

nuovo Mathematical Text

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathematicalText](../../imathematicaltext/)
* Classe [MathematicalTextFactory](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)