---
title: CreateMathematicalText()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea elemento di testo matematico vuoto
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() metodo


Crea elemento di testo matematico vuoto

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```


### Valore di ritorno

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) metodo


Crea elemento di testo matematico con il valore specificato

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathSymbol | char16_t | singolo simbolo da usare come valore di testo |

### Valore di ritorno

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) metodo


Crea elemento di testo matematico vuoto con il valore specificato

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |

### Valore di ritorno

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metodo


Crea elemento di testo matematico vuoto con il valore specificato e le proprietà di formattazione

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | valore di testo |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | impostazioni di formato del testo |

### Valore di ritorno

new Mathematical Text

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathematicalText](../../imathematicaltext/)
* Classe [IMathematicalTextFactory](../)
* Classe [String](../../../system/string/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)