---
title: IHtml5Options
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le opzioni di esportazione HTML5.
type: docs
weight: 170
url: /it/aspose.slides.export/ihtml5options/
---
## IHtml5Options classe


Rappresenta le opzioni di esportazione HTML5.

```cpp
class IHtml5Options : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **bool** [get_AnimateShapes](./get_animateshapes/)() | Restituisce l'opzione di animazione delle forme. Lettura **bool**. |
| virtual **bool** [get_AnimateTransitions](./get_animatetransitions/)() | Restituisce l'opzione di animazione delle transizioni. Lettura **bool**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Restituisce il font usato nel caso il font sorgente non sia trovato. Legge [System::String](../../system/string/). |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Ottiene un valore che indica se il testo è renderizzato senza usare le legature. Quando impostato a **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a **false**. |
| virtual **bool** [get_EmbedImages](./get_embedimages/)() | Restituisce l'opzione di incorporamento delle immagini. Lettura **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Restituisce lo stile visivo del gradiente. Legge [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() | Determina dove devono essere archiviate le risorse esterne. Legge [System::String](../../system/string/). |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Rappresenta il livello di compressione delle immagini. Legge [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Rappresenta un oggetto callback per salvare gli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura **bool**. Il valore predefinito è **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Restituisce un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Legge [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_AnimateShapes](./set_animateshapes/)(**bool**) | Imposta l'opzione di animazione delle forme. Scrittura **bool**. |
| virtual void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) | Imposta l'opzione di animazione delle transizioni. Scrittura **bool**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Imposta il font usato nel caso il font sorgente non sia trovato. Scrive [System::String](../../system/string/). |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Imposta un valore che indica se il testo è renderizzato senza usare le legature. Quando impostato a **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a **false**. |
| virtual void [set_EmbedImages](./set_embedimages/)(**bool**) | Imposta l'opzione di incorporamento delle immagini. Scrittura **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Imposta lo stile visivo del gradiente. Scrive [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) | Determina dove devono essere archiviate le risorse esterne. Scrive [System::String](../../system/string/). |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Rappresenta il livello di compressione delle immagini. Scrive [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Rappresenta un oggetto callback per salvare gli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrittura **bool**. Il valore predefinito è **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Scrive [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-shapes-and-transitions.html", SaveFormat::Html5, options);
```




## Vedi anche

* Classe [ISaveOptions](../isaveoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)