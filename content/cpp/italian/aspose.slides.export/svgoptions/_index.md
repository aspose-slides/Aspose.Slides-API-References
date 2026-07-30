---
title: SVGOptions
second_title: Riferimento API di Aspose.Slides for C++
description: Rappresenta un'opzione SVG.
type: docs
weight: 703
url: /it/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Rappresenta un'opzione SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Restituisce le impostazioni predefinite. Sola lettura [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Restituisce il carattere usato nel caso in cui il carattere sorgente non sia trovato. Legge [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se vero le parti ritagliate verranno rimosse, se falso saranno serializzate nel documento (il che può portare a un file più grande). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Determina se il testo 3D è disabilitato in SVG. Leggi **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Ottiene un valore che indica se il testo è renderizzato senza usare legature. Quando impostato a **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Disabilita la suddivisione dei gradienti FromCornerX e FromCenter. Leggi **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 non consente di definire rientri per i marker. [Aspose.Slides](../../aspose.slides/) il motore di scrittura SVG ha una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marker. Questa opzione disabilita tale comportamento. Leggi **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Determina un modo di gestire i caratteri caricati esternamente. Leggi [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Restituisce lo stile visuale del gradiente. Leggi [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornisce opzioni che controllano l'aspetto degli oggetti [Ink](../../aspose.slides.ink/) nel documento esportato. Sola lettura [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Determina la qualità della codifica JPEG. Leggi **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Restituisce il limite di risoluzione inferiore per la rasterizzazione dei metafile. Leggi **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Rappresenta il livello di compressione delle immagini. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Rappresenta un oggetto callback per salvare gli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Restituisce e imposta un'interfaccia callback che consente all'utente di controllare la conversione delle forme. Leggi [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Restituisce le impostazioni per la generazione del file SVG più semplice e più piccolo. Sola lettura [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Leggi **bool**. Il valore predefinito è **true**. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Leggi **bool**. Il valore predefinito è **false**. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Determina se il testo su una diapositiva sarà salvato come grafica. Leggi **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà abortito. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Restituisce le impostazioni per la generazione del file SVG più accurata. Sola lettura [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa l'istruzione C# lock() di blocco. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonaggio di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato. Scrive [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se vero le parti ritagliate verranno rimosse, se falso saranno serializzate nel documento (il che può portare a un file più grande). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Determina se il testo 3D è disabilitato in SVG. Scrivi **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Imposta un valore che indica se il testo è renderizzato senza usare legature. Quando impostato a **true**, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Disabilita la suddivisione dei gradienti FromCornerX e FromCenter. Scrivi **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 non consente di definire rientri per i marker. [Aspose.Slides](../../aspose.slides/) il motore di scrittura SVG ha una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marker. Questa opzione disattiva tale comportamento. Scrivi **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Determina un modo di gestire i caratteri caricati esternamente. Scrivi [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Imposta lo stile visuale del gradiente. Scrivi [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Determina la qualità della codifica JPEG. Scrivi **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Scrivi **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Rappresenta il livello di compressione delle immagini. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Rappresenta un oggetto callback per salvare gli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Restituisce e imposta un'interfaccia callback che consente all'utente di controllare la conversione delle forme. Scrivi [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Scrivi **bool**. Il valore predefinito è **true**. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Scrivi **bool**. Il valore predefinito è **false**. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Determina se il testo su una diapositiva sarà salvato come grafica. Scrivi **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà abortito. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Inizializza una nuova istanza della classe [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Inizializza una nuova istanza della classe [SVGOptions](./) specificando l'oggetto controller di incorporamento del collegamento. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [SaveOptions](../saveoptions/)
* Classe [ISVGOptions](../isvgoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)