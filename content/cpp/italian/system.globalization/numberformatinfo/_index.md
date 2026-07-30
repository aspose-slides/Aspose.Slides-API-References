---
title: NumberFormatInfo
second_title: Riferimento API di Aspose.Slides per C++
description: "Contiene informazioni su come formattare i numeri. Le operazioni di impostazione sono abilitate solo su oggetti non di sola lettura. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e utilizzare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 248
url: /it/system.globalization/numberformatinfo/
---
## NumberFormatInfo classe

Contiene informazioni su come formattare i numeri. Le operazioni di impostazione sono abilitate solo su oggetti non di sola lettura. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la [System::MakeObject()](../../system/makeobject/) funzione. Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò causerà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methods

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clona le informazioni di formattazione. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Ottiene il numero di cifre decimali della moneta. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Ottiene il separatore decimale della moneta. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Ottiene il separatore del gruppo della moneta. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Ottiene il numero di cifre decimali della moneta per gruppo. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Ottiene il modello negativo della moneta. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Ottiene il modello positivo della moneta. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Ottiene il simbolo della moneta. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Ottiene le informazioni di formattazione numerica definite dalla cultura del thread corrente. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Ottiene un valore che specifica come visualizzare la forma di una cifra. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Ottiene le informazioni di formattazione numerica definite dalla cultura invariata. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Verifica se il formato è di sola lettura. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Ottiene il simbolo Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Ottiene i simboli delle cifre (da 0 a 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Ottiene il simbolo di infinito negativo. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Ottiene il segno negativo. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Ottiene il numero di cifre decimali. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Ottiene il separatore decimale. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Ottiene il separatore del gruppo numerico. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Ottiene il numero di cifre per gruppo. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Ottiene il modello negativo del numero. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Ottiene il numero di posizioni decimali nei valori percentuali. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Ottiene il separatore decimale nei valori percentuali. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Ottiene il separatore di gruppo nei valori percentuali. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Ottiene il numero di cifre per gruppo di valori percentuali. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Ottiene il modello negativo della percentuale. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Ottiene il modello positivo della percentuale. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Ottiene il simbolo della percentuale. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Ottiene il simbolo del permille. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Ottiene il simbolo di infinito positivo. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Ottiene il segno positivo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Ottiene il formatter di tipo specifico. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Ottiene il formatter associato al provider di formattazione. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [NumberFormatInfo](./numberformatinfo/)() | Costruttore predefinito ([NumberFormatInfo](./) invariato). |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Ottiene la versione di sola lettura del formatter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso di un valore specificato. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Imposta il numero di cifre decimali della moneta. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Imposta il separatore decimale della moneta. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Imposta il separatore del gruppo della moneta. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Imposta il numero di cifre decimali della moneta per gruppo. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Imposta il modello negativo della moneta. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Imposta il modello positivo della moneta. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo della moneta. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Imposta un valore che specifica come visualizzare la forma di una cifra. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Imposta i simboli delle cifre (da 0 a 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo di infinito negativo. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Imposta il segno negativo. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Imposta il numero di cifre decimali. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Imposta il separatore decimale. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Imposta il separatore del gruppo numerico. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Imposta il numero di cifre per gruppo. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Imposta il modello negativo del numero. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Imposta il numero di posizioni decimali nei valori percentuali. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Imposta il separatore decimale nei valori percentuali. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Imposta il separatore di gruppo nei valori percentuali. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Imposta il numero di cifre per gruppo di valori percentuali. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Imposta il modello negativo della percentuale. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Imposta il modello positivo della percentuale. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo della percentuale. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo del permille. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Imposta il simbolo di infinito positivo. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Imposta il segno positivo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Permette di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Classe [IFormatProvider](../../system/iformatprovider/)
* Classe [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)