---
title: Delimit()
second_title: Riferimento API di Aspose.Slides per C++
description: Delimita gli argomenti usando il carattere delimitatore specificato
type: docs
weight: 144
url: /it/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metodo


Delimita gli argomenti usando il carattere delimitatore specificato

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char16_t | carattere delimitatore |

### Valore di ritorno

Questo oggetto dopo l'applicazione del carattere delimitatore
## Osservazioni



Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)