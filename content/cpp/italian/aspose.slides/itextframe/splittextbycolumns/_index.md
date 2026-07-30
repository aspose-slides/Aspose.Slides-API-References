---
title: SplitTextByColumns()
second_title: Riferimento API di Aspose.Slides per C++
description: Dividi il contenuto di testo dell'ITextFrame in un array di stringhe, dove ogni elemento corrisponde a una colonna di testo separata all'interno del riquadro.
type: docs
weight: 118
url: /it/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metodo

Dividi il contenuto di testo del [ITextFrame](../) in un array di stringhe,

 dove ogni elemento corrisponde a una colonna di testo separata all'interno del riquadro.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### Valore di ritorno

Un array di stringhe, dove ogni stringa rappresenta il contenuto di testo di una colonna specifica

 nel [ITextFrame](../).
## Osservazioni

Se il riquadro di testo non contiene più colonne, l'array restituito avrà un solo elemento

 contenente il testo completo.

 Empty columns will be represented as empty strings in the array.

Il seguente esempio dimostra come utilizzare [ITextFrame::SplitTextByColumns](./):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Ottieni la prima forma nella diapositiva e convertila in ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Dividi il contenuto del riquadro di testo in colonne
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Stampa il testo di ogni colonna sulla console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [ITextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)