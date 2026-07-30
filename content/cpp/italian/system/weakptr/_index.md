---
title: WeakPtr
second_title: Riferimento API Aspose.Slides per C++
description: "Sottoclasse di System::SmartPtr che si imposta in modalità debole alla costruzione. Si noti che questa classe non garantisce che la sua istanza rimanga sempre in modalità debole poiché set_Mode() è ancora accessibile. Questo tipo è un puntatore per gestire la cancellazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni per valore o per riferimento costante."
type: docs
weight: 1496
url: /it/system/weakptr/
---
## WeakPtr classe


Sottoclasse di [System::SmartPtr](../smartptr/) che si imposta in modalità debole al momento della costruzione. Si noti che questa classe non garantisce che la sua istanza rimanga sempre in modalità debole poiché [set_Mode()](../smartptr/set_mode/) è ancora accessibile. Questo tipo è un puntatore per gestire la cancellazione di altri oggetti. Deve essere allocato sullo stack e passato alle funzioni sia per valore sia per riferimento costante.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'oggetto puntato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accessor per il metodo [begin()](../smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accessor per il metodo [begin()](../smartptr/begin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Converte il puntatore al proprio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Conversione del puntatore al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Conversione del puntatore al tipo derivato usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Conversione del puntatore al tipo derivato usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accessor per il metodo [cbegin()](../smartptr/cbegin/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accessor per il metodo [cend()](../smartptr/cend/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando const_cast sull'oggetto puntato. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando dynamic_cast sull'oggetto puntato. |
| auto [end](../smartptr/end/)() | Accessor per il metodo [end()](../smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accessor per il metodo [end()](../smartptr/end/) di una collezione sottostante. Compila solo se SmartPtr_ è un tipo di specializzazione con il metodo [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Verifica se l'oggetto referenziato è già stato cancellato. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Ottiene l'oggetto puntato. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Restituisce la modalità del puntatore. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Ottiene l'oggetto puntato, ma verifica che il puntatore sia in modalità condivisa. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Restituisce il numero di puntatori condivisi esistenti per l'oggetto referenziato, inclusa l'attuale. Verifica che il puntatore corrente sia in modalità condivisa. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Ottiene l'oggetto referenziato. Verifica che il puntatore sia in modalità debole. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Chiama [GetHashCode()](../smartptr/gethashcode/) sull'oggetto puntato. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Ottiene l'oggetto attualmente referenziato (se presente) o solleva un'eccezione. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Ottiene l'oggetto puntato (se presente) o nullptr. Identico a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Ottiene l'oggetto referenziato. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Ottiene l'oggetto puntato (se presente) o nullptr. Identico a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto puntato è di un tipo specifico o di un tipo figlio. Segue la semantica 'is' di C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Verifica se il puntatore punta a un oggetto diverso da quello posseduto (creato da un costruttore di aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Verifica se il puntatore è in modalità condivisa. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Verifica se il puntatore è in modalità debole. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Verifica se il puntatore non è nullo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Verifica se il puntatore è nullo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Ottiene un riferimento all'oggetto puntato. Verifica che il puntatore non sia nullo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Consente di accedere ai membri dell'oggetto referenziato. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fornisce la semantica di confronto meno per la classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fornisce la semantica di confronto meno per la classe [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Assegna il valore al puntatore debole. Invoca l'operatore di assegnazione specifico di SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Assegna tramite move l'oggetto [SmartPtr](../smartptr/). x diventa inutilizzabile. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Assegna tramite copia l'oggetto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Assegna tramite copia l'oggetto [SmartPtr](../smartptr/). Esegue le conversioni di tipo richieste. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Assegna un puntatore grezzo all'oggetto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Imposta il valore del puntatore a nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se il puntatore debole è nullo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Rimuove l'aliasing (creato da un costruttore di aliasing) dal puntatore, assicurando che gestisca (se condiviso) o tracci (se debole) lo stesso oggetto a cui punta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Imposta l'oggetto puntato. |
| void [reset](../smartptr/reset/)() | Fa sì che il puntatore punti a nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Imposta la modalità del puntatore. Può modificare i contatori di riferimento dell'oggetto referenziato. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Chiama il metodo SetTemplateWeakPtr() sull'oggetto puntato (se presente). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](../smartptr/) della modalità richiesta. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un oggetto [SmartPtr](../smartptr/) a puntatore nullo della modalità richiesta. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](../smartptr/) che punta all'oggetto specificato, o converte un puntatore grezzo in [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Costruisce copie di un oggetto [SmartPtr](../smartptr/). Entrambi i puntatori puntano allo stesso oggetto in seguito. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Costruisce copie di un oggetto [SmartPtr](../smartptr/). Entrambi i puntatori puntano allo stesso oggetto in seguito. Esegue la conversione di tipo se consentita. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Costruisce tramite move un oggetto [SmartPtr](../smartptr/). In pratica, scambia due puntatori, se entrambi sono della stessa modalità. x può diventare inutilizzabile dopo la chiamata. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Converte il tipo dell'array referenziato creando un nuovo array di tipo diverso. Utile se in C# esiste un cast di tipo array non supportato in C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inizializza un array vuoto. Usato per tradurre alcuni costrutti di codice C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Costruisce un [SmartPtr](../smartptr/) che condivide le informazioni di proprietà con il valore iniziale di ptr, ma contiene un puntatore non correlato e non gestito p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Conversione del puntatore a un tipo diverso usando static_cast sull'oggetto puntato. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Converte qualsiasi tipo di puntatore in un puntatore a [Object](../object/). Non richiede che il tipo Pointee_ sia completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Scorciatoia per ottenere l'oggetto [System::TypeInfo](../typeinfo/) per il tipo Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Crea un puntatore nullo. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Crea un puntatore debole per l'oggetto fornito. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Crea un puntatore debole che fa riferimento allo stesso puntatore a cui ptr punta. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Crea un puntatore debole che fa riferimento allo stesso puntatore a cui x punta. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Costruisce una copia del puntatore debole. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Costruisce una copia del puntatore debole. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Costruisce tramite move un puntatore debole. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Distrugge l'oggetto [SmartPtr](../smartptr/). Se necessario, diminuisce il contatore di riferimento dell'oggetto puntato ed elimina l'oggetto. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias per la classe [SmartPtr](../smartptr/) corrispondente. |
| [WeakPtr_](./weakptr_/) | Alias per il tipo stesso. |
| [Pointee_](./pointee_/) | Tipo puntato. |

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)