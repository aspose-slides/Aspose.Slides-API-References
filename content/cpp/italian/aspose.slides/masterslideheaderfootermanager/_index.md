---
title: MasterSlideHeaderFooterManager
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il gestore che controlla il comportamento del segnaposto piè di pagina della diapositiva master, dei segnaposti data-ora, numero di pagina e di tutti i segnaposti figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.
type: docs
weight: 4499
url: /it/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager classe

Rappresenta il gestore che contiene il comportamento del segnaposto piè di pagina della diapositiva master, data-ora, numero di pagina e tutti i segnaposti figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Restituisce il valore che indica la presenza di un segnaposto data-ora. Leggi **bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Restituisce il valore che indica la presenza di un segnaposto piè di pagina. Leggi **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Restituisce il valore che indica la presenza di un segnaposto numero di pagina. Leggi **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo effettivo dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Imposta il testo nel segnaposto data-ora della diapositiva master e in tutti i segnaposti data-ora figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Modifica la visibilità del segnaposto data-ora della diapositiva master e di tutti i segnaposti data-ora figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Imposta il testo nel segnaposto data-ora della diapositiva. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Modifica la visibilità del segnaposto data-ora della diapositiva. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Imposta il testo nel segnaposto piè di pagina della diapositiva master e in tutti i segnaposti piè di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Modifica la visibilità del segnaposto piè di pagina della diapositiva master e di tutti i segnaposti piè di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Imposta il testo nel segnaposto piè di pagina della diapositiva. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Modifica la visibilità del segnaposto piè di pagina della diapositiva. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Modifica la visibilità del segnaposto numero di pagina della diapositiva master e di tutti i segnaposti numero di pagina figlio. I segnaposti figlio indicano segnaposti contenuti nelle diapositive layout dipendenti e nelle diapositive dipendenti. Le diapositive layout dipendenti e le diapositive utilizzano e dipendono dalla diapositiva master. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Modifica la visibilità del segnaposto numero di pagina della diapositiva. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece puntatori intelligenti o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece puntatori intelligenti o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti debole. Non dovrebbe essere chiamato direttamente; utilizzare invece puntatori intelligenti o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti debole. Non dovrebbe essere chiamato direttamente; utilizzare invece puntatori intelligenti o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Classe [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)