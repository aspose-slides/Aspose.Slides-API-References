---
title: ListExt
second_title: Aspose.Slides für C++ API Referenz
description: generische List-Klasse, die das IListWrapper-Interface implementiert
type: docs
weight: 443
url: /de/system.collections.generic/listext/
---
## ListExt Klasse

generische [List](../list/) Klasse, die das [IListWrapper](../../system.collections/ilistwrapper/) Schnittstelle implementiert

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | C++ spezifisch. |
| void [Add](../list/add/)(const T\&) override | Fügt ein Element am Ende der Liste hinzu. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Fügt Elemente zur Liste hinzu; wird beim Übersetzen von Initialisierern verwendet. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Fügt alle Elemente aus der Sammlung (oder sich selbst) am Ende der aktuellen Liste hinzu. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Gibt eine schreibgeschützte Referenz auf diese Sammlung zurück. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Gibt einen Iterator auf das erste Element der Sammlung zurück. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Gibt einen Iterator auf das erste Element der const-qualifizierten Sammlung zurück. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Sucht ein Element in einer sortierten Liste. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Sucht ein Element in einer sortierten Liste. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Sucht ein Element in einer sortierten Liste. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Gibt einen Iterator auf das erste const-qualifizierte Element der Sammlung zurück. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Gibt einen Iterator für ein nicht vorhandenes const-qualifiziertes Element hinter dem Ende der Sammlung zurück. |
| void [Clear](../list/clear/)() override | Löscht alle Elemente. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Prüft, ob das Element in der Liste vorhanden ist. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Erstellt eine Liste von Elementen, die in einen anderen Typ konvertiert wurden. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Kopiert Listenelemente in bereits vorhandene Array-Elemente. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Kopiert alle Elemente in bereits vorhandene Array-Elemente. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Kopiert Elemente beginnend beim angegebenen Index in bereits vorhandene Array-Elemente. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Gibt einen Reverse-Iterator auf das letzte const-qualifizierte Element der Sammlung zurück (erstes im Reverse). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) Schnittstelle Implementierung. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) Implementierungshilfe für Referenztypen. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) Implementierungshilfe für Werttypen. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) Implementierungshilfe für andere Typen. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Gibt einen Reverse-Iterator für ein nicht vorhandenes const-qualifiziertes Element vor dem Beginn der Sammlung zurück. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Zugriffs-Funktion auf die zugrunde liegende Datenstruktur. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Zugriffs-Funktion auf die zugrunde liegende Datenstruktur. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Gibt einen Iterator für ein nicht vorhandenes Element hinter dem Ende der Sammlung zurück. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Gibt einen Iterator für ein nicht vorhandenes Element hinter dem Ende der const-qualifizierten Sammlung zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-ähnlichen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-ähnlichen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Prüft, ob ein Element, das einem bestimmten Prädikat entspricht, in der Liste vorhanden ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Sucht ein Element, das einem bestimmten Prädikat entspricht. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Sucht Elemente, die einem bestimmten Prädikat entsprechen. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Sucht ein Element, das einem bestimmten Prädikat entspricht. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Sucht ein Element, das einem bestimmten Prädikat entspricht. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Sucht ein Element, das einem bestimmten Prädikat entspricht. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Sucht das letzte Element, das einem bestimmten Prädikat entspricht. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Wendet eine Aktion auf alle Elemente in der Liste an. |
| int [get_Capacity](../list/get_capacity/)() const | Gibt die aktuelle Kapazität der Liste zurück. |
| int [get_Count](../list/get_count/)() const override | Gibt die Anzahl der Elemente in der aktuellen Liste zurück. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Prüft, ob die Sammlung eine feste Größe hat. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Prüft, ob die Sammlung schreibgeschützt ist. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Gibt das Objekt zurück, über das die Sammlung synchronisiert wird. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Gibt einen Enumerator zurück, um durch Listenelemente zu iterieren. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Erstellt einen Ausschnitt der Liste. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| [ICollection](../icollection/icollection/)() | Standard-Konstruktor. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Kopierkonstruktor. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Move-Konstruktor. |
| T [idx_get](../list/idx_get/)(int) const override | Gibt das Element an einer bestimmten Position zurück. |
| void [idx_set](../list/idx_set/)(int, T) override | Setzt das Element an einer bestimmten Position. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Gibt den ersten Index eines bestimmten Elements zurück. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Sucht ein bestimmtes Element in der Liste. |
| void [Insert](../list/insert/)(int, const T\&) override | Fügt ein Element an der angegebenen Position ein. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Fügt einen Datenbereich an einer bestimmten Position ein. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Auftretens in der gesamten Liste zurück. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Auftretens im Bereich der Elemente im [List](../list/) zurück, der vom ersten Element bis zum angegebenen Index reicht. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Durchsucht das angegebene Objekt und gibt den nullbasierten Index des letzten Auftretens im Bereich der Elemente im [List](../list/) zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Wendet eine Akkumulatorfunktion auf eine Sequenz an. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestimmt, ob alle Elemente einer Sequenz eine Bedingung erfüllen. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Bestimmt, ob eine Sequenz Elemente enthält. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestimmt, ob ein Element einer Sequenz existiert oder eine Bedingung erfüllt. |
| T [LINQ_Average](../ienumerable/linq_average/)() | Berechnet den Durchschnitt einer Sequenz numerischer Werte. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Berechnet den Durchschnitt einer Sequenz von Werten, die durch Aufrufen einer Transformationsfunktion für jedes Element der Eingabesequenz erhalten werden. |
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
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Gibt das erste Element einer Sequenz zurück oder einen Standardwert, falls die Sequenz leer ist. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Gibt das erste Element der Sequenz zurück, das eine Bedingung erfüllt, oder einen Standardwert, falls kein solches Element gefunden wird. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Gruppiert die Elemente einer Sequenz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Gruppiert die Elemente einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Gibt das letzte Element einer Sequenz zurück. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Gibt das letzte Element einer Sequenz zurück oder einen Standardwert, falls die Sequenz leer ist. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft für jedes Element einer generischen Sequenz eine Transformationsfunktion auf und gibt den maximalen resultierenden Wert zurück. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Ruft für jedes Element einer generischen Sequenz eine Transformationsfunktion auf und gibt den minimalen resultierenden Wert zurück. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | Überspringt eine angegebene Anzahl zusammenhängender Elemente vom Anfang einer Sequenz und gibt den Rest zurück. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Gibt eine angegebene Anzahl zusammenhängender Elemente vom Anfang einer Sequenz zurück. |
| [System::ArrayPtr](../../system/arrayptr/)\<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Erstellt ein Array aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Erstellt eine List<T> aus einer Sequenz. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert eine Sequenz basierend auf dem angegebenen Prädikat. |
| [List](../list/list/)() | Erstellt eine leere Liste. |
| [List](../list/list/)(int) | Erstellt eine Liste mit vordefinierter Kapazität. |
| [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Kopierkonstruktor. |
| void [Lock](../../system/object/lock/)() | Implementiert das Lock-Statement von C#. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move-Zuweisungsoperator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move-Zuweisungsoperator. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Zugriffs-Funktion. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Zugriffs-Funktion. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Gibt einen Reverse-Iterator auf das letzte Element der Sammlung zurück (erstes im Reverse). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Gibt einen Reverse-Iterator auf das letzte Element der const-qualifizierten Sammlung zurück (erstes im Reverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| **bool** [Remove](../list/remove/)(const T\&) override | Entfernt die erste Instanz eines bestimmten Elements aus der Liste. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Entfernt alle Elemente, die einem bestimmten Prädikat entsprechen. |
| void [RemoveAt](../list/removeat/)(int) override | Entfernt das Element an der angegebenen Position. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [RemoveRange](../list/removerange/)(int, int) | Entfernt einen Ausschnitt der Liste. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Gibt einen Reverse-Iterator für ein nicht vorhandenes Element vor dem Beginn der Sammlung zurück. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Gibt einen Reverse-Iterator für ein nicht vorhandenes Element vor dem Beginn der const-qualifizierten Sammlung zurück. |
| void [Reverse](../list/reverse/)() | Kehrt die Reihenfolge aller Elemente der gesamten Liste um. |
| void [Reverse](../list/reverse/)(int, int) | Kehrt die Reihenfolge der Elemente eines Listenausschnitts um. |
| void [set_Capacity](../list/set_capacity/)(int) | Setzt die Kapazität der Liste. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sortiert die Elemente in der Liste. |
| void [Sort](../list/sort/)() | Sortiert die Elemente in der Liste mit dem Standardkomparator. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sortiert die Elemente eines Listenausschnitts. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sortiert die Elemente in der Liste. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Konvertiert die Liste in ein Array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| void [TrimExcess](../list/trimexcess/)() | Passt die Listenkapazität an ihre Größe an. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Bestimmt, ob jedes Element in der Sammlung die durch das angegebene Prädikat definierten Bedingungen erfüllt. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Unlock-Statement von C#. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Gibt die Implementierung des begin-const-Iterators für den aktuellen Container zurück. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Gibt die Implementierung des begin-Iterators für den aktuellen Container zurück. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Gibt die Implementierung des end-const-Iterators für den aktuellen Container zurück. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Gibt die Implementierung des end-Iterators für den aktuellen Container zurück. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Siehe auch

* Klasse [List](../list/)
* Klasse [IListWrapper](../../system.collections/ilistwrapper/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)