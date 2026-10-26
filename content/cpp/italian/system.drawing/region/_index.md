---
title: Region
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta l'interno di una forma grafica. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò proverà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 261
url: /it/system.drawing/region/
---
## Classe Region

Rappresenta l'interno di una forma grafica. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class Region : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Restituisce una copia dell'oggetto corrente. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con la porzione della regione definita dal rettangolo specificato che non interseca questa regione. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con la porzione della regione definita dal rettangolo specificato che non interseca questa regione. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con la porzione della regione definita dal percorso specificato che non interseca questa regione. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con la porzione della regione specificata che non interseca questa regione. |
| void [Dispose](./dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se la regione specificata è identica alla regione rappresentata dall'oggetto corrente sulla superficie di disegno specificata. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'esclusione della regione definita dal rettangolo specificato. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'esclusione della regione definita dal rettangolo specificato. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'esclusione della regione definita dal percorso specificato. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'esclusione della regione specificata. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Ottiene una struttura [RectangleF](../rectanglef/) che rappresenta un rettangolo che delimita questo [Region](./) sulla superficie di disegno di un oggetto [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Restituisce un oggetto RegionData contenente i dati che definiscono la regione rappresentata dall'oggetto corrente. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Restituisce un array di strutture [RectangleF](../rectanglef/) che approssimano questo [Region](./) dopo l'applicazione della trasformazione matriciale specificata. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione con una regione definita dal rettangolo specificato. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione con una regione definita dal rettangolo specificato. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione con una regione definita dal percorso specificato. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'intersezione di questa regione con la regione specificata. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se la regione rappresentata dall'oggetto corrente ha un interno vuoto sulla superficie di disegno specificata. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se la regione rappresentata dall'oggetto corrente ha un interno infinito sulla superficie di disegno specificata. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Determina se una porzione del rettangolo specificato è contenuta nella regione rappresentata dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Determina se una porzione del rettangolo specificato è contenuta nella regione rappresentata dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente usando la grafica specificata. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente usando la grafica specificata. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se una porzione del rettangolo specificato è contenuta nella regione rappresentata dall'oggetto corrente usando la grafica specificata. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Determina se una porzione del rettangolo specificato è contenuta nella regione rappresentata dall'oggetto corrente usando la grafica specificata. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Determina se il punto specificato è contenuto nella regione rappresentata dall'oggetto corrente usando la grafica specificata. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Inizializza l'oggetto corrente con interno vuoto. |
| void [MakeInfinite](./makeinfinite/)() | Inizializza questo oggetto Region con interno infinito. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente il clonaggio di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
|  [Region](./region/)() | Crea una nuova istanza della classe [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Crea una nuova istanza della classe [Region](./) che rappresenta una regione definita dal rettangolo specificato. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Crea una nuova istanza della classe [Region](./) che rappresenta una regione definita dal rettangolo specificato. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Crea una nuova istanza della classe [Region](./) che rappresenta una regione definita dal percorso specificato. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Crea una nuova istanza della classe [Region](./) che rappresenta una regione definita dall'oggetto RegionData specificato. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento template a un puntatore weak (anziché shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Trasforma questa regione mediante la matrice specificata. |
| void [Transform](./transform/)(const SkMatrix\&) | Trasforma questa regione mediante la matrice specificata. |
| void [Translate](./translate/)(int, int) | Sposta le coordinate della regione dell'ammontare specificato. |
| void [Translate](./translate/)(**float**, **float**) | Sposta le coordinate della regione dell'ammontare specificato. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'operazione di unione di questa regione con una regione definita dal rettangolo specificato. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'operazione di unione di questa regione con una regione definita dal rettangolo specificato. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'unione di questa regione con una regione definita dal percorso specificato. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con il risultato dell'unione di questa regione con la regione specificata. |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con le porzioni di questa regione e della regione definita dal rettangolo specificato che non si intersecano. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Sostituisce la regione rappresentata dall'oggetto corrente con le porzioni di questa regione e della regione definita dal rettangolo specificato che non si intersecano. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con le porzioni di questa regione e della regione definita dal percorso specificato che non si intersecano. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Sostituisce la regione rappresentata dall'oggetto corrente con le porzioni di questa regione e della regione specificata che non si intersecano. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~Region](./~region/)() | Distruttore. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)