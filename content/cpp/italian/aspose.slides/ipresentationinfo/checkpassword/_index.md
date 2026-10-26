---
title: CheckPassword()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se una password è corretta per una presentazione protetta con password aperta.
type: docs
weight: 53
url: /it/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) metodo

Verifica se una password è corretta per una presentazione protetta con password aperta.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La password da verificare. |

### Valore di ritorno

True se la presentazione è protetta con password aperta e la password è corretta e false altrimenti.

## Osservazioni

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Quando la password è null o vuota, questo metodo restituisce false. 

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IPresentationInfo](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)