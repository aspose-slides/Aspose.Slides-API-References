---
title: QueuePtr
second_title: Riferimento API di Aspose.Slides per C++
description: Puntatore di coda. Questo tipo è un puntatore per gestire l'eliminazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni sia per valore sia per riferimento const.
type: docs
weight: 482
url: /it/system.collections.generic/queueptr/
---
## QueuePtr classe


[Queue](../queue/) puntatore. Questo tipo è un puntatore per gestire la cancellazione di altri oggetti. Dovrebbe essere allocato sullo stack e passato alle funzioni sia per valore sia per riferimento const.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accessor per il metodo [begin()](../../system/smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accessor per il metodo [begin()](../../system/smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua il cast del puntatore al suo stesso tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua il cast del puntatore al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua il cast del puntatore al tipo derivato usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Effettua il cast del puntatore al tipo derivato usando dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accessor per il metodo [cbegin()](../../system/smartptr/cbegin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accessor per il metodo [cend()](../../system/smartptr/cend/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando const_cast sull'oggetto puntato. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando dynamic_cast sull'oggetto puntato. |
| auto [end](../../system/smartptr/end/)() | Accessor per il metodo [end()](../../system/smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accessor per il metodo [end()](../../system/smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Restituisce l'oggetto puntato. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Restituisce la modalità del puntatore. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Restituisce l'oggetto puntato, ma verifica che il puntatore sia in modalità condivisa. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Restituisce il numero di puntatori condivisi esistenti per l'oggetto referenziato, incluso quello corrente. Verifica che il puntatore corrente sia in modalità condivisa. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Invoca [GetHashCode()](../../system/smartptr/gethashcode/) sull'oggetto puntato. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Restituisce l'oggetto attualmente referenziato (se presente) oppure solleva un'eccezione. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Restituisce l'oggetto puntato (se presente) oppure nullptr. Identico a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Restituisce l'oggetto referenziato. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Restituisce l'oggetto puntato (se presente) oppure nullptr. Identico a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto puntato è di un tipo specifico o di un suo tipo figlio. Segue la semantica 'is' di C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Verifica se il puntatore punta a un oggetto diverso da quello posseduto (creato da un costruttore di aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Verifica se il puntatore è in modalità condivisa. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Verifica se il puntatore è in modalità debole. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Verifica se il puntatore non è null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Verifica se il puntatore è null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Restituisce un riferimento all'oggetto puntato. Verifica che il puntatore non sia null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Consente di accedere ai membri dell'oggetto referenziato. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Assegna per movimento l'oggetto [SmartPtr](../../system/smartptr/). x diventa inutilizzabile. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Assegna per copia l'oggetto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Assegna per copia l'oggetto [SmartPtr](../../system/smartptr/). Esegue le conversioni di tipo necessarie. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assegna un puntatore grezzo all'oggetto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Imposta il valore del puntatore a nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Verifica se il puntatore punta a nullptr. |
|  [QueuePtr](./queueptr/)() | Costruisce un puntatore null. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Costruisce un puntatore a una coda specifica. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Rimuove l'aliasing (creato da un costruttore di aliasing) dal puntatore, garantendo che gestisca (se condiviso) o tracci (se debole) lo stesso oggetto a cui punta. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Imposta l'oggetto puntato. |
| void [reset](../../system/smartptr/reset/)() | Fa sì che il puntatore punti a nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Imposta la modalità del puntatore. Può modificare i contatori di riferimento dell'oggetto referenziato. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Invoca il metodo SetTemplateWeakPtr() sull'oggetto puntato (se presente). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crea un oggetto [SmartPtr](../../system/smartptr/) nella modalità richiesta. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crea un oggetto [SmartPtr](../../system/smartptr/) null-pointer nella modalità richiesta. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crea un [SmartPtr](../../system/smartptr/) che punta all'oggetto specificato, o converte un puntatore grezzo in [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](../../system/smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per copia un oggetto [SmartPtr](../../system/smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. Esegue la conversione di tipo se consentita. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce per movimento un oggetto [SmartPtr](../../system/smartptr/). In pratica, scambia due puntatori, se entrambi sono della stessa modalità. x può diventare inutilizzabile dopo la chiamata. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Converte il tipo dell'array referenziato creando un nuovo array di tipo diverso. Utile se in C# esiste un cast di tipo array non supportato in C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inizializza un array vuoto. Utilizzato per tradurre alcuni costrutti di codice C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Costruisce un [SmartPtr](../../system/smartptr/) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma detiene un puntatore p non correlato e non gestito. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando static_cast sull'oggetto puntato. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Converte qualsiasi tipo di puntatore in puntatore a [Object](../../system/object/). Non richiede che il tipo Pointee_ sia completo. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../../system/typeinfo/) per il tipo Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Distrugge l'oggetto [SmartPtr](../../system/smartptr/). Se necessario, decrementa il contatore di riferimento dell'oggetto puntato e lo elimina. |

## Vedi anche

* Classe [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)