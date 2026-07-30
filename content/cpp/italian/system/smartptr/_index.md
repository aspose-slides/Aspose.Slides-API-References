---
title: SmartPtr
second_title: Riferimento API di Aspose.Slides per C++
description: "Classe puntatore per avvolgere i tipi allocati sull'heap. Usala per gestire la memoria delle classi che ereditano Object. Questo tipo di puntatore segue la semantica dei puntatori intrusivi. Il contatore di riferimento è memorizzato sia nell'oggetto Object stesso sia in una struttura di contatore strettamente legata all'istanza di Object. In ogni caso, tutte le istanze di SmartPtr formano un unico gruppo di proprietà indipendentemente da come siano state create, a differenza del comportamento della classe std::shared_ptr. Convertire un puntatore grezzo in SmartPtr è sicuro poiché esistono altre istanze di SmartPtr che mantengono riferimenti condivisi allo stesso oggetto. Un'istanza della classe SmartPtr può trovarsi in uno dei due stati: puntatore condiviso (shared) e puntatore debole (weak). Per mantenere vivo l'oggetto, il conteggio dei riferimenti condivisi deve rimanere positivo. Entrambi i puntatori weak e shared possono essere usati per accedere all'oggetto puntato (per chiamare metodi, leggere o scrivere campi, ecc.), ma i puntatori weak non partecipano al conteggio dei riferimenti condivisi. L'oggetto viene eliminato quando l'ultimo puntatore 'shared' di SmartPtr ad esso viene distrutto. Pertanto, assicurati che ciò non avvenga quando non esistono altri puntatori shared di SmartPtr verso l'oggetto, ad esempio durante la costruzione o la distruzione dell'oggetto. Usa gli oggetti sentinella System::Object::ThisProtector (nel codice C++) o gli attributi CppCTORSelfReference o CppSelfReference (nel codice C# tradotto) per risolvere il problema. Allo stesso modo, assicurati di rompere i riferimenti ciclici usando la classe puntatore System::WeakPtr o la modalità puntatore System::SmartPtrMode::Weak (nel codice C++) o l'attributo CppWeakPtr (nel codice C# tradotto). Se due o più oggetti si riferiscono reciprocamente usando puntatori 'shared', non verranno mai eliminati. Se il tipo di puntatore (weak o shared) deve essere modificato a runtime, usa il metodo System::SmartPtr<T>::set_Mode() o la classe System::DynamicWeakPtr. La classe SmartPtr non contiene metodi virtuali. Dovresti ereditarla solo se crei una tua strategia di gestione della memoria. Questo tipo è un puntatore per gestire l'eliminazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni per valore o per riferimento const."
type: docs
weight: 1236
url: /it/system/smartptr/
---
## SmartPtr classe

Classe puntatore per avvolgere i tipi allocati sull'heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Type of the pointed object. Must be either [System::Object](../object/) or subclass of it. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| auto [begin](./begin/)() | Accessor per il metodo [begin()](./begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](./begin/). |
| auto [begin](./begin/)() const | Accessor per il metodo [begin()](./begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Conversione del puntatore al suo stesso tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Conversione del puntatore al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Conversione del puntatore al tipo derivato usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Conversione del puntatore al tipo derivato usando dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Accessor per il metodo [cbegin()](./cbegin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Accessor per il metodo [cend()](./cend/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando const_cast sull'oggetto puntato. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando dynamic_cast sull'oggetto puntato. |
| auto [end](./end/)() | Accessor per il metodo [end()](./end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](./end/). |
| auto [end](./end/)() const | Accessor per il metodo [end()](./end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Restituisce l'oggetto puntato. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Restituisce la modalità del puntatore. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Restituisce l'oggetto puntato, ma verifica che il puntatore sia in modalità shared. |
| int [get_shared_count](./get_shared_count/)() const | Restituisce il numero di puntatori shared esistenti verso l'oggetto di riferimento, incluso quello corrente. Verifica che il puntatore corrente sia in modalità shared. |
| int [GetHashCode](./gethashcode/)() const | Chiama [GetHashCode()](./gethashcode/) sull'oggetto puntato. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Restituisce l'oggetto di riferimento attuale (se presente) o lancia un'eccezione. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Restituisce l'oggetto puntato (se presente) o nullptr. Equivalente a [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Restituisce l'oggetto di riferimento. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Restituisce l'oggetto puntato (se presente) o nullptr. Equivalente a [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto puntato è di un tipo specifico o di un suo tipo figlio. Segue la semantica 'is' di C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Verifica se il puntatore punta a un oggetto diverso da quello di proprietà (creato da un costruttore di aliasing). |
| **bool** [IsShared](./isshared/)() const | Verifica se il puntatore è in modalità shared. |
| **bool** [IsWeak](./isweak/)() const | Verifica se il puntatore è in modalità weak. |
| explicit  [operator bool](./operator_bool/)() const | Verifica se il puntatore non è null. |
| **bool** [operator!](./operator_not/)() const | Verifica se il puntatore è null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Restituisce un riferimento all'oggetto puntato. Verifica che il puntatore non sia null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Consente l'accesso ai membri dell'oggetto di riferimento. |
| **bool** [operator<](./operator_less/)(Y *) const | Fornisce la semantica di confronto < per la classe [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Fornisce la semantica di confronto < per la classe [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Assegna via move l'oggetto [SmartPtr](./). x diventa inutilizzabile. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Assegna via copia l'oggetto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Assegna via copia l'oggetto [SmartPtr](./). Esegue le conversioni di tipo richieste. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Assegna un puntatore grezzo all'oggetto [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Imposta il valore del puntatore a nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se il puntatore punta a nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Rimuove l'aliasing (creato da un costruttore di aliasing) dal puntatore, garantendo che gestisca (se shared) o tracci (se weak) lo stesso oggetto a cui punta. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Imposta l'oggetto puntato. |
| void [reset](./reset/)() | Fa puntare il puntatore a nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Imposta la modalità del puntatore. Può alterare i contatori di riferimento dell'oggetto di riferimento. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Chiama il metodo SetTemplateWeakPtr() sull'oggetto puntato (se presente). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](./) della modalità richiesta. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](./) null-pointer della modalità richiesta. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](./) che punta all'oggetto specificato, o converte un puntatore grezzo a [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](./). Entrambi i puntatori puntano allo stesso oggetto dopo la chiamata. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](./). Entrambi i puntatori puntano allo stesso oggetto dopo la chiamata. Esegue la conversione di tipo se consentita. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Costruisce per move un oggetto [SmartPtr](./). Scambia efficacemente due puntatori, se hanno la stessa modalità. x può diventare inutilizzabile dopo la chiamata. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converte il tipo dell'array di riferimento creando un nuovo array di tipo diverso. Utile se in C# esiste un cast di array non supportato in C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Inizializza un array vuoto. Utilizzato per tradurre alcuni costrutti di codice C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Costruisce un [SmartPtr](./) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma possiede un puntatore non correlato e non gestito p. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando static_cast sull'oggetto puntato. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Converte qualsiasi tipo di puntatore a puntatore a [Object](../object/). Non richiede che il tipo Pointee_ sia completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../typeinfo/) per il tipo Pointee_. |
|  [~SmartPtr](./~smartptr/)() | Distrugge l'oggetto [SmartPtr](./). Se necessario, decrementa il contatore di riferimento dell'oggetto puntato e lo elimina. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [Pointee_](./pointee_/) | Tipo puntato. |
| [SmartPtr_](./smartptr_/) | Tipo smart pointer specializzato. |
| [ArrayType](./arraytype/) | Stesso di Pointee_, se è una specializzazione di [System::Array](../array/), altrimenti void. |
| [ValueType](./valuetype/) | Tipo di storage dell'array puntato. Significativo solo se T è una specializzazione di [System::Array](../array/). |
## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)