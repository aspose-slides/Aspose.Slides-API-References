---
title: SortedDictionaryPtr
second_title: Riferimento API di Aspose.Slides per C++
description: Puntatore a dizionario ordinato con operatori di accesso. Questo tipo è un puntatore per gestire la cancellazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni sia per valore sia per riferimento costante.
type: docs
weight: 534
url: /it/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr classe

Sorted dictionary pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<SortedDictionary<T, V>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor per il metodo [begin()](../../system/smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accessor per il metodo [begin()](../../system/smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua un cast del puntatore al proprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua un cast del puntatore al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua un cast del puntatore al tipo derivato usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua un cast del puntatore al tipo derivato usando dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor per il metodo [cbegin()](../../system/smartptr/cbegin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accessor per il metodo [cend()](../../system/smartptr/cend/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Effettua un cast del puntatore a un tipo diverso usando const_cast sull'oggetto puntato. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Effettua un cast del puntatore a un tipo diverso usando dynamic_cast sull'oggetto puntato. |
| auto [end](../../system/smartptr/end/)() | Accessor per il metodo [end()](../../system/smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accessor per il metodo [end()](../../system/smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Ottiene l'oggetto puntato. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Ottiene la modalità del puntatore. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Ottiene l'oggetto puntato, ma verifica che il puntatore sia in modalità condivisa. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Restituisce il numero di puntatori condivisi esistenti per l'oggetto riferito, incluso quello corrente. Verifica che il puntatore corrente sia in modalità condivisa. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Invoca [GetHashCode()](../../system/smartptr/gethashcode/) sull'oggetto puntato. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Ottiene l'oggetto attualmente referenziato (se presente) o genera un'eccezione. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Ottiene l'oggetto puntato (se presente) o nullptr. Identico a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Ottiene l'oggetto referenziato. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Ottiene l'oggetto puntato (se presente) o nullptr. Identico a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto puntato è di un tipo specifico o di un suo tipo derivato. Segue la semantica 'is' di C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Verifica se il puntatore punta a un oggetto diverso da quello posseduto (creato da un costruttore di aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Verifica se il puntatore è in modalità condivisa. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Verifica se il puntatore è in modalità debole. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Verifica se il puntatore non è nullo. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Verifica se il puntatore è nullo. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Ottiene un riferimento all'oggetto puntato. Verifica che il puntatore non sia nullo. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Consente di accedere ai membri dell'oggetto referenziato. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Assegna per spostamento l'oggetto [SmartPtr](../../system/smartptr/). x diventa inutilizzabile. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Assegna per copia l'oggetto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Assegna per copia l'oggetto [SmartPtr](../../system/smartptr/). Effettua le conversioni di tipo necessarie. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assegna un puntatore grezzo all'oggetto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Imposta il valore del puntatore a nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Verifica se il puntatore punta a nullptr. |
| V\& [operator[]](./operator[]/)(const T\&) const | Funzione di accesso. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Rimuove l'aliasing (creato da un costruttore di aliasing) dal puntatore, assicurandosi che gestisca (se condiviso) o tracci (se debole) lo stesso oggetto a cui punta. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Imposta l'oggetto puntato. |
| void [reset](../../system/smartptr/reset/)() | Fa puntare il puntatore a nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Imposta la modalità del puntatore. Può alterare i contatori di riferimento dell'oggetto referenziato. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chiama il metodo SetTemplateWeakPtr() sull'oggetto puntato (se presente). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crea un oggetto [SmartPtr](../../system/smartptr/) della modalità richiesta. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crea un oggetto [SmartPtr](../../system/smartptr/) a puntatore nullo della modalità richiesta. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crea un [SmartPtr](../../system/smartptr/) che punta all'oggetto specificato, o converte un puntatore grezzo in [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](../../system/smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](../../system/smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. Esegue la conversione di tipo se consentita. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per spostamento un oggetto [SmartPtr](../../system/smartptr/). Effettivamente, scambia due puntatori, se entrambi sono della stessa modalità. x può diventare inutilizzabile dopo la chiamata. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converte il tipo dell'array referenziato creando un nuovo array di tipo differente. Utile se in C# esiste un cast di tipo array non supportato in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inizializza un array vuoto. Usato per tradurre alcuni costrutti di codice C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce un [SmartPtr](../../system/smartptr/) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma contiene un puntatore p non correlato e non gestito. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)() | Costruisce un puntatore nullo. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedDictionary](../sorteddictionary/)\<T, V\>\>\&) | Costruisce un puntatore al dizionario ordinato specificato. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Effettua un cast del puntatore a un tipo diverso usando static_cast sull'oggetto puntato. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converte qualsiasi tipo di puntatore in un puntatore a [Object](../../system/object/). Non richiede che il tipo Pointee_ sia completo. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../../system/typeinfo/) per il tipo Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Distrugge l'oggetto [SmartPtr](../../system/smartptr/). Se necessario, decrementa il contatore di riferimento dell'oggetto puntato e lo elimina. |

## Vedi anche

* Classe [SmartPtr](../../system/smartptr/)
* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)