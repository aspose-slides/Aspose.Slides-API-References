---
title: SortedDictionary
second_title: Aspose.Slides für C++ API-Referenz
description: Vorwärtsdeklaration des sortierten Wörterbuchtyps.
type: docs
weight: 521
url: /de/system.collections.generic/sorteddictionary/
---
## SortedDictionary Klasse


Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```


### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Fügt ein Schlüssel-Wert-Paar in den Container ein. |
| virtual void [Add](../icollection/add/)(const T\&) | Fügt ein Element zur Sammlung hinzu. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Gibt einen Iterator zurück, der auf das erste Element (falls vorhanden) der Sammlung zeigt. Dieser Iterator kann nicht verwendet werden, um das referenzierte Objekt zu ändern, weil [GetEnumerator()](../ienumerable/getenumerator/) ein Kopie-Objekt von T zurückgibt. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Gibt einen Iterator zurück, der auf das erste Element (falls vorhanden) der konstant-qualifizierten Instanz der Sammlung zeigt. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Gibt einen Iterator zurück, der auf das erste konstant-qualifizierte Element (falls vorhanden) der Sammlung zeigt. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Gibt einen Iterator zurück, der direkt nach dem letzten konstant-qualifizierten Element (falls vorhanden) der Sammlung zeigt. |
| virtual void [Clear](../icollection/clear/)() | Löscht alle Elemente aus der Sammlung. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Prüft, ob das Element in der Sammlung vorhanden ist. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Prüft, ob der Container den Schlüssel enthält. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Kopiert den Inhalt des Wörterbuchs in vorhandene Array-Elemente. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Gibt einen Reverse-Iterator zum letzten konstant-qualifizierten Element der Sammlung zurück (erstes im Rückwärtsmodus). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Gibt einen Reverse-Iterator für ein nicht vorhandenes konstant-qualifiziertes Element vor dem Beginn der Sammlung zurück. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Gibt einen Iterator zurück, der direkt nach dem letzten Element (falls vorhanden) der Sammlung zeigt. Dieser Iterator kann nicht verwendet werden, um das referenzierte Objekt zu ändern, weil [GetEnumerator()](../ienumerable/getenumerator/) ein Kopie-Objekt von T zurückgibt. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Gibt einen Iterator zurück, der direkt nach dem letzten Element (falls vorhanden) der konstant-qualifizierten Instanz der Sammlung zeigt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() const | Gibt den IComparer<TKey> zurück, der zum Sortieren der Elemente des SortedDictionary<TKey,TValue> verwendet wird. |
| virtual int [get_Count](../icollection/get_count/)() const | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Prüft, ob die Größe der Sammlung fest ist. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Prüft, ob die Sammlung schreibgeschützt ist. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Prüft, ob der Container threadsicher ist. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Greift auf die Schlüssel-Sammlung zu. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Gibt das Objekt zurück, über das die Sammlung synchronisiert wird. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Greift auf die Werte-Sammlung zu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verbunden ist. |
| static [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Singleton-Zugriffsfunktion. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Gibt einen Enumerator zurück, um das aktuelle Wörterbuch zu iterieren. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | Gibt den Wert zurück, wenn gefunden; ansonsten **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | Gibt den Wert zurück, wenn gefunden; ansonsten **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | Gibt den Wert zurück, wenn gefunden; ansonsten **null**, sinnvoll nur für Referenztypen. |
|  [ICollection](../icollection/icollection/)() | Standardkonstruktor. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopierkonstruktor. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Move-Konstruktor. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | Getter-Funktion. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | Setter-Funktion. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Wendet eine Akkumulatorfunktion auf eine Sequenz an. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestimmt, ob alle Elemente einer Sequenz eine Bedingung erfüllen. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bestimmt, ob eine Sequenz irgendwelche Elemente enthält. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestimmt, ob ein Element einer Sequenz existiert oder eine Bedingung erfüllt. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Berechnet den Durchschnitt einer Sequenz numerischer Werte. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berechnet den Durchschnitt einer Sequenz von Werten, die durch Aufrufen einer Transformationsfunktion auf jedes Element der Eingabesequenz erhalten werden. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Wandelt die Elemente in den angegebenen Typ um. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Verkettet zwei Sequenzen. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Bestimmt, ob eine Sequenz einen angegebenen Wert enthält. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Gibt die Anzahl der Elemente in der Sequenz zurück (berechnet durch direktes Zählen). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Gibt die Anzahl der Elemente in der Sequenz zurück, die die angegebene Bedingung erfüllen. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_First](../ienumerable/linq_first/)() | Gibt das erste Element einer Sequenz zurück. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Gibt das erste Element einer Sequenz zurück, das die angegebene Bedingung erfüllt. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Gibt das erste Element einer Sequenz zurück, oder einen Standardwert, falls die Sequenz leer ist. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Gibt das erste Element der Sequenz zurück, das eine Bedingung erfüllt, oder einen Standardwert, falls kein solches Element gefunden wird. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Gruppiert die Elemente einer Sequenz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Gruppiert die Elemente einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Gibt das letzte Element einer Sequenz zurück. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Gibt das letzte Element einer Sequenz zurück, oder einen Standardwert, falls die Sequenz leer ist. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den maximalen resultierenden Wert zurück. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den minimalen resultierenden Wert zurück. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtert die Elemente der Sequenz basierend auf dem angegebenen Typ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz in aufsteigender Reihenfolge nach den vom keySelector ausgewählten Schlüsselwerten. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz in absteigender Reihenfolge nach den vom keySelector ausgewählten Schlüsselwerten. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Kehrt die Reihenfolge der Elemente einer Sequenz um. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformiert die Elemente einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformiert jedes Element einer Sequenz in eine neue Form, indem der Index des Elements einbezogen wird. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projiziert jedes Element einer Sequenz und kombiniert die resultierenden Sequenzen zu einer einzigen Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Überspringt eine angegebene Anzahl zusammenhängender Elemente am Anfang einer Sequenz und gibt den Rest zurück. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Gibt eine angegebene Anzahl zusammenhängender Elemente vom Anfang einer Sequenz zurück. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Erstellt ein Array aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Erstellt eine List<T> aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert eine Sequenz basierend auf dem angegebenen Prädikat. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move-Zuweisungsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move-Zuweisungsoperator. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Gibt einen Reverse-Iterator zum letzten Element der Sammlung zurück (erstes im Rückwärtsmodus). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Gibt einen Reverse-Iterator zum letzten Element der konstant-qualifizierten Sammlung zurück (erstes im Rückwärtsmodus). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | Entfernt den Schlüssel aus dem Container. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Löscht das Element aus der Sammlung. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Gibt einen Reverse-Iterator für ein nicht vorhandenes Element vor dem Beginn der Sammlung zurück. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Gibt einen Reverse-Iterator für ein nicht vorhandenes Element vor dem Beginn der konstant-qualifizierten Sammlung zurück. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
|  [SortedDictionary](./sorteddictionary/)() | Konstruiert ein leeres Wörterbuch. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Konstruiert ein leeres Wörterbuch. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | Kopierkonstruktor. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Kopierkonstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | Sucht nach dem Wert und holt ihn, wenn gefunden. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Gibt die Implementierung des begin-const-Iterators für den aktuellen Container zurück. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Gibt die Implementierung des begin-Iterators für den aktuellen Container zurück. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Gibt die Implementierung des end-const-Iterators für den aktuellen Container zurück. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Gibt die Implementierung des end-Iterators für den aktuellen Container zurück. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [KeyCollection](./keycollection/) | Key collection type. |
| [ValueCollection](./valuecollection/) | Value collection type. |
| [map_t](./map_t/) | Underlying data type. |
| [this_t](./this_t/) | Self type. |
| [Ptr](./ptr/) | Pointer type. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [IEnumerablePtr](./ienumerableptr/) | Collection of same elements. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** type. |
| [iterator](./iterator/) | Iterator type. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
## Bemerkungen

Sortierte Wörterbuch-Klasse, die STL map kapselt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Nie eine Instanz dieses Typs im Stack oder mit operator new erstellen, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Immer diese Klasse in einen [System::SmartPtr](../../system/smartptr/)-Pointer einwickeln und diesen Pointer verwenden, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Klasse [BaseDictionary](../basedictionary/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)