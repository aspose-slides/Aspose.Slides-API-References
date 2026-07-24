---
title: ListPtr
second_title: Aspose.Slides für C++ API-Referenz
description: List Zeiger mit Zugriffsoperatoren. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const Referenz übergeben werden.
type: docs
weight: 456
url: /de/system.collections.generic/listptr/
---
## ListPtr Klasse


[List](../list/) Zeiger mit Zugriffsoperatoren. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriff auf die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriff auf die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger zu seinem eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den Basistyp um, mittels static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ um, mittels dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ um, mittels dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriff auf die [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriff auf die [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, mittels const_cast auf das referenzierte Objekt. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, mittels dynamic_cast auf das referenzierte Objekt. |
| auto [end](../../system/smartptr/end/)() | Zugriff auf die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriff auf die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Gibt den Zeigermodus zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, behauptet jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Gibt die Anzahl der vorhandenen Shared-Zeiger auf das referenzierte Objekt zurück, inklusive des aktuellen. Behauptet, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) am referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleiches wie [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleiches wie [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das referenzierte Objekt vom spezifischen Typ oder einem abgeleiteten Typ ist. Folgt den C#-‘is’-Semantiken. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Überprüft, ob der Zeiger auf ein anderes Objekt als das besessene zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Überprüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Überprüft, ob der Zeiger im Weak-Modus ist. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Initialisiert einen Nullzeiger. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Initialisiert den Zeiger auf die angegebene Liste. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Überprüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Überprüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Erhält eine Referenz auf das referenzierte Objekt. Behauptet, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Member des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Bietet weniger-Vergleichssemantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Bietet weniger-Vergleichssemantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Verschiebt die Zuweisung auf ein [SmartPtr](../../system/smartptr/)-Objekt. x wird unbenutzbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert das Zuweisen auf ein [SmartPtr](../../system/smartptr/)-Objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert das Zuweisen auf ein [SmartPtr](../../system/smartptr/)-Objekt. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist den Rohzeiger dem [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Überprüft, ob der [List](../list/)-Zeiger null ist. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Zugriff. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Zugriff. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt Aliasing (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei Shared) verwaltet oder (bei Weak) verfolgt dasselbe Objekt, auf das er zeigt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt auf (falls vorhanden). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein Nullzeiger-[SmartPtr](../../system/smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/), das auf das angegebene Objekt zeigt, oder konvertiert den Rohzeiger zu [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt, falls erlaubt, Typkonvertierung durch. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Verschiebt die Konstruktion eines [SmartPtr](../../system/smartptr/)-Objekts. Tauscht effektiv zwei Zeiger aus, falls beide im gleichen Modus sind. x kann nach dem Aufruf unbenutzbar sein. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typ-Cast gibt, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird zur Übersetzung einiger C#-Codekonstrukte verwendet. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/), das Besitzinformationen mit dem Anfangswert von ptr teilt, aber einen nicht verwandten und unverwalten Zeiger p hält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, indem static_cast auf das referenzierte Objekt angewendet wird. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp zu einem Zeiger auf [Object](../../system/object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Abkürzung, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, verringert den Referenzzähler des referenzierten Objekts und löscht das Objekt. |
## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)