---
title: StringCollectionPtr
second_title: Aspose.Slides für C++ API-Referenz
description: String-Collection-Zeiger mit Zugriffsoperator.
type: docs
weight: 40
url: /de/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr Klasse


String-Collection-Zeiger mit Zugriffsoperator.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsfunktion für die Methode [begin()](../../system/smartptr/begin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [begin()](../../system/smartptr/begin/) ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsfunktion für die Methode [begin()](../../system/smartptr/begin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [begin()](../../system/smartptr/begin/) ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels static_cast in den Basistyp um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsfunktion für die Methode [cbegin()](../../system/smartptr/cbegin/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [cbegin()](../../system/smartptr/cbegin/) ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsfunktion für die Methode [cend()](../../system/smartptr/cend/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [cend()](../../system/smartptr/cend/) ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger mittels const_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger mittels dynamic_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| auto [end](../../system/smartptr/end/)() | Zugriffsfunktion für die Methode [end()](../../system/smartptr/end/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [end()](../../system/smartptr/end/) ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsfunktion für die Methode [end()](../../system/smartptr/end/) einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der Methode [end()](../../system/smartptr/end/) ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Ermittelt den Zeiger-Modus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, prüft jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Ermittelt die Anzahl der Shared-Zeiger, die auf das referenzierte Objekt zeigen, einschließlich des aktuellen. Prüft, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) am referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das derzeit referenzierte Objekt zurück (falls vorhanden) oder löst eine Ausnahme aus. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichwertig zu [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichwertig zu [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem abgeleiteten Typ ist. Entspricht der C#-„is“-Semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das eigene zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Prüft, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Stellt eine „less“-Vergleichssemantik für die Klasse [SmartPtr](../../system/smartptr/) bereit. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Stellt eine „less“-Vergleichssemantik für die Klasse [SmartPtr](../../system/smartptr/) bereit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-zuweist das Objekt [SmartPtr](../../system/smartptr/). x wird danach unbenutzbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert das Objekt [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert das Objekt [SmartPtr](../../system/smartptr/) und führt notwendige Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist einen rohen Zeiger dem Objekt [SmartPtr](../../system/smartptr/) zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Zugriffsfunktion. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Aliasing (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei Shared) verwaltet oder (bei Weak) verfolgt dasselbe Objekt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeiger-Modus. Kann die Referenzzählungen des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die Methode SetTemplateWeakPtr() am referenzierten Objekt auf (falls vorhanden). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein Null-Zeiger-[SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder wandelt einen rohen Zeiger in [SmartPtr](../../system/smartptr/) um. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen anschließend auf dasselbe Objekt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen anschließend auf dasselbe Objekt. Führt ggf. eine Typkonvertierung durch. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstituiert ein [SmartPtr](../../system/smartptr/)-Objekt. Tauscht im Wesentlichen zwei Zeiger, sofern sie denselben Modus besitzen. x kann nach dem Aufruf unbenutzbar sein. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn in C# ein Array-Typ-Cast existiert, der in C++ nicht unterstützt wird. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/), das die Besitzinformationen des ursprünglichen Zeigers teilt, aber einen nicht zusammenhängenden und nicht verwalteten Zeiger p hält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger mittels static_cast in einen anderen Typ um, basierend auf dem referenzierten Objekt. |
| [StringCollectionPtr](./stringcollectionptr/)() | Erzeugt einen Null-Zeiger. |
| [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Erstellt einen Zeiger auf eine bestimmte Sammlung. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Wandelt beliebige Zeigertypen in einen Zeiger zu [Object](../../system/object/) um. Der Pointee_-Typ muss nicht vollständig sein. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzform, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, reduziert den Referenzzähler des referenzierten Objekts und löscht das Objekt. |

## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Collections::Specialized](../)
* Bibliothek [Aspose.Slides](../../)