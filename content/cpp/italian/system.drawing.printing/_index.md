---
title: "System::Drawing::Printing"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 521
url: /it/system.drawing.printing/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Margins](./margins/) | Rappresenta i margini di una pagina stampata. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PageSettings](./pagesettings/) | Rappresenta le impostazioni di una pagina stampata. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PaperSize](./papersize/) | Specifica la dimensione di un foglio di carta. |
| [PrintController](./printcontroller/) | Controlla come viene stampato un documento, quando si stampa da un'applicazione Forms [Windows](../system.windows/). Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PrintDocument](./printdocument/) | Sposta l'output a una stampante, quando si stampa da un'applicazione Forms [Windows](../system.windows/). Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PrinterResolution](./printerresolution/) | Rappresenta la risoluzione di una stampante. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PrinterSettings](./printersettings/) | Rappresenta le impostazioni di una stampante. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PrintEventArgs](./printeventargs/) | Fornisce i dati per gli eventi BeginPrint e EndPrint. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [PrintPageEventArgs](./printpageeventargs/) | Fornisce i dati per l'evento PrintPage. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [QueryPageSettingsEventArgs](./querypagesettingseventargs/) | Fornisce i dati per l'evento QueryPageSettings. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [StandardPrintController](./standardprintcontroller/) | Specifica un controller di stampa che invia informazioni a una stampante. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |

## Enumerazioni

| Enum | Descrizione |
| --- | --- |
| [PaperKind](./paperkind/) | Specifica le dimensioni standard della carta. |
| [PrintAction](./printaction/) | Specifica un tipo di operazione di stampa. |
| [PrintRange](./printrange/) | Specifica quali pagine vengono stampate. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [PrintPageEventHandler](./printpageeventhandler/) | Un tipo di funzione che gestisce l'evento PrintPage. |
| [PrintEventHandler](./printeventhandler/) | Un tipo di oggetto funzione che gestisce gli eventi BeginPrint e EndPrint. |