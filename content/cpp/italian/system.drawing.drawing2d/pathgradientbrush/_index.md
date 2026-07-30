---
title: PathGradientBrush
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un pennello che riempie l'interno di un oggetto GraphicsPath con un gradiente. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 144
url: /it/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush classe


Rappresenta un pennello che riempie l'interno di un oggetto [GraphicsPath](../graphicspath/) con un gradiente. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarla alle funzioni come argomento.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crea una copia dell'oggetto corrente. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Non fa nulla. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri floating point in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri floating point in stile C# in cui due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | NON IMPLEMENTATO. |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | Restituisce un colore che si trova al centro del percorso riempito dall'oggetto corrente. |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | Ottiene il punto centrale del gradiente. |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | Ottiene il punto focale per il decadimento del gradiente. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Restituisce un valore che definisce un gradiente lineare multicolore. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | NON IMPLEMENTATO. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | Restituisce i colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](./) riempie. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Restituisce una copia di un oggetto [Matrix](../matrix/) che specifica le trasformazioni geometriche per il pennello rappresentato dall'oggetto corrente. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Restituisce la modalità di avvolgimento. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Moltiplica la matrice di trasformazione dell'oggetto corrente per la matrice specificata. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | Costruisce una nuova istanza della classe [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | Costruisce una nuova istanza della classe [PathGradientBrush](./). |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | Costruisce una nuova istanza della classe [PathGradientBrush](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [ResetTransform](./resettransform/)() | Reimposta la matrice di trasformazione dell'oggetto corrente affinché diventi una matrice identità. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Ruota la trasformazione geometrica locale dell'angolo specificato nell'ordine specificato. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Scala la trasformazione geometrica locale dei fattori specificati nell'ordine specificato. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Imposta una sfumatura che specifica fattori e posizioni dei colori di base per questo pennello. |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | Imposta un colore che si trova al centro del percorso riempito dall'oggetto corrente. |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | Imposta il punto centrale del gradiente. |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | Imposta il punto focale per il decadimento del gradiente. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Imposta un valore che definisce un gradiente lineare multicolore. |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Imposta i colori che corrispondono ai punti nel percorso che questo [PathGradientBrush](./) riempie. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Imposta un oggetto [Matrix](../matrix/) che specifica le trasformazioni geometriche per il pennello rappresentato dall'oggetto corrente. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Imposta la modalità di avvolgimento. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | NON IMPLEMENTATO. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | NON IMPLEMENTATO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Trasla la trasformazione geometrica locale delle dimensioni specificate nell'ordine specificato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Libreria [Aspose.Slides](../../)