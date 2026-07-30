---
title: Bitmap
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un'immagine bitmap GDI+. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject() . Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.drawing/bitmap/
---
## Bitmap classe

Rappresenta un'immagine bitmap GDI+. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class Bitmap : public System::Drawing::Image
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Abilita la modalità di elaborazione dei pixel. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Crea un nuovo oggetto [Bitmap](./) a partire dall'immagine esistente specificata. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Crea un nuovo oggetto [Bitmap](./) a partire dallo stream specificato. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Crea un nuovo oggetto [Bitmap](./) a partire dal file specificato. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Crea un nuovo oggetto [Bitmap](./) a partire dal file specificato. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Crea un nuovo oggetto [Bitmap](./) che rappresenta un'immagine bitmap con la larghezza, altezza, formato dei pixel e dati dei pixel specificati. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Crea un nuovo oggetto [Bitmap](./) a partire dall'immagine esistente specificata, ridimensionata alla dimensione specificata. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Crea un nuovo oggetto [Bitmap](./) a partire dall'immagine esistente specificata con larghezza e altezza ridimensionate ai valori specificati. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Crea una copia dell'oggetto corrente. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Crea un oggetto [Bitmap](./) che rappresenta una copia di una regione dell'immagine bitmap rappresentata dall'oggetto corrente. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Crea un oggetto [Bitmap](./) che rappresenta una copia di una regione dell'immagine bitmap rappresentata dall'oggetto corrente. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Calcola il valore hash SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Crea una copia dell'immagine bitmap specificata con il formato dei pixel modificato a Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Rilascia tutte le risorse acquisite dall'oggetto corrente. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Disabilita la modalità di elaborazione dei pixel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo reference nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali, anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Crea un oggetto [Image](../image/) a partire dal file specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Crea un oggetto [Bitmap](./) a partire dal bitmap GDI specificato. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Crea un oggetto [Image](../image/) a partire dallo stream specificato. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Restituisce una combinazione bitwise dei valori enum ImageFlags che rappresentano gli attributi dell'immagine. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Restituisce un array di GUID che rappresentano le dimensioni dei frame all'interno dell'immagine rappresentata dall'oggetto corrente. |
| int [get_Height](./get_height/)() const override | Restituisce l'altezza dell'immagine in pixel. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Restituisce la risoluzione orizzontale dell'immagine rappresentata dall'oggetto corrente in pixel per pollice. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Restituisce la paletta di colori usata dall'immagine rappresentata dall'oggetto corrente. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Restituisce il formato dei pixel dell'immagine rappresentata dall'oggetto corrente. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Ottiene gli ID degli elementi di proprietà memorizzati in questa immagine. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Ottiene tutti gli elementi di proprietà (pezzi di metadati) memorizzati in questa immagine. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Restituisce il formato file dell'immagine rappresentata dall'oggetto corrente. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Restituisce un oggetto [Size](../size/) che rappresenta la larghezza e l'altezza dell'immagine in pixel. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Ottiene un oggetto che fornisce dati aggiuntivi sull'immagine. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Restituisce la risoluzione verticale dell'immagine rappresentata dall'oggetto corrente in pixel per pollice. |
| int [get_Width](./get_width/)() const override | Restituisce la larghezza dell'immagine in pixel. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Restituisce i limiti dell'immagine nelle unità di misura specificate. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Restituisce il numero di frame della dimensione di frame specificata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Crea un oggetto bitmap GDI a partire dal bitmap rappresentato dall'oggetto corrente. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Restituisce il colore del pixel specificato. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Restituisce il numero di bit usati per rappresentare la profondità di colore nel formato pixel specificato. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Restituisce un puntatore grezzo all'oggetto SkBitmap sottostante. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Ottiene una miniatura per questo oggetto [System::Drawing::Image](../image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Determina se il formato pixel specificato contiene informazioni alfa. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Restituisce se il formato originale è una multi-immagine. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement C# bloccante. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Blocca un [Bitmap](./) nella memoria di sistema. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Blocca un [Bitmap](./) nella memoria di sistema. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Cambia il colore di tutti i pixel con il colore specificato in trasparente. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| void [PremultipleColors](./premultiplecolors/)() | Effettua il premoltiplicazione dei colori dei pixel dell'immagine rappresentata dall'oggetto corrente. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Ruota l'immagine di un multiplo di 90 gradi e la capovolge. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Salva l'immagine rappresentata dall'oggetto corrente nel file specificato in formato PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Salva l'immagine rappresentata dall'oggetto corrente nel file specificato nel formato specificato. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Salva l'immagine rappresentata dall'oggetto corrente nello stream specificato nel formato specificato. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Salva l'immagine rappresentata dall'oggetto corrente nel file specificato usando il codificatore e i parametri di codifica specificati. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Salva l'immagine rappresentata dall'oggetto corrente nello stream specificato usando il codificatore e i parametri di codifica specificati. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Aggiunge un frame al file o stream specificato in una chiamata precedente al metodo [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Aggiunge un frame al file o stream specificato in una chiamata precedente al metodo [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Seleziona il frame specificato. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Imposta la paletta di colori usata dall'immagine rappresentata dall'oggetto corrente. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Imposta un oggetto che fornisce dati aggiuntivi sull'immagine. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Imposta il colore del pixel specificato nell'immagine bitmap rappresentata dall'oggetto corrente. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Imposta la risoluzione dell'immagine. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Sblocca il bitmap specificato dalla memoria di sistema. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Image](../image/)
* Spazio dei nomi [System::Drawing](../)
* Library [Aspose.Slides](../../)