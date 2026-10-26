---
title: Matrix
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una matrice 3x3 che definisce operazioni di trasformazione. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject() . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 118
url: /it/system.drawing.drawing2d/matrix/
---
## Matrix classe

Rappresenta una matrice 3x3 che definisce operazioni di trasformazione. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizzare questo puntatore per passarla alle funzioni come argomento.

```cpp
class Matrix : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Crea una copia dell'oggetto corrente. |
| void [Dispose](./dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Verifica se l'oggetto specificato è un [Matrix](./) ed è identico a questo oggetto. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Restituisce un array contenente gli elementi della matrice nel seguente ordine: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Determina se la matrice rappresentata dall'oggetto corrente è una matrice identità. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Determina se la matrice rappresentata dall'oggetto corrente è invertibile. |
| **float** [get_OffsetX](./get_offsetx/)() const | Restituisce il valore di traslazione X della matrice rappresentata dall'oggetto corrente. |
| **float** [get_OffsetY](./get_offsety/)() const | Restituisce il valore di traslazione Y della matrice rappresentata dall'oggetto corrente. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hash di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Inverte la matrice rappresentata dall'oggetto corrente. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| [Matrix](./matrix/)() | Crea una nuova istanza della classe [Matrix](./) che rappresenta una matrice identità. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Crea una nuova istanza della classe [Matrix](./) e la inizializza con i valori specificati. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Crea una nuova istanza della classe [Matrix](./) per la trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Crea una nuova istanza della classe [Matrix](./) per la trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonaggio di tipi personalizzati. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Moltiplica la matrice rappresentata dall'oggetto corrente per la matrice specificata. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Moltiplica la matrice rappresentata dall'oggetto corrente per la matrice specificata. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, realmente, semplicemente inizializza il nuovo oggetto e consente la costruzione di copie nelle subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, realmente, semplicemente inizializza il nuovo oggetto e consente la costruzione di copie nelle subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [Reset](./reset/)() | Reimposta la matrice rappresentata dall'oggetto corrente affinché diventi una matrice identità. |
| void [Rotate](./rotate/)(**float**) | Ruota la matrice rappresentata dall'oggetto corrente in senso orario dell'angolo specificato. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Ruota la matrice rappresentata dall'oggetto corrente in senso orario attorno all'origine dell'angolo specificato. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Ruota la matrice rappresentata dall'oggetto corrente in senso orario attorno al punto specificato dell'angolo specificato. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Ruota la matrice rappresentata dall'oggetto corrente in senso orario attorno al punto specificato dell'angolo specificato. |
| void [Scale](./scale/)(**float**, **float**) | Applica il vettore di scala specificato alla matrice rappresentata dall'oggetto corrente. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applica il vettore di scala specificato alla matrice rappresentata dall'oggetto corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del modello come puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Applica il vettore di shear specificato alla matrice rappresentata dall'oggetto corrente. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applica il vettore di shear specificato alla matrice rappresentata dall'oggetto corrente. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applica la trasformazione geometrica definita dalla matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applica la trasformazione geometrica definita dalla matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applica la trasformazione geometrica definita dalla matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applica la trasformazione geometrica definita dalla matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Applica solo le componenti di scala e rotazione della matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Applica solo le componenti di scala e rotazione della matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Applica solo le componenti di scala e rotazione della matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Applica solo le componenti di scala e rotazione della matrice rappresentata dall'oggetto corrente ai punti specificati. |
| void [Translate](./translate/)(**float**, **float**) | Applica il vettore di traslazione specificato alla matrice rappresentata dall'oggetto corrente. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Applica il vettore di traslazione specificato alla matrice rappresentata dall'oggetto corrente. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Moltiplica ogni vettore in un array per la matrice rappresentata dall'oggetto corrente. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Moltiplica ogni vettore in un array per la matrice rappresentata dall'oggetto corrente. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Libreria [Aspose.Slides](../../)