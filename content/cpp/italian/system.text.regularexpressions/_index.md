---
title: "System::Text::RegularExpressions"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 989
url: /it/system.text.regularexpressions/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Capture](./capture/) | Risultato di una singola corrispondenza di sottoespressione. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [CaptureCollection](./capturecollection/) | Elenco di catture effettuate da un singolo gruppo di cattura. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [Group](./group/) | Risultato di una corrispondenza effettuata da un singolo gruppo di cattura. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [GroupCollection](./groupcollection/) | Elenco dei gruppi di cattura in una singola corrispondenza. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) puntatore di collezione. Questo tipo è un puntatore per gestire l'eliminazione di altri oggetti. Dovrebbe essere allocato sullo stack e passato alle funzioni sia per valore che per riferimento costante. |
| [Match](./match/) | Corrispondenza [Single](../system/single/) di espressione regolare su stringa. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [MatchCollection](./matchcollection/) | Collezione di corrispondenze ottenute applicando ripetutamente l'espressione regolare a una stringa. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
| [Regex](./regex/) | Espressione regolare che segue una sintassi simile a C#. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento. |
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Wrapper per contenere la classe MatchHolder senza includerla, oltre a PCRE2. |
## Enum

| Enum | Descrizione |
| --- | --- |
| [RegexOptions](./regexoptions/) | Opzioni [Regex](./regex/). |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [UStringPtr](./ustringptr/) | UnicodeString condivisa per evitare copie. |
| [CapturePtr](./captureptr/) | Puntatore a un singolo oggetto di cattura. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Puntatore a una collezione di cattura. |
| [GroupPtr](./groupptr/) | Puntatore a un gruppo. |
| [RegexPtr](./regexptr/) | Puntatore [Regex](./regex/). |
| [MatchPtr](./matchptr/) | Puntatore [Match](./match/). |
| [MatchCollectionPtr](./matchcollectionptr/) | Puntatore della collezione [Match](./match/). |
| [MatchEvaluator](./matchevaluator/) | Tipo delegate per valutare la corrispondenza. |