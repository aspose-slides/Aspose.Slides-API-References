---
title: TiffOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato TIFF.
type: docs
weight: 768
url: /it/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata nel formato TIFF.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) è impostato su [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Leggi [BlackWhiteConversionMode](../blackwhiteconversionmode/). Il valore predefinito è [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Specifica il tipo di compressione. Leggi [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Restituisce il font usato nel caso il font di origine non sia trovato. Legge [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Specifica la risoluzione orizzontale in punti per pollice. Leggi **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Specifica la risoluzione verticale in punti per pollice. Leggi **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Restituisce lo stile visivo del gradiente. Leggi [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Specifica la dimensione di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata verranno calcolate in base al valore della dimensione della diapositiva della presentazione. Leggi [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornisce opzioni che controllano l'aspetto degli oggetti [Ink](../../aspose.slides.ink/) nel documento esportato. Solo lettura [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Specifica il formato pixel per le immagini generate. Leggi [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Rappresenta un oggetto callback per salvare aggiornamenti di progresso in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie per le subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, si limita a inizializzare un nuovo oggetto e consente la costruzione di copie per le subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) è impostato su [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) o [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Scrivi [BlackWhiteConversionMode](../blackwhiteconversionmode/). Il valore predefinito è [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Specifica il tipo di compressione. Scrivi [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Imposta il font usato nel caso il font di origine non sia trovato. Scrive [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Specifica la risoluzione orizzontale in punti per pollice. Scrivi **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Specifica la risoluzione verticale in punti per pollice. Scrivi **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Imposta lo stile visivo del gradiente. Scrivi [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Specifica la dimensione di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata verranno calcolate in base al valore della dimensione della diapositiva della presentazione. Scrivi [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Specifica il formato pixel per le immagini generate. Scrivi [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Rappresenta un oggetto callback per salvare aggiornamenti di progresso in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [TiffOptions](./tiffoptions/)() | Costruttore predefinito. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

L'esempio seguente mostra come convertire PowerPoint in TIFF con dimensione predefinita.  
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Salva la presentazione in un documento TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```  
L'esempio seguente mostra come convertire PowerPoint in TIFF con dimensione personalizzata.  
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Istanzia la classe TiffOptions
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Imposta il tipo di compressione
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Tipi di compressione
// Default - Specifica lo schema di compressione predefinito (LZW).
// None - Specifica nessuna compressione.
// CCITT3
// CCITT4
// LZW
// RLE
// La profondità dipende dal tipo di compressione e non può essere impostata manualmente.
// L'unità di risoluzione è sempre uguale a "2" (punti per pollice)
// Imposta i DPI dell'immagine
opts->set_DpiX(200);
opts->set_DpiY(100);
// Imposta la dimensione dell'immagine
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Salva la presentazione in TIFF con la dimensione dell'immagine specificata
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```  
L'esempio seguente mostra come convertire PowerPoint in TIFF con formato pixel dell'immagine personalizzato.  
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Salva la presentazione in TIFF con la dimensione dell'immagine specificata
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Vedi anche

* Classe [SaveOptions](../saveoptions/)
* Classe [ITiffOptions](../itiffoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)