---
title: WeakPtr
second_title: Aspose.Slides für C++ API-Referenz
description: "Unterklasse von System::SmartPtr, die sich beim Erzeugen in den schwachen Modus versetzt. Bitte beachten Sie, dass diese Klasse nicht garantiert, dass ihre Instanz stets im schwachen Modus bleibt, da set_Mode() weiterhin zugänglich ist. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const Referenz übergeben werden."
type: docs
weight: 1496
url: /de/system/weakptr/
---
## WeakPtr Klasse

Unterklasse von [System::SmartPtr](../smartptr/), die sich beim Erzeugen in den schwachen Modus versetzt. Bitte beachten Sie, dass diese Klasse nicht garantiert, dass ihre Instanz stets im schwachen Modus bleibt, da [set_Mode()](../smartptr/set_mode/) weiterhin zugänglich ist. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const Referenz übergeben werden.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Pointee-Typ. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Zugriffsfunktion für die [begin()](../smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../smartptr/begin/)-Methode ist. |
| auto [begin](../smartptr/begin/)() const | Zugriffsfunktion für die [begin()](../smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger mittels static_cast in den Basistyp um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| auto [cbegin](../smartptr/cbegin/)() const | Zugriffsfunktion für die [cbegin()](../smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../smartptr/cbegin/)-Methode ist. |
| auto [cend](../smartptr/cend/)() const | Zugriffsfunktion für die [cend()](../smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../smartptr/cend/)-Methode ist. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Wandelt den Zeiger mittels const_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger mittels dynamic_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| auto [end](../smartptr/end/)() | Zugriffsfunktion für die [end()](../smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../smartptr/end/)-Methode ist. |
| auto [end](../smartptr/end/)() const | Zugriffsfunktion für die [end()](../smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../smartptr/end/)-Methode ist. |
| **bool** [expired](./expired/)() const | Überprüft, ob das referenzierte Objekt bereits gelöscht wurde. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Erhält das referenzierte Objekt. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Ermittelt den Zeigermodus. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Erhält das referenzierte Objekt, verlangt jedoch, dass der Zeiger im geteilten Modus ist. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Ermittelt die Anzahl der vorhandenen geteilten Zeiger auf das referenzierte Objekt, inklusive des aktuellen. Verlangt, dass der aktuelle Zeiger im geteilten Modus ist. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Erhält das referenzierte Objekt. Verlangt, dass der Zeiger im schwachen Modus ist. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Ruft [GetHashCode()](../smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Erhält das derzeit referenzierte Objekt (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Erhält das referenzierte Objekt (falls vorhanden) oder nullptr. Gleichbedeutend mit [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Erhält das referenzierte Objekt. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Erhält das referenzierte Objekt (falls vorhanden) oder nullptr. Gleichbedeutend mit [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Überprüft, ob das referenzierte Objekt vom angegebenen Typ oder einem abgeleiteten Typ ist. Befolgt die 'is'-Semantik von C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Überprüft, ob der Zeiger auf ein anderes Objekt als das besessene zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../smartptr/isshared/)() const | Überprüft, ob der Zeiger im geteilten Modus ist. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Überprüft, ob der Zeiger im schwachen Modus ist. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Überprüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../smartptr/operator_not/)() const | Überprüft, ob der Zeiger null ist. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Erhält eine Referenz auf das referenzierte Objekt. Verlangt, dass der Zeiger nicht null ist. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Stellt Vergleichssemantik für die [SmartPtr](../smartptr/)-Klasse bereit. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Stellt Vergleichssemantik für die [SmartPtr](../smartptr/)-Klasse bereit. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Weist dem schwachen Zeiger einen Wert zu. Ruft den entsprechenden Zuweisungsoperator von SmartPtr_ auf. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Verschiebt und zuweist das [SmartPtr](../smartptr/)-Objekt. x wird unbenutzbar. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Kopiert und weist das [SmartPtr](../smartptr/)-Objekt zu. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Kopiert und weist das [SmartPtr](../smartptr/)-Objekt zu. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Weist einen rohen Zeiger dem [SmartPtr](../smartptr/)-Objekt zu. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Überprüft, ob der schwache Zeiger null ist. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei geteiltem Modus) das gleiche Objekt verwaltet oder (bei schwachem Modus) nachverfolgt, auf das er zeigt. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt (falls vorhanden) auf. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Erzeugt ein [SmartPtr](../smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Erzeugt ein Null-Zeiger-[SmartPtr](../smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Erzeugt ein [SmartPtr](../smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](../smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](../smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt, falls erlaubt, eine Typkonvertierung durch. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Verschiebt und konstruiert ein [SmartPtr](../smartptr/)-Objekt. Tauscht im Wesentlichen zwei Zeiger, sofern sie im selben Modus sind. x kann nach dem Aufruf unbenutzbar sein. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typcast gibt, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruiert ein [SmartPtr](../smartptr/), das die Besitzinformationen mit dem Anfangswert von ptr teilt, aber einen unrelated und nicht verwalteten Zeiger p hält. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Wandelt den Zeiger mittels static_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger auf [Object](../object/). Benötigt nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Kurzfassung, um das [System::TypeInfo](../typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Erzeugt einen Null-Zeiger. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Erzeugt einen schwachen Zeiger auf das angegebene Objekt. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Erzeugt einen schwachen Zeiger, der auf denselben Zeiger verweist, auf den ptr zeigt. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Erzeugt einen schwachen Zeiger, der auf denselben Zeiger verweist, auf den x zeigt. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Kopiert einen schwachen Zeiger. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Kopiert einen schwachen Zeiger. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Verschiebt einen schwachen Zeiger. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Zerstört das [SmartPtr](../smartptr/)-Objekt. Reduziert bei Bedarf den Referenzzähler des referenzierten Objekts und löscht das Objekt. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias für die entsprechende [SmartPtr](../smartptr/)-Klasse. |
| [WeakPtr_](./weakptr_/) | Alias für den eigenen Typ. |
| [Pointee_](./pointee_/) | Zeigertyp. |

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)