---
title: PictureFillFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta uno stile di riempimento con immagine.
type: docs
weight: 4720
url: /it/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

Rappresenta uno stile di riempimento con immagine.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Comprimi l'immagine riducendo le sue dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente elimina anche le aree ritagliate. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Comprimi l'immagine riducendo le sue dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente elimina anche le aree ritagliate. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Elimina le aree ritagliate del riempimento [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Restituisce la percentuale dell'altezza reale dell'immagine che è ritagliata dal fondo dell'immagine. Lettura **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Restituisce la percentuale della larghezza reale dell'immagine che è ritagliata a sinistra dell'immagine. Lettura **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Restituisce la percentuale della larghezza reale dell'immagine che è ritagliata a destra dell'immagine. Lettura **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Restituisce la percentuale dell'altezza reale dell'immagine che è ritagliata dalla parte superiore dell'immagine. Lettura **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Restituisce i dpi utilizzati per riempire un'immagine. Lettura **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Restituisce l'immagine. Solo lettura [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Restituisce la modalità di riempimento immagine. Lettura [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Restituisce il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Lettura **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Restituisce il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Lettura **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Restituisce il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Lettura **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Restituisce il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Lettura **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Restituisce come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della texture e come si ripete sulla forma. Lettura [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Capovolge la tessera della texture attorno al suo asse orizzontale, verticale o entrambi. Lettura [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Restituisce lo spostamento orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso destra, mentre un valore negativo la sposta verso sinistra. Lettura **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Restituisce lo spostamento verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Lettura **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Restituisce la scala orizzontale per il riempimento texture come percentuale. Lettura **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Restituisce la scala verticale per il riempimento texture come percentuale. Lettura **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, semplicemente inizializza un nuovo oggetto e consente la copia dei costruttori delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, semplicemente inizializza un nuovo oggetto e consente la copia dei costruttori delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Imposta la percentuale dell'altezza reale dell'immagine che è ritagliata dal fondo dell'immagine. Scrittura **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Imposta la percentuale della larghezza reale dell'immagine che è ritagliata a sinistra dell'immagine. Scrittura **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Imposta la percentuale della larghezza reale dell'immagine che è ritagliata a destra dell'immagine. Scrittura **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Imposta la percentuale dell'altezza reale dell'immagine che è ritagliata dalla parte superiore dell'immagine. Scrittura **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Imposta i dpi utilizzati per riempire un'immagine. Scrittura **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Imposta la modalità di riempimento immagine. Scrittura [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Scrittura **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Scrittura **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Scrittura **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva indica un inset, mentre una negativa indica un outset. Scrittura **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Imposta come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della texture e come si ripete sulla forma. Scrittura [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Capovolge la tessera della texture attorno al suo asse orizzontale, verticale o entrambi. Scrittura [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Imposta lo spostamento orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso destra, mentre un valore negativo la sposta verso sinistra. Scrittura **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Imposta lo spostamento verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Scrittura **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Imposta la scala orizzontale per il riempimento texture come percentuale. Scrittura **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Imposta la scala verticale per il riempimento texture come percentuale. Scrittura **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)