---
title: IPdfOptions
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.
type: docs
weight: 274
url: /it/aspose.slides.export/ipdfoptions/
---
## IPdfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con accesso utente. Vedi [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Restituisce un array di nomi di famiglie di caratteri definiti dall'utente che [Aspose.Slides](../../aspose.slides/) dovrebbe considerare comuni. Leggi [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | Applica il colore trasparente specificato a un'immagine se **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione minore del documento PDF risultante. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | Livello di conformità desiderato per il documento PDF generato. Leggi [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Restituisce il carattere usato nel caso in cui il carattere sorgente non sia trovato. Legge [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | True per disegnare una cornice nera attorno a ogni diapositiva. Leggi **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. Leggi **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | True per incorporare i font TrueType per i caratteri ASCII 32-127. [Fonts](../../aspose.slides/fonts/) per i codici di carattere superiori a 127 sono sempre incorporati. Leggi **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Restituisce lo stile visivo del gradiente. Leggi [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Ottiene il colore trasparente dell'immagine. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Fornisce opzioni che controllano l'aspetto degli oggetti [Ink](../../aspose.slides.ink/) nel documento esportato. Solo lettura [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | Restituisce un valore che determina la qualità delle immagini JPEG nel documento PDF. Leggi **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Impostazione della password utente per proteggere il documento PDF. Leggi [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per certi font. Leggi **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. Leggi **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Leggi **bool**. Il valore predefinito è **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Ottiene la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | Restituisce un valore che determina la risoluzione delle immagini nel documento PDF. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale del documento. Leggi [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Restituisce un oggetto che riceve avvisi e decide se il processo di caricamento continuare o essere interrotto. Leggi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'object rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e consente la costruzione di copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e consente la costruzione di copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con accesso utente. Vedi [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Imposta un array di nomi di famiglie di caratteri definiti dall'utente che [Aspose.Slides](../../aspose.slides/) dovrebbe considerare comuni. Scrivi [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | Applica il colore trasparente specificato a un'immagine se **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su **bool**.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione minore del documento PDF risultante. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | Livello di conformità desiderato per il documento PDF generato. Scrivi [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato. Scrive [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | True per disegnare una cornice nera attorno a ogni diapositiva. Scrivi **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. Scrivi **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | True per incorporare i font TrueType per i caratteri ASCII 32-127. [Fonts](../../aspose.slides/fonts/) per i codici di carattere superiori a 127 sono sempre incorporati. Scrivi **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Imposta lo stile visivo del gradiente. Scrivi [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Imposta il colore trasparente dell'immagine. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | Imposta un valore che determina la qualità delle immagini JPEG nel documento PDF. Scrivi **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Impostazione della password utente per proteggere il documento PDF. Scrivi [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font. Scrivi **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | True per convertire tutti i metafile usati in una presentazione in immagini PNG. Scrivi **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | Imposta un valore che determina la risoluzione delle immagini nel documento PDF. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale del documento. Scrivi [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuare o essere interrotto. Scrivi [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ISaveOptions](../isaveoptions/)
* Spazio dei nomi [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)