---
title: DynamicWeakPtr
second_title: Riferimento API di Aspose.Slides per C++
description: Classe smart pointer che traccia le modalità dei puntatori degli argomenti di modello dell'oggetto memorizzato e le aggiorna dopo ogni assegnazione. Questo tipo è un puntatore per gestire l'eliminazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni sia per valore che per riferimento const.
type: docs
weight: 781
url: /it/system/dynamicweakptr/
---
## DynamicWeakPtr classe

Smart pointer class which tracks pointer modes of template arguments of stored object and updates them after each assignment. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Pointee | tipo. |
| trunkMode | Modalità dello smart pointer stesso, shared o weak. |
| weakLeafs | Indici degli argomenti del modello del tipo memorizzato che devono essere impostati sulla modalità weak pointer. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accessor per il metodo [begin()](../smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accessor per il metodo [begin()](../smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Effettua il cast del puntatore al proprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Effettua il cast del puntatore al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Effettua il cast del puntatore al tipo derivato usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Effettua il cast del puntatore al tipo derivato usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accessor per il metodo [cbegin()](../smartptr/cbegin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accessor per il metodo [cend()](../smartptr/cend/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando const_cast sull'oggetto puntato. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando dynamic_cast sull'oggetto puntato. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Crea uno smart pointer nullo. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Crea uno smart pointer che punta all'oggetto fornito. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Costruisce copia dello smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Costruisce copia dello smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Costruisce copia dello smart pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Costruisce tramite spostamento lo smart pointer. |
| auto [end](../smartptr/end/)() | Accessor per il metodo [end()](../smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accessor per il metodo [end()](../smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo specializzato con il metodo [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Restituisce l'oggetto puntato. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Restituisce la modalità del puntatore. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Restituisce l'oggetto puntato, ma verifica che il puntatore sia in modalità shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Restituisce il numero di smart pointer condivisi esistenti sull'oggetto referenziato, compreso quello corrente. Verifica che il puntatore corrente sia in modalità shared. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Chiama [GetHashCode()](../smartptr/gethashcode/) sull'oggetto puntato. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Restituisce l'oggetto attualmente referenziato (se presente) o lancia un'eccezione. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Restituisce l'oggetto puntato (se presente) o nullptr. Identico a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Restituisce l'oggetto referenziato. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Restituisce l'oggetto puntato (se presente) o nullptr. Identico a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto puntato è di un tipo specifico o di un suo tipo figlio. Segue la semantica 'is' di C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Verifica se il puntatore punta a un altro oggetto rispetto a quello di proprietà (creato da un costruttore aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Verifica se il puntatore è in modalità shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Verifica se il puntatore è in modalità weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Verifica se il puntatore non è nullo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Verifica se il puntatore è nullo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Restituisce un riferimento all'oggetto puntato. Verifica che il puntatore non sia nullo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Consente di accedere ai membri dell'oggetto referenziato. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fornisce la semantica di confronto minore per la classe [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Assegna per spostamento lo smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Assegna per copia lo smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Assegna per copia lo smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Assegna lo smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Imposta lo smart pointer a null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se lo smart pointer è nullo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Rimuove l'aliasing (creato da un costruttore aliasing) dal puntatore, assicurandosi che gestisca (se shared) o tracci (se weak) lo stesso oggetto a cui punta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Imposta l'oggetto puntato. |
| void [reset](../smartptr/reset/)() | Fa sì che il puntatore punti a nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Imposta la modalità del puntatore. Può modificare i contatori di riferimento dell'oggetto referenziato. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chiama il metodo SetTemplateWeakPtr() sull'oggetto puntato (se presente). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](../smartptr/) della modalità richiesta. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](../smartptr/) a puntatore nullo della modalità richiesta. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](../smartptr/) che punta all'oggetto specificato, o converte un puntatore grezzo in [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Copia costruisce un oggetto [SmartPtr](../smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Copia costruisce un oggetto [SmartPtr](../smartptr/). Entrambi i puntatori puntano allo stesso oggetto successivamente. Esegue la conversione di tipo se consentita. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Costruisce per spostamento un oggetto [SmartPtr](../smartptr/). In pratica, scambia due puntatori, se entrambi sono della stessa modalità. x può diventare inutilizzabile dopo la chiamata. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converti il tipo dell'array referenziato creando un nuovo array di tipo diverso. Utile se in C# esiste un cast di tipo array non supportato in C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inizializza un array vuoto. Usato per tradurre alcuni costrutti di codice C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Costruisce un [SmartPtr](../smartptr/) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma contiene un puntatore p non correlato e non gestito. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Effettua il cast del puntatore a un tipo diverso usando static_cast sull'oggetto puntato. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converte qualsiasi tipo di puntatore in un puntatore a [Object](../object/). Non richiede che il tipo Pointee_ sia completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../typeinfo/) per il tipo Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Distrugge l'oggetto [SmartPtr](../smartptr/). Se necessario, decrementa il contatore di riferimento dell'oggetto puntato e lo elimina. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias della classe base. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias del tipo self. |
| [Pointee_](./pointee_/) | tipo puntato. |

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)