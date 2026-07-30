---
title: SymmetricAlgorithm
second_title: Riferimento API di Aspose.Slides per C++
description: "Algoritmo simmetrico che utilizza la stessa chiave per la crittografia e la decrittografia, classe base. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 651
url: /it/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm classe

Algoritmo simmetrico che utilizza la stessa chiave per crittografia e decrittografia, classe base. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando operator new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizzare questo puntatore per passarlo alle funzioni come argomento.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Crea un'istanza dell'algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Crea un decrittatore con i parametri associati all'oggetto algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Crea un decrittatore con parametri espliciti. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Crea un encryptor con i parametri associati all'oggetto algoritmo. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Crea un encryptor con parametri espliciti. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual void [GenerateIV](./generateiv/)() | Genera un valore iniziale casuale per l'algoritmo. Sovrascrive quello esistente (se presente). |
| virtual void [GenerateKey](./generatekey/)() | Genera una chiave casuale per l'algoritmo. Sovrascrive quella esistente (se presente). |
| virtual int [get_BlockSize](./get_blocksize/)() | Ottiene la dimensione del blocco dell'operazione crittografica. |
| virtual int [get_FeedbackSize](./get_feedbacksize/)() | Ottiene la dimensione del feedback dell'operazione crittografica. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](./get_iv/)() | Ottiene il valore iniziale dell'operazione crittografica. Ne crea uno nuovo se non è già stato creato. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](./get_key/)() | Ottiene la chiave dell'operazione crittografica. Ne crea una nuova se non è già stata creata. |
| virtual int [get_KeySize](./get_keysize/)() | Ottiene la dimensione della chiave dell'operazione crittografica. |
| virtual [CipherMode](../ciphermode/) [get_Mode](./get_mode/)() | Ottiene la modalità dell'operazione crittografica. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](./get_padding/)() | Ottiene il padding dell'operazione crittografica. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, si limita ad inizializzare un nuovo oggetto e permette la copia dei sottotipi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, si limita ad inizializzare un nuovo oggetto e permette la copia dei sottotipi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_BlockSize](./set_blocksize/)(int) | Imposta la dimensione del blocco dell'operazione crittografica. |
| virtual void [set_FeedbackSize](./set_feedbacksize/)(int) | Imposta la dimensione del feedback dell'operazione crittografica. |
| virtual void [set_IV](./set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imposta il valore iniziale dell'operazione crittografica. |
| virtual void [set_Key](./set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imposta la chiave dell'operazione crittografica. |
| virtual void [set_KeySize](./set_keysize/)(int) | Imposta la dimensione della chiave dell'operazione crittografica. |
| virtual void [set_Mode](./set_mode/)([CipherMode](../ciphermode/)) | Imposta la modalità dell'operazione crittografica. |
| virtual void [set_Padding](./set_padding/)([PaddingMode](../paddingmode/)) | Imposta il padding dell'operazione crittografica. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come weak pointer (anziché shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](./validkeysize/)(int) | Verifica se la dimensione della chiave è valida. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Libreria [Aspose.Slides](../../)