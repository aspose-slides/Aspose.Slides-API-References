---
title: PdfOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.
type: docs
weight: 573
url: /it/aspose.slides.export/pdfoptions/
---
## PdfOptions classe


Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. Vedi [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Restituisce un array di nomi di famiglie di caratteri definiti dall'utente che [Aspose.Slides](../../aspose.slides/) dovrebbe considerare comuni. Leggi [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Applica il colore trasparente specificato a un'immagine se **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato a **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Livello di conformità desiderato per il documento PDF generato. Leggi [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Restituisce il carattere utilizzato nel caso in cui il carattere di origine non sia trovato. Legge [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Vero per disegnare una cornice nera attorno a ogni diapositiva. Leggi **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. Leggi **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Determina se [Aspose.Slides](../../aspose.slides/) incorporerà i font comuni per il testo ASCII (intervallo codici 33..127). [Fonts](../../aspose.slides/fonts/) per i codici carattere superiori a 127 sono sempre incorporati. L'elenco dei font comuni include i 14 font di base del PDF e font aggiuntivi specificati dall'utente. Leggi **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Restituisce lo stile visivo del gradiente. Leggi [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Ottiene il colore trasparente dell'immagine. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Leggi **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornisce opzioni che controllano l'aspetto degli oggetti [Ink](../../aspose.slides.ink/) nel documento esportato. Solo lettura [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Restituisce un valore che determina la qualità delle immagini JPEG nel documento PDF. Leggi **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Impostazione della password utente per proteggere il documento PDF. Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di progresso in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultato per alcuni font. Leggi **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Vero per convertire tutti i metafile usati in una presentazione in immagini PNG. Leggi **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specifica se il documento generato deve includere diapositive nascoste o no. Il valore predefinito è **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Restituisce un valore che determina la risoluzione delle immagini nel documento PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale nel documento. Leggi [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Restituisce o imposta un oggetto che riceve avvertimenti e decide se il processo di caricamento continuerà o sarà interrotto. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la copia di costruttori delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la copia di costruttori delle subclassi. |
|  [PdfOptions](./pdfoptions/)() | Costruttore predefinito. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. Vedi [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Imposta un array di nomi di famiglie di font definiti dall'utente che [Aspose.Slides](../../aspose.slides/) dovrebbe considerare comuni. Scrivi [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Applica il colore trasparente specificato a un'immagine se **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato a **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Livello di conformità desiderato per il documento PDF generato. Scrivi [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Imposta il font usato nel caso in cui il font di origine non sia trovato. Scrive [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Vero per disegnare una cornice nera attorno a ogni diapositiva. Scrivi **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. Scrivi **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Determina se [Aspose.Slides](../../aspose.slides/) incorporerà i font comuni per il testo ASCII (intervallo codici 33..127). [Fonts](../../aspose.slides/fonts/) per i codici carattere superiori a 127 sono sempre incorporati. L'elenco dei font comuni include i 14 font di base del PDF e font aggiuntivi specificati dall'utente. Scrivi **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Imposta lo stile visivo del gradiente. Scrivi [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Imposta il colore trasparente dell'immagine. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Imposta un valore che determina la qualità delle immagini JPEG nel documento PDF. Scrivi **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Impostazione della password utente per proteggere il documento PDF. Scrivi [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di progresso in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultato per alcuni font. Scrivi **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Vero per convertire tutti i metafile usati in una presentazione in immagini PNG. Scrivi **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specifica se il documento generato deve includere diapositive nascoste o no. Il valore predefinito è **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Imposta un valore che determina la risoluzione delle immagini nel documento PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale nel documento. Scrivi [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Restituisce o imposta un oggetto che riceve avvertimenti e decide se il processo di caricamento continuerà o sarà interrotto. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni



Il seguente esempio mostra come convertire PowerPoint in PDF con opzioni personalizzate. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instanzia la classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Imposta la qualità Jpeg
pdfOptions->set_JpegQuality(90);
// Imposta il comportamento per i metafile
pdfOptions->set_SaveMetafilesAsPng(true);
// Imposta il livello di compressione del testo
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Definisce lo standard PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Salva la presentazione come PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Il seguente esempio mostra come convertire PowerPoint in PDF con diapositive nascoste. 
```cpp
// Instanzia una classe Presentation che rappresenta un file PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instanzia la classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Aggiunge diapositive nascoste
pdfOptions->set_ShowHiddenSlides(true);
// Salva la presentazione come PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Il seguente esempio mostra come convertire PowerPoint in PDF protetto da password. 
```cpp
// Instanzia un oggetto Presentation che rappresenta un file PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Imposta la password PDF e i permessi di accesso
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Salva la presentazione come PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Il seguente esempio mostra come convertire PowerPoint in PDF con note. 
```cpp
// Instanzia un oggetto Presentation che rappresenta un file di presentazione
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Vedi anche

* Classe [SaveOptions](../saveoptions/)
* Classe [IPdfOptions](../ipdfoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)