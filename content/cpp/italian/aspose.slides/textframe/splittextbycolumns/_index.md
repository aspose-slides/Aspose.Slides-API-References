---
title: SplitTextByColumns()
second_title: Riferimento API di Aspose.Slides per C++
description: Divide il contenuto di testo dell'ITextFrame in un array di stringhe, dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame.
type: docs
weight: 144
url: /it/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metodo


Divide il contenuto di testo del [ITextFrame](../../itextframe/) in un array di stringhe, 

 dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Valore di ritorno

Un array di stringhe, dove ogni stringa rappresenta il contenuto di testo di una colonna specifica 

 nel [ITextFrame](../../itextframe/).
## Osservazioni



Se il frame di testo non contiene più colonne, l'array restituito avrà un unico elemento 

 contenente l'intero testo. 

 Le colonne vuote saranno rappresentate come stringhe vuote nell'array. 

Il seguente esempio dimostra come utilizzare [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Ottieni la prima forma sulla diapositiva e castala a ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Dividi il contenuto del frame di testo in colonne
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Stampa il testo di ogni colonna nella console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [TextFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)