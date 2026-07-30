---
title: ColorMatrix
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta una matrice 5x5 che contiene le coordinate per lo spazio colore RGBAW. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 27
url: /it/system.drawing.imaging/colormatrix/
---
## ColorMatrix classe


Rappresenta una matrice 5x5 che contiene le coordinate per lo spazio colore RGBAW. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class ColorMatrix : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Costruisce una nuova istanza della classe [ColorMatrix](./) e la inizializza con i valori della matrice identità. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Costruisce una nuova istanza della classe [ColorMatrix](./) e la inizializza con i valori specificati. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di floating point in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di floating point in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **float** [get_Matrix00](./get_matrix00/)() const | Restituisce un valore nella riga 0 e colonna 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | Restituisce un valore nella riga 0 e colonna 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | Restituisce un valore nella riga 0 e colonna 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | Restituisce un valore nella riga 0 e colonna 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | Restituisce un valore nella riga 0 e colonna 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | Restituisce un valore nella riga 1 e colonna 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | Restituisce un valore nella riga 1 e colonna 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | Restituisce un valore nella riga 1 e colonna 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | Restituisce un valore nella riga 1 e colonna 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | Restituisce un valore nella riga 1 e colonna 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | Restituisce un valore nella riga 2 e colonna 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | Restituisce un valore nella riga 2 e colonna 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | Restituisce un valore nella riga 2 e colonna 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | Restituisce un valore nella riga 2 e colonna 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | Restituisce un valore nella riga 2 e colonna 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | Restituisce un valore nella riga 3 e colonna 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | Restituisce un valore nella riga 3 e colonna 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | Restituisce un valore nella riga 3 e colonna 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | Restituisce un valore nella riga 3 e colonna 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | Restituisce un valore nella riga 3 e colonna 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | Restituisce un valore nella riga 4 e colonna 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | Restituisce un valore nella riga 4 e colonna 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | Restituisce un valore nella riga 4 e colonna 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | Restituisce un valore nella riga 4 e colonna 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | Restituisce un valore nella riga 4 e colonna 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Restituisce un valore nella riga e colonna specificate. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Imposta il valore specificato nella posizione indicata nella matrice. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'instanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement di C# per il blocco. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Imposta un valore nella riga 0 e colonna 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Imposta un valore nella riga 0 e colonna 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Imposta un valore nella riga 0 e colonna 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Imposta un valore nella riga 0 e colonna 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Imposta un valore nella riga 0 e colonna 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Imposta un valore nella riga 1 e colonna 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Imposta un valore nella riga 1 e colonna 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Imposta un valore nella riga 1 e colonna 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Imposta un valore nella riga 1 e colonna 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Imposta un valore nella riga 1 e colonna 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Imposta un valore nella riga 2 e colonna 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Imposta un valore nella riga 2 e colonna 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Imposta un valore nella riga 2 e colonna 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Imposta un valore nella riga 2 e colonna 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Imposta un valore nella riga 2 e colonna 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Imposta un valore nella riga 3 e colonna 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Imposta un valore nella riga 3 e colonna 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Imposta un valore nella riga 3 e colonna 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Imposta un valore nella riga 3 e colonna 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Imposta un valore nella riga 3 e colonna 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Imposta un valore nella riga 4 e colonna 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Imposta un valore nella riga 4 e colonna 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Imposta un valore nella riga 4 e colonna 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Imposta un valore nella riga 4 e colonna 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Imposta un valore nella riga 4 e colonna 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'n-esimo argomento template a un puntatore weak (piuttosto che shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() statement di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Libreria [Aspose.Slides](../../)