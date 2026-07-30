---
title: IPictureFillFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta uno stile di riempimento con immagine.
type: docs
weight: 3225
url: /it/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe


Rappresenta uno stile di riempimento con immagine.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Comprimi l'immagine riducendone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Comprimi l'immagine riducendone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Elimina le aree ritagliate del riempimento [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Restituisce il numero di percentuali di altezza reale dell'immagine che vengono ritagliate nella parte inferiore dell'immagine. Leggi **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Restituisce il numero di percentuali di larghezza reale dell'immagine che vengono ritagliate a sinistra dell'immagine. Leggi **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Restituisce il numero di percentuali di larghezza reale dell'immagine che vengono ritagliate a destra dell'immagine. Leggi **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Restituisce il numero di percentuali di altezza reale dell'immagine che vengono ritagliate nella parte superiore dell'immagine. Leggi **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Restituisce i dpi utilizzati per riempire un'immagine. Leggi **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Restituisce l'immagine. Solo lettura [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Restituisce la modalità di riempimento dell'immagine. Leggi [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Restituisce il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Leggi **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Restituisce il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Leggi **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Restituisce il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Leggi **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Restituisce il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Leggi **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Restituisce come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di inizio del motivo della trama e il modo in cui si ripete sulla forma. Leggi [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Capovolge la tessera della trama lungo l'asse orizzontale, verticale o entrambi. Leggi [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Restituisce lo spostamento orizzontale della trama dall'origine della forma in punti. Un valore positivo sposta la trama a destra, mentre un valore negativo la sposta a sinistra. Leggi **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Restituisce lo spostamento verticale della trama dall'origine della forma in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Leggi **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Restituisce la scala orizzontale del riempimento della trama come percentuale. Leggi **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Restituisce la scala verticale del riempimento della trama come percentuale. Leggi **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiama direttamente o utilizza l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Imposta il numero di percentuali di altezza reale dell'immagine che vengono ritagliate nella parte inferiore dell'immagine. Scrivi **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Imposta il numero di percentuali di larghezza reale dell'immagine che vengono ritagliate a sinistra dell'immagine. Scrivi **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Imposta il numero di percentuali di larghezza reale dell'immagine che vengono ritagliate a destra dell'immagine. Scrivi **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Imposta il numero di percentuali di altezza reale dell'immagine che vengono ritagliate nella parte superiore dell'immagine. Scrivi **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Imposta i dpi utilizzati per riempire un'immagine. Scrivi **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Imposta la modalità di riempimento dell'immagine. Scrivi [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Scrivi **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Scrivi **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Scrivi **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa indica un'espansione. Scrivi **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Imposta come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di inizio del motivo della trama e il modo in cui si ripete sulla forma. Scrivi [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Capovolge la tessera della trama lungo l'asse orizzontale, verticale o entrambi. Scrivi [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Imposta lo spostamento orizzontale della trama dall'origine della forma in punti. Un valore positivo sposta la trama a destra, mentre un valore negativo la sposta a sinistra. Scrivi **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Imposta lo spostamento verticale della trama dall'origine della forma in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Scrivi **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Imposta la scala orizzontale del riempimento della trama come percentuale. Scrivi **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Imposta la scala verticale del riempimento della trama come percentuale. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizza smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizza smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o utilizza l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizza smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizza smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IFillParamSource](../ifillparamsource/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)