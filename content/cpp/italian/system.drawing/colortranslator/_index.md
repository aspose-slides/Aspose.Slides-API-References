---
title: ColorTranslator
second_title: Riferimento API Aspose.Slides per C++
description: "Esegue traduzioni di colori. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject() . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 66
url: /it/system.drawing/colortranslator/
---
## ColorTranslator classe


Esegue traduzioni di colori. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o utilizzando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzioni. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class ColorTranslator
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Converte la rappresentazione colore HTML specificata nell'oggetto [Color](../color/) equivalente. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Converte il colore [Windows](../../system.windows/) specificato nell'oggetto [Color](../color/) equivalente. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Converte l'oggetto [Color](../color/) specificato nella rappresentazione stringa del colore HTML equivalente. |
## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)