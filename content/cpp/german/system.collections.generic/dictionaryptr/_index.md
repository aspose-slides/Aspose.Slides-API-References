---
title: DictionaryPtr
second_title: Aspose.Slides für C++ API-Referenz
description: Dictionary-Zeigerklasse mit Operatorüberladungen. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 170
url: /de/system.collections.generic/dictionaryptr/
---
## DictionaryPtr Klasse


[Dictionary](../dictionary/) Pointer-Klasse mit Operatorüberladungen. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Key type. |
| V | Value type. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konvertiert den Zeiger in seinen eigenen Typ. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konvertiert den Zeiger in den Basistyp mittels static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konvertiert den Zeiger in den abgeleiteten Typ mittels dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Konvertiert den Zeiger in den abgeleiteten Typ mittels dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsfunktion für die [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsfunktion für die [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Konvertiert den Zeiger in einen anderen Typ mittels const_cast auf das referenzierte Objekt. |
| [DictionaryPtr](./dictionaryptr/)() | Initialisiert einen Nullzeiger. |
| [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | Konvertiert den Zeigertyp. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Konvertiert den Zeiger in einen anderen Typ mittels dynamic_cast auf das referenzierte Objekt. |
| auto [end](../../system/smartptr/end/)() | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Wird nur kompiliert, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Gibt den Zeigermodus zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, wobei bestätigt wird, dass der Zeiger im gemeinsamen Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Gibt die Anzahl der bestehenden Shared-Zeiger auf das referenzierte Objekt zurück, einschließlich des aktuellen. Bestätigt, dass der aktuelle Zeiger im gemeinsamen Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das derzeit referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleich wie [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleich wie [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem davon abgeleiteten Typ ist. Folgt der C#-'is'-Semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das Eigentum zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Bestätigt, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Bietet eine Vergleichs-<-Semantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Bietet eine Vergleichs-<-Semantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-zuweist das [SmartPtr](../../system/smartptr/)-Objekt. x wird unbenutzbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert zuweist das [SmartPtr](../../system/smartptr/)-Objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert zuweist das [SmartPtr](../../system/smartptr/)-Objekt. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist einen rohen Zeiger dem [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| V\& [operator[]](./operator[]/)(const X\&) const | Zugriffsoperator für die Arbeit mit Schlüsseltyp-Konvertierung. |
| V\& [operator[]](./operator[]/)(const T\&) const | Zugriffsoperator. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger, stellt sicher, dass er (falls shared) verwaltet oder (falls weak) das gleiche Objekt verfolgt, auf das er zeigt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt (falls vorhanden) auf. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein Null-Zeiger-[SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt eine Typkonvertierung durch, falls erlaubt. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstruiert ein [SmartPtr](../../system/smartptr/)-Objekt. Effektiv werden zwei Zeiger getauscht, sofern sie beide im selben Modus sind. x kann nach dem Aufruf unbenutzbar sein. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn in C# ein Array-Typ-Cast vorhanden ist, der in C++ nicht unterstützt wird. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/), das Besitzinformationen mit dem Anfangswert von ptr teilt, aber einen nicht zusammenhängenden und nicht verwalteten Zeiger p hält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Konvertiert den Zeiger in einen anderen Typ mittels static_cast auf das referenzierte Objekt. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger auf [Object](../../system/object/). Erfordert keinen vollständigen Pointee_-Typ. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzform, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, wird der Referenzzähler des referenzierten Objekts verringert und das Objekt gelöscht. |

## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)