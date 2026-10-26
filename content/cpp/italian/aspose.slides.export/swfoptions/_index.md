---
title: SwfOptions
second_title: Riferimento API Aspose.Slides per C++
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato Swf.
type: docs
weight: 742
url: /it/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti utilizzando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **bool** [get_Compressed](./get_compressed/)() override | Specifica se il documento SWF generato deve essere compresso o meno. Il valore predefinito è **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Restituisce il carattere usato nel caso il carattere sorgente non sia trovato. Legge [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Restituisce lo stile visivo del gradiente. Leggi [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Specifica la qualità delle immagini JPEG. Il valore predefinito è 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Immagine che verrà mostrata come logo nell'angolo in alto a destra del visualizzatore. L'immagine deve essere PNG 32x64 pixel, altrimenti il logo può essere visualizzato in modo errato. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Ottiene l'indirizzo hyperlink completo per un logo. Ha effetto solo se è specificato un [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Mostra/nascondi il pannello inferiore. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Mostra/nascondi il pulsante a schermo intero. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Mostra/nascondi il pannello sinistro. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Specifica se il bordo attorno alle pagine deve essere mostrato. Il valore predefinito è true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Mostra/nascondi il selettore di pagina. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Mostra/nascondi la sezione di ricerca. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Mostra/nascondi l'intero pannello superiore. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specifica se ignorare gli hyperlink con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). Questa proprietà non supporta l'assegnazione di oggetti di tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Avvia con il pannello sinistro aperto. Può essere sovrascritto nei flashvars. Il valore predefinito è false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Specifica se il documento SWF generato deve includere il visualizzatore di documenti integrato o meno. Il valore predefinito è **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiama direttamente o usa l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Specifica se il documento SWF generato deve essere compresso o meno. Il valore predefinito è **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Imposta il carattere usato nel caso il carattere sorgente non sia trovato. Scrive [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Imposta lo stile visivo del gradiente. Scrivi [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Specifica la qualità delle immagini JPEG. Il valore predefinito è 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Immagine che verrà mostrata come logo nell'angolo in alto a destra del visualizzatore. L'immagine deve essere PNG 32x64 pixel, altrimenti il logo può essere visualizzato in modo errato. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Imposta l'indirizzo hyperlink completo per un logo. Ha effetto solo se è specificato un [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Mostra/nascondi il pannello inferiore. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Mostra/nascondi il pulsante a schermo intero. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Mostra/nascondi il pannello sinistro. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Specifica se il bordo attorno alle pagine deve essere mostrato. Il valore predefinito è true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Mostra/nascondi il selettore di pagina. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Mostra/nascondi la sezione di ricerca. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Mostra/nascondi l'intero pannello superiore. Può essere sovrascritto nei flashvars. Il valore predefinito è true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specifica se ignorare gli hyperlink con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). Questa proprietà non supporta l'assegnazione di oggetti di tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Avvia con il pannello sinistro aperto. Può essere sovrascritto nei flashvars. Il valore predefinito è false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Specifica se il documento SWF generato deve includere il visualizzatore di documenti integrato o meno. Il valore predefinito è **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori in contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Costruttore predefinito. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiama direttamente o usa l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

Il seguente esempio mostra come convertire PowerPoint in SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Vedi anche

* Classe [SaveOptions](../saveoptions/)
* Classe [ISwfOptions](../iswfoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)