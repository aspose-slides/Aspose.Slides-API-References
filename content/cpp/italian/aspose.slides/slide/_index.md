---
title: Slide
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una diapositiva in una presentazione.
type: docs
weight: 5175
url: /it/aspose.slides/slide/
---
## Slide classe

Rappresenta una diapositiva in una presentazione.

```cpp
class Slide : public Aspose::Slides::BaseSlide,
              public Aspose::Slides::ISlide
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Restituisce un tema efficace per questa diapositiva. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Determina se le due istanze [IBaseSlide](../ibaseslide/) sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e ai contenuti statici. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori di identificatori unici, ad esempio SlideId, e dei contenuti dinamici, ad esempio il valore della data corrente in Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Restituisce lo sfondo della diapositiva. Solo lettura [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Restituisce il controllo ActiveX all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Restituisce la raccolta di controlli ActiveX su una diapositiva. Solo lettura [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Restituisce i dati personalizzati della diapositiva. Solo lettura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Restituisce il gestore HeaderFooter della diapositiva. Solo lettura [ISlideHeaderFooterManager](../islideheaderfootermanager/). |
| **bool** [get_Hidden](./get_hidden/)() override | Determina se la diapositiva specificata è nascosta durante una presentazione. Lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() override | Restituisce la diapositiva di layout per la diapositiva corrente. Lettura [ILayoutSlide](../ilayoutslide/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | Restituisce il nome di una diapositiva. Lettura [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() override | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla. Solo lettura [INotesSlideManager](../inotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | Restituisce l'interfaccia [IPresentation](../ipresentation/). Solo lettura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Restituisce la forma all'indice specificato. Solo lettura [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Restituisce le forme di una diapositiva. Solo lettura [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Restituisce la diapositiva base. Solo lettura [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Restituisce l'ID di una diapositiva. Solo lettura **uint32_t**. |
| **int32_t** [get_SlideNumber](./get_slidenumber/)() override | Restituisce il numero di una diapositiva. L'indice della diapositiva nella collezione [Presentation::get_Slides()](../presentation/get_slides/) è sempre uguale a SlideNumber - Presentation::get(set)_FirstSlideNumber. Lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. Solo lettura [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Restituisce il gestore del tema sovrascrivente. Solo lettura [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Restituisce l'oggetto della timeline di animazione. Solo lettura [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) override | Restituisce un oggetto Thumbnail Image con ridimensionamento personalizzato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) override | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) override | Restituisce un oggetto immagine tiff Thumbnail con i parametri specificati. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | Restituisce un oggetto Thumbnail Image. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | Restituisce un oggetto Thumbnail Image con ridimensionamento personalizzato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) override | Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia costruttiva delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnamento. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia costruttiva delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| void [Remove](./remove/)() override | Rimuove la diapositiva dalla presentazione. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [Reset](./reset/)() override | Reimposta posizione, dimensione e formattazione di ogni forma che ha un prototipo su [LayoutSlide](../layoutslide/). |
| void [set_Hidden](./set_hidden/)(**bool**) override | Determina se la diapositiva specificata è nascosta durante una presentazione. Scrivi **bool**. |
| void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Imposta la diapositiva di layout per la diapositiva corrente. Scrivi [ILayoutSlide](../ilayoutslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | Imposta il nome di una diapositiva. Scrivi [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Scrivi **bool**. |
| void [set_SlideNumber](./set_slidenumber/)(**int32_t**) override | Restituisce il numero di una diapositiva. L'indice della diapositiva nella collezione [Presentation::get_Slides()](../presentation/get_slides/) è sempre uguale a SlideNumber - Presentation::get(set)_FirstSlideNumber. Scrivi **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a weak pointer (piuttosto che shared). Consente di passare i puntatori nei contenitori a modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva il contenuto della diapositiva come file EMF. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva il contenuto della diapositiva come file SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva il contenuto della diapositiva come file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [BaseSlide](../baseslide/)
* Classe [ISlide](../islide/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)