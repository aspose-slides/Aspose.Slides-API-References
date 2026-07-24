---
title: HashSetPtr
second_title: Aspose.Slides für C++ API-Referenz
description: Zeiger zum Halten von HashSet-Referenzen. Dieser Typ ist ein Zeiger, der die Löschung anderer Objekte verwaltet. Er sollte im Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 235
url: /de/system.collections.generic/hashsetptr/
---
## HashSetPtr Klasse

Zeiger zum Halten von [HashSet](../hashset/) Referenzen. Dieser Typ ist ein Zeiger, der die Löschung anderer Objekte verwaltet. Er sollte im Stack allokiert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsmethode für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsmethode für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mit static_cast in den Basistyp um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mit dynamic_cast in einen abgeleiteten Typ um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mit dynamic_cast in einen abgeleiteten Typ um. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsmethode für die [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsmethode für die [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger mit const_cast in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger mit dynamic_cast in einen anderen Typ um. |
| auto [end](../../system/smartptr/end/)() | Zugriffsmethode für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsmethode für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisationstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Ermittelt den Zeigermodus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, prüft jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Ermittelt die Anzahl der bestehenden Shared-Zeiger auf das referenzierte Objekt, inklusive des aktuellen. Prüft, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) am referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Entspricht [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Entspricht [get()](../../system/smartptr/get/). |
| [HashSetPtr](./hashsetptr/)() | Null-Zeiger-Konstruktor. |
| [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Kopierkonstruktor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem abgeleiteten Typ ist. Entspricht der C#-'is'-Semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das eigene verweist (erstellt durch einen aliasierenden Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Prüft, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Stellt eine Vergleichssemantik 'less' für die [SmartPtr](../../system/smartptr/)-Klasse bereit. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Stellt eine Vergleichssemantik 'less' für die [SmartPtr](../../system/smartptr/)-Klasse bereit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Weist ein [SmartPtr](../../system/smartptr/)-Objekt mittels Move zu. x wird unbrauchbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt zu und führt notwendige Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist einen rohen Zeiger einem [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen aliasierenden Konstruktor) vom Zeiger und stellt sicher, dass er (bei Shared) verwaltet oder (bei Weak) das gleiche Objekt verfolgt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzählungen des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode am referenzierten Objekt (falls vorhanden) auf. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein Null-Zeiger-[SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/), das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt, falls erlaubt, eine Typkonvertierung durch. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/)-Objekt mittels Move. Tauscht im Wesentlichen zwei Zeiger, wenn beide im selben Modus sind. x kann nach dem Aufruf unbrauchbar sein. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typcast gibt, der in C++ nicht unterstützt wird. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/), das die Besitzinformationen des ursprünglichen ptr-Werts teilt, aber einen unabhängigen und nicht verwalteten Zeiger p enthält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger mit static_cast in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger auf [Object](../../system/object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzform, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Bei Bedarf wird der Referenzzähler des referenzierten Objekts verringert und das Objekt gelöscht. |

## Siehe Auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)