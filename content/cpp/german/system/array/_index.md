---
title: Array
second_title: Aspose.Slides für C++ API-Referenz
description: "Klasse, die eine Array-Datenstruktur darstellt. Objekte dieser Klasse sollten ausschließlich mit den Funktionen System::MakeArray() und System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 14
url: /de/system/array/
---
## Array Klasse

Klasse, die eine Array-Datenstruktur darstellt. Objekte dieser Klasse sollten nur mit den Funktionen [System::MakeArray()](../makearray/) und [System::MakeObject()](../makeobject/) alloziert werden. Erzeugen Sie nie eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der Elemente eines Arrays |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Add](./add/)(const T\&) override | Nicht unterstützt, weil das vom aktuellen Objekt dargestellte Array schreibgeschützt ist. |
|  [Array](./array/)() | Konstruiert ein leeres Array. |
|  [Array](./array/)(int, const T\&) | Füllender Konstruktor. |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Füllender Konstruktor. |
|  [Array](./array/)(int, const T) | Füllender Konstruktor. |
|  [Array](./array/)(**vector_t**\&&) | Move-Konstruktor. |
|  [Array](./array/)(const **vector_t**\&) | Kopierkonstruktor. |
|  [Array](./array/)(const std::vector\<Q\>\&) | Konstruiert ein [Array](./)-Objekt und füllt es mit Werten, die von einem std::vector-Objekt kopiert wurden, dessen Werttyp mit **T** übereinstimmt, aber von **UnderlyingType** abweicht. |
|  [Array](./array/)(std::vector\<Q\>\&&) | Konstruiert ein [Array](./)-Objekt und füllt es mit Werten, die von einem std::vector-Objekt verschoben wurden, dessen Werttyp mit **T** übereinstimmt, aber von **UnderlyingType** abweicht. |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Konstruiert ein [Array](./)-Objekt und füllt es mit Werten aus der angegebenen Initializer-Liste, die Elemente des Typs **UnderlyingType** enthält. |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Konstruiert ein [Array](./)-Objekt und füllt es mit Werten aus dem angegebenen Array, das Elemente des Typs **UnderlyingType** enthält. |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | Konstruiert ein [Array](./)-Objekt und füllt es mit Werten aus der angegebenen Initializer-Liste, die Elemente des Typs bool enthält. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Wandelt das Array in eine schreibgeschützte Sammlung um. |
| [iterator](./iterator/) [begin](./begin/)() | Gibt einen Iterator auf das erste Element des Containers zurück. Ist der Container leer, ist der zurückgegebene Iterator gleich [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Gibt einen Iterator auf das erste Element des const-qualifizierten Containers zurück. Ist der Container leer, ist der zurückgegebene Iterator gleich [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Führt eine binäre Suche im sortierten Array durch. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NICHT IMPLEMENTIERT. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Gibt einen Iterator auf das erste const-qualifizierte Element des Containers zurück. Ist der Container leer, ist der zurückgegebene Iterator gleich [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Gibt einen Iterator auf das Element zurück, das dem letzten Element des Containers folgt. Dieses Element dient als Platzhalter; ein Zugriff darauf führt zu undefiniertem Verhalten. |
| void [Clear](./clear/)() override | Nicht unterstützt, weil das vom aktuellen Objekt dargestellte Array schreibgeschützt ist. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Ersetzt **count** Werte beginnend beim Index **startIndex** im angegebenen Array durch Standardwerte. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Klont das Array. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiert einen Bereich von Elementen aus einem [System.Array](./) beginnend bei der angegebenen Quelle. |
| **bool** [Contains](./contains/)(const T\&) const override | Bestimmt, ob das angegebene Element im Array enthalten ist. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Konstruiert ein neues [Array](./)-Objekt und füllt es mit Elementen des angegebenen Arrays, die mithilfe des angegebenen Konverter-Delegaten in den Typ **OutputType** konvertiert wurden. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Konstruiert ein neues [Array](./)-Objekt und füllt es mit Elementen des angegebenen Arrays, die mithilfe des angegebenen Konverter-Funktionsobjekts in den Typ **OutputType** konvertiert wurden. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiert die angegebene Anzahl von Elementen vom Quellarray zum Zielarray. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiert die angegebene Anzahl von Elementen von der Quell-Array-View zum Zielarray. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopiert die angegebene Anzahl von Elementen vom Quellarray zur Ziel-Array-View. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Kopiert die angegebene Anzahl von Elementen von der Quell-Array-View zur Ziel-Array-View. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Kopiert die angegebene Anzahl von Elementen vom Quell-Stack-Array zum Zielarray. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Kopiert die angegebene Anzahl von Elementen vom Quellarray zum Ziel-Stack-Array. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Kopiert die angegebene Anzahl von Elementen vom Quell-Stack-Array zum Ziel-Stack-Array. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-View, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position in der Ziel-Array-View. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-View, beginnend beim angegebenen Index, zur angegebenen Position in der Ziel-Array-View. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen vom Quell-Stack-Array, beginnend beim angegebenen Index, zur angegebenen Position im Zielarray. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen vom Quellarray, beginnend beim angegebenen Index, zur angegebenen Position im Ziel-Stack-Array. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen vom Quell-Stack-Array, beginnend beim angegebenen Index, zur angegebenen Position im Ziel-Stack-Array. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Kopiert eine angegebene Anzahl von Elementen von der Quell-Array-View, beginnend beim angegebenen Index, zur angegebenen Position im Ziel-Stack-Array. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Kopiert alle Elemente des aktuellen Arrays in das angegebene Zielarray. Die Elemente werden im Zielarray ab dem durch das Argument **arrayIndex** angegebenen Index eingefügt. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Kopiert alle Elemente des aktuellen Arrays in das angegebene Zielarray. Die Elemente werden im Zielarray ab dem durch das Argument **dstIndex** angegebenen Index eingefügt. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Kopiert alle Elemente des aktuellen Arrays in die angegebene Ziel-Array-View. Die Elemente werden in der Ziel-Array-View ab dem durch das Argument **dstIndex** angegebenen Index eingefügt. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopiert eine angegebene Anzahl von Elementen aus dem aktuellen Array, beginnend an der angegebenen Position, in das angegebene Zielarray. Die Elemente werden im Zielarray ab dem durch das Argument **dstIndex** angegebenen Index eingefügt. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Kopiert eine angegebene Anzahl von Elementen aus dem aktuellen Array, beginnend an der angegebenen Position, in die angegebene Ziel-Array-View. Die Elemente werden in der Ziel-Array-View ab dem durch das Argument **dstIndex** angegebenen Index eingefügt. |
| int [Count](./count/)() const | Gibt eine Zahl zurück, die die Gesamtzahl aller Elemente in allen Dimensionen des Arrays darstellt. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Gibt einen Reverse-Iterator auf das erste Element des umgekehrten Containers zurück. Er entspricht dem letzten Element des nicht umgekehrten Containers. Ist der Container leer, ist der zurückgegebene Iterator gleich [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Gibt einen Reverse-Iterator auf das Element zurück, das dem letzten Element des umgekehrten Containers folgt. Er entspricht dem Element, das dem ersten Element des nicht umgekehrten Containers vorausgeht. Dieses Element dient als Platzhalter; ein Zugriff darauf führt zu undefiniertem Verhalten. |
| **vector_t**\& [data](./data/)() | Gibt eine Referenz auf die interne Datenstruktur zurück, die zur Speicherung der Array-Elemente verwendet wird. |
| const **vector_t**\& [data](./data/)() const | Gibt eine konstante Referenz auf die interne Datenstruktur zurück, die zur Speicherung der Array-Elemente verwendet wird. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Gibt einen rohen Zeiger auf den Anfang des Speicherpuffers zurück, in dem die Array-Elemente gespeichert sind. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Gibt einen konstanten rohen Zeiger auf den Anfang des Speicherpuffers zurück, in dem die Array-Elemente gespeichert sind. |
| [iterator](./iterator/) [end](./end/)() | Gibt einen Iterator auf das Element zurück, das dem letzten Element des Containers folgt. Dieses Element dient als Platzhalter; ein Zugriff darauf führt zu undefiniertem Verhalten. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Gibt einen Iterator auf das Element zurück, das dem letzten Element des const-qualifizierten Containers folgt. Dieses Element dient als Platzhalter; ein Zugriff darauf führt zu undefiniertem Verhalten. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Bestimmt, ob das angegebene [Array](./)-Objekt ein Element enthält, das die Anforderungen des angegebenen Prädikats erfüllt. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Durchsucht das angegebene Array nach dem ersten Element, das die Bedingungen des angegebenen Prädikats erfüllt. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Ruft alle Elemente ab, die den vom angegebenen Prädikat definierten Bedingungen entsprechen. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Durchsucht das angegebene Array nach dem ersten Element, das die Bedingungen des angegebenen Prädikats erfüllt. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Führt die angegebene Aktion für jedes Element des angegebenen Arrays aus. |
| int [get_Count](./get_count/)() const override | Gibt die Größe des Arrays zurück. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Prüft, ob die Sammlung eine feste Größe hat. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Gibt an, ob das Array schreibgeschützt ist. |
| **int32_t** [get_Length](./get_length/)() const override | Gibt einen 32-Bit-Integer zurück, der die Gesamtzahl aller Elemente in allen Dimensionen des Arrays darstellt. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Gibt einen 64-Bit-Integer zurück, der die Gesamtzahl aller Elemente in allen Dimensionen des Arrays darstellt. |
| **int32_t** [get_Rank](./get_rank/)() const | NICHT IMPLEMENTIERT. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Gibt das Objekt zurück, über das die Sammlung synchronisiert wird. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Gibt einen Zeiger auf ein **Enumerator**-Objekt zurück, das die IEnumerator-Schnittstelle für die Elemente des vom aktuellen Objekt dargestellten Arrays bereitstellt. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| int [GetLength](./getlength/)(int) | Gibt die Anzahl der Elemente in der angegebenen Dimension zurück. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Gibt die Anzahl der Elemente in der angegebenen Dimension als 64-Bit-Integer zurück. |
| int [GetLowerBound](./getlowerbound/)(int) const | Gibt die untere Grenze der angegebenen Dimension zurück. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Gibt eine std::size_t-Variable zurück, die die Gesamtzahl aller Elemente in allen Dimensionen des Arrays darstellt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Gibt die obere Grenze der angegebenen Dimension zurück. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Standardkonstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Copy-Konstruktor. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Move-Konstruktor. |
| T [idx_get](./idx_get/)(int) const override | Gibt das Element am angegebenen Index zurück. |
| void [idx_set](./idx_set/)(int, T) override | Setzt den angegebenen Wert als Element des Arrays am angegebenen Index. |
| int [IndexOf](./indexof/)(const T\&) const override | Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bestimmt den Index des ersten Auftretens des angegebenen Elements im Array, beginnend beim angegebenen Index. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bestimmt den Index des ersten Auftretens des angegebenen Elements in einem durch den Startindex und die Anzahl der Elemente im Bereich definierten Abschnitt des Arrays. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Füllt das vom aktuellen Objekt dargestellte Array mit den Werten aus dem angegebenen Array. |
| void [Initialize](./initialize/)() | Füllt das Array mit standardmäßig konstruierten Objekten vom Typ **T**. |
| void [Insert](./insert/)(int, const T\&) override | Nicht unterstützt, da das vom aktuellen Objekt dargestellte Array schreibgeschützt ist. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Bestimmt den Index des letzten Auftretens des angegebenen Elements in einem durch den Startindex und die Anzahl der Elemente im Bereich definierten Abschnitt des Arrays. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Bestimmt den Index des letzten Auftretens des angegebenen Elements im Array, beginnend beim angegebenen Index. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Bestimmt den Index des letzten Auftretens des angegebenen Elements im Array. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Wendet eine Akkumulatorfunktion auf eine Sequenz an. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bestimmt, ob alle Elemente einer Sequenz eine Bedingung erfüllen. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bestimmt, ob eine Sequenz Elemente enthält. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bestimmt, ob irgendein Element einer Sequenz existiert oder eine Bedingung erfüllt. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Berechnet den Durchschnitt einer Sequenz numerischer Werte. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | Berechnet den Durchschnitt einer Sequenz von Werten, die durch Aufrufen einer Transformationsfunktion für jedes Element der Eingabesequenz erhalten werden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Wandelt die Elemente in den angegebenen Typ um. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Verkettet zwei Sequenzen. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bestimmt, ob eine Sequenz einen angegebenen Wert enthält. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Gibt die Anzahl der Elemente in der Sequenz zurück (berechnet durch direktes Zählen). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Gibt die Anzahl der Elemente in der Sequenz zurück, die die angegebene Bedingung erfüllen. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Gibt das Element an einem angegebenen Index in einer Sequenz zurück. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Gibt das erste Element einer Sequenz zurück. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Gibt das erste Element einer Sequenz zurück, das die angegebene Bedingung erfüllt. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Gibt das erste Element einer Sequenz zurück oder einen Standardwert, wenn die Sequenz leer ist. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Gibt das erste Element der Sequenz zurück, das eine Bedingung erfüllt, oder einen Standardwert, falls kein solches Element gefunden wird. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Gruppiert die Elemente einer Sequenz. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Gruppiert die Elemente einer Sequenz. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Gibt das letzte Element einer Sequenz zurück. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Gibt das letzte Element einer Sequenz zurück oder einen Standardwert, wenn die Sequenz leer ist. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Ruft für jedes Element einer generischen Sequenz eine Transformationsfunktion auf und gibt den maximalen resultierenden Wert zurück. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Ruft für jedes Element einer generischen Sequenz eine Transformationsfunktion auf und gibt den minimalen resultierenden Wert zurück. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtert die Elemente der Sequenz basierend auf dem angegebenen Typ. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz in aufsteigender Reihenfolge nach den Schlüsseln, die vom keySelector ausgewählt werden. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Sortiert die Elemente einer Sequenz in absteigender Reihenfolge nach den Schlüsseln, die vom keySelector ausgewählt werden. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Kehrt die Reihenfolge der Elemente in einer Sequenz um. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transformiert die Elemente einer Sequenz. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transformiert jedes Element einer Sequenz in eine neue Form, indem der Index des Elements einbezogen wird. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projektiert jedes Element einer Sequenz und kombiniert die resultierenden Sequenzen zu einer Sequenz. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Überspringt eine angegebene Anzahl zusammenhängender Elemente am Anfang einer Sequenz und gibt den Rest zurück. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Gibt eine angegebene Anzahl zusammenhängender Elemente vom Anfang einer Sequenz zurück. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Erstellt ein Array aus einer Sequenz. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Erstellt eine List<T> aus einer Sequenz. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert eine Sequenz basierend auf dem angegebenen Prädikat. |
| void [Lock](../object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Findet das größte Element im Array mithilfe von [operator<()](../operator_less/) zum Vergleichen der Elemente. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Findet das kleinste Element im Array mithilfe von [operator<()](../operator_less/) zum Vergleichen der Elemente. |
|  [Object](../object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Move-Zuweisungsoperator. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Move-Zuweisungsoperator. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Gibt ein Element am angegebenen Index zurück. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Gibt ein Element am angegebenen Index zurück. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Gibt einen Zeiger auf das erste Element eines eindimensionalen Arrays zurück. Für mehrdimensionale Arrays ist das Ergebnis undefiniert. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Gibt einen Reverse-Iterator auf das erste Element des umgekehrten Containers zurück. Er entspricht dem letzten Element des nicht umgekehrten Containers. Ist der Container leer, ist der zurückgegebene Iterator gleich [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Gibt einen Reverse-Iterator auf das erste Element des umgekehrten Containers zurück. Er entspricht dem letzten Element des nicht umgekehrten Containers. Ist der Container leer, ist der zurückgegebene Iterator gleich [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von strings. |
| **bool** [Remove](./remove/)(const T\&) override | Nicht unterstützt, weil das vom aktuellen Objekt repräsentierte Array nur lesbar ist. |
| void [RemoveAt](./removeat/)(int) override | Nicht unterstützt, weil das vom aktuellen Objekt repräsentierte Array nur lesbar ist. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Gibt einen Reverse-Iterator auf das Element zurück, das dem letzten Element des umgekehrten Containers folgt. Er entspricht dem Element, das dem ersten Element des nicht umgekehrten Containers vorausgeht. Dieses Element dient als Platzhalter; der Versuch, darauf zuzugreifen, führt zu undefiniertem Verhalten. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Gibt einen Reverse-Iterator auf das Element zurück, das dem letzten Element des umgekehrten Containers folgt. Er entspricht dem Element, das dem ersten Element des nicht umgekehrten Containers vorausgeht. Dieses Element dient als Platzhalter; der Versuch, darauf zuzugreifen, führt zu undefiniertem Verhalten. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Ändert die Größe des angegebenen Arrays auf den angegebenen Wert oder erstellt ein neues Array mit der angegebenen Größe. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Kehrt die Elemente im angegebenen Array um. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Kehrt einen Bereich von Elementen im angegebenen Array um. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Lässt das Array gespeicherte Zeiger als schwach behandeln (falls zutreffend). |
| void [SetValue](./setvalue/)(const T\&, int) | Setzt den Wert des Elements am angegebenen Index. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert der gemeinsam genutzten Referenzzählung. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht die gemeinsam genutzte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert die gemeinsam genutzte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Sortiert die Elemente im angegebenen Array mithilfe des Standardvergleichs. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Sortiert einen Bereich von Elementen im angegebenen Array mithilfe des Standardvergleichs. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Sortiert die Elemente im angegebenen Array mithilfe des angegebenen Vergleichs. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NICHT IMPLEMENTIERT. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Sortiert die Elemente im angegebenen Array mithilfe des angegebenen Vergleichs. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Sortiert zwei Arrays, eines mit Schlüsseln und das andere mit den zugehörigen Elementen, basierend auf den Werten des Arrays mit den Schlüsseln, dessen Elemente mit dem Operator\< verglichen werden. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Sortiert zwei Arrays, eines mit Schlüsseln und das andere mit den zugehörigen Elementen, basierend auf den Werten des Arrays mit den Schlüsseln, dessen Elemente mit dem Standardvergleich verglichen werden. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in string. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Bestimmt, ob alle Elemente im angegebenen Array die durch das angegebene Prädikat definierten Bedingungen erfüllen. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert den C#-Ausdruck typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Direkt aufrufen oder das Sentry-Objekt [LockContext](../lockcontext/) verwenden. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Erhält die Implementierung des const-Begin-Iterators für den aktuellen Container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Erhält die Implementierung des Begin-Iterators für den aktuellen Container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Erhält die Implementierung des const-End-Iterators für den aktuellen Container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Erhält die Implementierung des End-Iterators für den aktuellen Container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destruktor. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [ValueType](./valuetype/) | Alias für den Typ der Elemente des Arrays. |
| [UnderlyingType](./underlyingtype/) | Alias für den Typ, der zur Darstellung jedes Elements des Arrays verwendet wird. |
| [EnumerablePtr](./enumerableptr/) | Ein Alias für den Shared-Pointer-Typ, der auf ein IEnumerable-Objekt mit Elementen vom Typ **T** zeigt. |
| [EnumeratorPtr](./enumeratorptr/) | Ein Alias für den Shared-Pointer-Typ, der auf ein IEnumerator-Objekt mit Elementen vom Typ **T** zeigt. |
| [iterator](./iterator/) | Iterator-Typ. |
| [const_iterator](./const_iterator/) | Const-Iterator-Typ. |
| [reverse_iterator](./reverse_iterator/) | Reverse-Iterator-Typ. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const-Reverse-Iterator-Typ. |

## Anmerkungen



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Array erstellen und füllen.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Array-Elemente ausgeben.
  Print(arrayPtr);

  // Array-Elemente aufsteigend sortieren.
  Array<int32_t>::Sort(arrayPtr);

  // Array-Elemente ausgeben.
  Print(arrayPtr);

  // Anzahl der Array-Elemente ausgeben.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Index des Elements ausgeben, das gleich 4 ist.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Arraygröße ändern.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Array-Elemente ausgeben.
  Print(arrayPtr);

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Siehe auch

* Klasse [ArrayBase](../arraybase/)
* Klasse [IList](../../system.collections.generic/ilist/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)