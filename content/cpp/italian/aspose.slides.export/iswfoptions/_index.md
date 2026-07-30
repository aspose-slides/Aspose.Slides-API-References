---
title: ISwfOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato SWF.
type: docs
weight: 469
url: /it/aspose.slides.export/iswfoptions/
---
## ISwfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Specifica se il documento SWF generato deve essere compresso o meno. Il valore predefinito è **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Restituisce il carattere usato nel caso in cui il carattere sorgente non sia trovato. Legge [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Restituisce lo stile visivo del gradiente. Legge [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Specifica la qualità delle immagini JPEG. 

 Il valore predefinito è 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. 

 L'immagine dovrebbe essere un PNG di 32x64 pixel, altrimenti il logo potrebbe essere visualizzato in modo errato. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Ottiene l'indirizzo hyperlink completo per un logo. Ha effetto solo se è specificato un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Rappresenta un oggetto di callback per il salvataggio dei progressi in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Mostra/nasconde il pannello inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Mostra/nasconde il pulsante a schermo intero. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Mostra/nasconde il pannello sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Specifica se deve essere mostrato il bordo intorno alle pagine. Il valore predefinito è true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Mostra/nasconde il selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Mostra/nasconde la sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Mostra/nasconde l'intero pannello superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specifica se saltare i hyperlink con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina quando si esporta una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). Questa proprietà non supporta l'assegnazione di oggetti di tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Avvia con il pannello sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Specifica se il documento SWF generato deve includere il visualizzatore di documenti integrato o meno. Il valore predefinito è **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Restituisce un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà abortito. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e consente la copia di costruttori nelle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e consente la copia di costruttori nelle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Specifica se il documento SWF generato deve essere compresso o meno. Il valore predefinito è **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato. Scrive [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Abilita/disabilita il menu contestuale. Il valore predefinito è true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Imposta lo stile visivo del gradiente. Scrive [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Specifica la qualità delle immagini JPEG. 

 Il valore predefinito è 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. 

 L'immagine dovrebbe essere un PNG di 32x64 pixel, altrimenti il logo potrebbe essere visualizzato in modo errato. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Imposta l'indirizzo hyperlink completo per un logo. Ha effetto solo se è specificato un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Rappresenta un oggetto di callback per il salvataggio dei progressi in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Mostra/nasconde il pannello inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Mostra/nasconde il pulsante a schermo intero. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Mostra/nasconde il pannello sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Specifica se il bordo intorno alle pagine deve essere mostrato. Il valore predefinito è true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Mostra/nasconde il selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Mostra/nasconde la sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Mostra/nasconde l'intero pannello superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specifica se saltare gli hyperlink con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Imposta la modalità in cui le diapositive sono posizionate sulla pagina quando si esporta una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). Questa proprietà non supporta l'assegnazione di oggetti di tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Avvia con il pannello sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Specifica se il documento SWF generato deve includere il visualizzatore di documenti integrato o meno. Il valore predefinito è **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà abortito. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello a un weak pointer (piuttosto che shared). Consente di cambiare i puntatori nei container a modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ISaveOptions](../isaveoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)