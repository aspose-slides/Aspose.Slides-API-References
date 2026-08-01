---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een collectie van alle lay-outdia's van een gedefinieerde masterdia voor. Breidt de LayoutSlideCollection-klasse uit met methoden voor het toevoegen, invoegen, verwijderen, klonen en herschikken van lay-outdia's in de context van de afzonderlijke verzamelingen van de masterdia's lay-outdia's.
type: docs
weight: 4434
url: /nl/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection klasse


Stelt een verzameling van alle layout-dia's van een gedefinieerde masterdia voor. Breidt de [LayoutSlideCollection](../layoutslidecollection/) klasse uit met methoden voor het toevoegen/invoegen/verwijderen/klonen/herschikken van layout-dia's in de context van de individuele verzamelingen van de masterdia's layout-dia's.

```cpp
class MasterLayoutSlideCollection : public Aspose::Slides::LayoutSlideCollection,
                                    public Aspose::Slides::IMasterLayoutSlideCollection
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [Add](./add/)([SlideLayoutType](../slidelayouttype/), [System::String](../../system/string/)) override | Voegt een nieuwe layout-dia toe aan het einde van de collectie. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie. |
| [iterator](../layoutslidecollection/iterator/) [begin](../layoutslidecollection/begin/)() | Geeft een iterator die naar het eerste element (indien aanwezig) van de collectie wijst. |
| [const_iterator](../layoutslidecollection/const_iterator/) [begin](../layoutslidecollection/begin/)() const | Geeft een iterator die naar het eerste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| [const_iterator](../layoutslidecollection/const_iterator/) [cbegin](../layoutslidecollection/cbegin/)() const | Geeft een iterator die naar het eerste const-gekwalificeerde element (indien aanwezig) van de collectie wijst. |
| [const_iterator](../layoutslidecollection/const_iterator/) [cend](../layoutslidecollection/cend/)() const | Geeft een iterator die direct na het laatste const-gekwalificeerde element (indien aanwezig) van de collectie wijst. |
| void [CopyTo](../layoutslidecollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>\>, **int32_t**) override | Kopieert alle elementen van de collectie naar de opgegeven array. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [iterator](../layoutslidecollection/iterator/) [end](../layoutslidecollection/end/)() | Geeft een iterator die direct na het laatste element (indien aanwezig) van de collectie wijst. |
| [const_iterator](../layoutslidecollection/const_iterator/) [end](../layoutslidecollection/end/)() const | Geeft een iterator die direct na het laatste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietypeobjecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetypeobjecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **int32_t** [get_Count](../layoutslidecollection/get_count/)() override | Geeft het aantal layout-dia's in een collectie terug. Alleen-lezen **int32_t**. |
| **bool** [get_IsSynchronized](../layoutslidecollection/get_issynchronized/)() override | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../layoutslidecollection/get_syncroot/)() override | Geeft een synchronisatiewortel terug. Alleen-lezen [System::Object](../../system/object/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [GetByType](../layoutslidecollection/getbytype/)([SlideLayoutType](../slidelayouttype/)) override | Geeft de eerste layout-dia van het opgegeven type terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Geeft de referentieteller-datastructuur die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>\>\> [GetEnumerator](../layoutslidecollection/getenumerator/)() override | Geeft een enumerator terug die door de collectie iterereert. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Geeft het werkelijke type van het object terug. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [idx_get](../layoutslidecollection/idx_get/)(**int32_t**) override | Geeft de layout-dia terug op index. Alleen-lezen [LayoutSlide](../layoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [Insert](./insert/)(**int32_t**, [SlideLayoutType](../slidelayouttype/), [System::String](../../system/string/)) override | Voegt een nieuwe layout-dia in op de opgegeven positie in de collectie. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Voegt een kopie van een opgegeven layout-dia in op de opgegeven positie in de collectie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Past een accumulatorfunctie toe op een reeks. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Bepaalt of alle elementen van een reeks aan een voorwaarde voldoen. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Bepaalt of een reeks elementen bevat. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Bepaalt of een element van een reeks bestaat of aan een voorwaarde voldoet. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | Bereken het gemiddelde van een reeks numerieke waarden. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Bereken het gemiddelde van een reeks waarden die worden verkregen door een transformatiefunctie op elk element van de invoerreeks aan te roepen. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Zet de elementen om naar het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Voegt twee reeksen samen. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Bepaalt of een reeks een opgegeven waarde bevat. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Geeft het aantal elementen in de reeks terug (bepaald via directe telling). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Geeft het aantal elementen in de reeks terug die aan de opgegeven voorwaarde voldoen. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Geeft het element op een opgegeven index in een reeks terug. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Geeft het element op een opgegeven index in een reeks terug. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Geeft het eerste element van een reeks terug. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Geeft het eerste element van een reeks terug dat aan de opgegeven voorwaarde voldoet. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Geeft het eerste element van een reeks terug, of een standaardwaarde als de reeks leeg is. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Geeft het eerste element van de reeks terug dat aan een voorwaarde voldoet, of een standaardwaarde als geen dergelijk element wordt gevonden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Groepeert de elementen van een reeks. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Groepeert de elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Geeft het laatste element van een reeks terug. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Geeft het laatste element van een reeks terug, of een standaardwaarde als de reeks leeg is. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Voert een transformatiefunctie uit op elk element van een generieke reeks en retourneert de maximale resulterende waarde. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Voert een transformatiefunctie uit op elk element van een generieke reeks en retourneert de minimale resulterende waarde. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtert de elementen van de reeks op basis van het opgegeven type. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in oplopende volgorde op basis van de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Sorteert de elementen van een reeks in aflopende volgorde op basis van de sleutelwaarden geselecteerd door keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Keert de volgorde van de elementen in een reeks om. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transformeert elementen van een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transformeert elk element van een reeks in een nieuwe vorm door de index van het element op te nemen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projetteert elk element van een reeks en combineert de resulterende reeksen tot één reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | Sla een opgegeven aantal aaneengesloten elementen over vanaf het begin van een reeks en retourneer de rest. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Retourneert een opgegeven aantal aaneengesloten elementen vanaf het begin van een reeks. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Maakt een array aan uit een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Maakt een List<T> aan uit een reeks. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtert een reeks op basis van het opgegeven predicaat. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetypeobject per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| void [Remove](../layoutslidecollection/remove/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Verwijdert een layout uit de collectie. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Verwijdert het element op de opgegeven index van de collectie. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemoveUnused](../layoutslidecollection/removeunused/)() override | Verwijdert ongebruikte layout-dia's (layout-dia's waarvan HasDependingSlides onwaar is). |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Verplaatst een layout-dia van de collectie naar de opgegeven positie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Geeft de huidige waarde van de gedeelde referentieteller terug. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waakhondobject. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeBeginConstIterator](../layoutslidecollection/virtualizebeginconstiterator/)() const override | Geeft een iterator die naar het eerste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeBeginIterator](../layoutslidecollection/virtualizebeginiterator/)() override | Geeft een iterator die naar het eerste element (indien aanwezig) van de collectie wijst. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeEndConstIterator](../layoutslidecollection/virtualizeendconstiterator/)() const override | Geeft een iterator die direct na het laatste element (indien aanwezig) van de const-gekwalificeerde instantie van de collectie wijst. |
| [virtualized_iterator](../layoutslidecollection/virtualized_iterator/) * [virtualizeEndIterator](../layoutslidecollection/virtualizeenditerator/)() override | Geeft een iterator die direct na het laatste element (indien aanwezig) van de collectie wijst. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Libereert alle interne datastructuren. |

## Zie ook

* Klasse [LayoutSlideCollection](../layoutslidecollection/)
* Klasse [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)