---
title: DynamicWeakPtr
second_title: Aspose.Slides für C++ API-Referenz
description: Smart-Pointer-Klasse, die die Zeiger-Modi von Template-Argumenten des gespeicherten Objekts verfolgt und nach jeder Zuweisung aktualisiert. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 781
url: /de/system/dynamicweakptr/
---
## DynamicWeakPtr Klasse


Smart-Pointer-Klasse, die die Zeiger-Modi von Template-Argumenten des gespeicherten Objekts verfolgt und nach jeder Zuweisung aktualisiert. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Pointee | Typ. |
| trunkMode | Modus des Smart-Pointers selbst, shared oder weak. |
| weakLeafs | Indizes von Template-Argumenten des gespeicherten Typs, die auf den weak-Zeiger-Modus gesetzt werden sollen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Zugriffsfunktion für die [begin()](../smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../smartptr/begin/)-Methode ist. |
| auto [begin](../smartptr/begin/)() const | Zugriffsfunktion für die [begin()](../smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger in den Basistyp mittels static_cast um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger in einen abgeleiteten Typ mittels dynamic_cast um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger in einen abgeleiteten Typ mittels dynamic_cast um. |
| auto [cbegin](../smartptr/cbegin/)() const | Zugriffsfunktion für die [cbegin()](../smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../smartptr/cbegin/)-Methode ist. |
| auto [cend](../smartptr/cend/)() const | Zugriffsfunktion für die [cend()](../smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../smartptr/cend/)-Methode ist. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei const_cast auf das referenzierte Objekt angewendet wird. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei dynamic_cast auf das referenzierte Objekt angewendet wird. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Erzeugt einen null Smart-Pointer. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Erzeugt einen Smart-Pointer, der auf das gegebene Objekt zeigt. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Konstruiert einen Smart-Pointer durch Kopierkonstruktion. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Konstruiert einen Smart-Pointer durch Kopierkonstruktion. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Konstruiert einen Smart-Pointer durch Kopierkonstruktion. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Konstruiert einen Smart-Pointer durch Move-Konstruktion. |
| auto [end](../smartptr/end/)() | Zugriffsfunktion für die [end()](../smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../smartptr/end/)-Methode ist. |
| auto [end](../smartptr/end/)() const | Zugriffsfunktion für die [end()](../smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../smartptr/end/)-Methode ist. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Gibt den Zeiger-Modus zurück. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, prüft jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Gibt die Anzahl der existierenden Shared-Pointer für das referenzierte Objekt zurück, inklusive des aktuellen. Prüft, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Ruft [GetHashCode()](../smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Entspricht [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Entspricht [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom spezifischen Typ oder einem abgeleiteten Typ ist. Folgt den C#-'is'-Semantiken. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das Eigentums-Objekt zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../smartptr/isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Prüft, dass der Zeiger nicht null ist. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Bietet weniger-Vergleichssemantik für die [SmartPtr](../smartptr/)-Klasse. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Bietet weniger-Vergleichssemantik für die [SmartPtr](../smartptr/)-Klasse. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Weist den Smart-Pointer mittels Move-Zuweisung zu. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Weist den Smart-Pointer mittels Kopierzuweisung zu. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Weist den Smart-Pointer mittels Kopierzuweisung zu. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Weist dem Smart-Pointer zu. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Setzt den Smart-Pointer auf null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Smart-Pointer null ist. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Entfernt das Aliasing (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (wenn Shared) das gleiche Objekt verwaltet oder (wenn Weak) verfolgt, auf das er zeigt. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../smartptr/reset/)() | Lässt den Zeiger auf nullptr zeigen. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Setzt den Zeiger-Modus. Kann die Referenzzählungen des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt auf (falls vorhanden). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Erzeugt ein [SmartPtr](../smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Erzeugt ein null-Pointer [SmartPtr](../smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Erstellt ein [SmartPtr](../smartptr/), das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](../smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](../smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt bei Bedarf eine Typkonvertierung durch. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Move-konstruiert ein [SmartPtr](../smartptr/)-Objekt. Effektiv werden zwei Zeiger vertauscht, sofern sie denselben Modus haben. x kann nach dem Aufruf unbrauchbar sein. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typ-Cast gibt, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruiert ein [SmartPtr](../smartptr/), das Besitzinformationen mit dem Anfangswert von ptr teilt, aber einen unabhängigen, nicht verwalteten Zeiger p hält. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei static_cast auf das referenzierte Objekt angewendet wird. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger zu [Object](../object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Kurzform, um das [System::TypeInfo](../typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Zerstört das [SmartPtr](../smartptr/)-Objekt. Falls nötig, wird der Referenzzähler des referenzierten Objekts verringert und das Objekt gelöscht. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) Basisklassen-Alias. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Selbsttyp-Alias. |
| [Pointee_](./pointee_/) | Referenzierter Typ. |
## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)