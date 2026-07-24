---
title: StackPtr
second_title: Aspose.Slides für C++ API Referenz
description: Stack-Zeiger. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack zugewiesen werden und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 612
url: /de/system.collections.generic/stackptr/
---
## StackPtr Klasse

[Stack](../stack/) Zeiger. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack allokiert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Elementtyp. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den Basistyp mit static_cast um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ mit dynamic_cast um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ mit dynamic_cast um. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsfunktion für die [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsfunktion für die [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger mit const_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger mit dynamic_cast auf das referenzierte Objekt in einen anderen Typ um. |
| auto [end](../../system/smartptr/end/)() | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Liefert das referenzierte Objekt. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Liefert den Zeigermodus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Liefert das referenzierte Objekt, verlangt jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Liefert die Anzahl vorhandener Shared-Zeiger auf das referenzierte Objekt, einschließlich des aktuellen. Verlangt, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Liefert das aktuell referenzierte Objekt (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Liefert das referenzierte Objekt (falls vorhanden) oder nullptr. Entspricht [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Liefert das referenzierte Objekt. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Liefert das referenzierte Objekt (falls vorhanden) oder nullptr. Entspricht [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt einen bestimmten Typ oder einen abgeleiteten Typ hat. Folgt der C#-'is'-Semantik. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das eigene zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Liefert eine Referenz auf das referenzierte Objekt. Verlangt, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Stellt Vergleichssemantik für die Klasse [SmartPtr](../../system/smartptr/) bereit. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Stellt Vergleichssemantik für die Klasse [SmartPtr](../../system/smartptr/) bereit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Weist das [SmartPtr](../../system/smartptr/)-Objekt mittels Move-Zuweisung zu. x wird unbrauchbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt per Kopierzuweisung. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt per Kopierzuweisung. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist den rohen Zeiger dem [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei Shared) das gleiche Objekt verwaltet oder (bei Weak) verfolgt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Lässt den Zeiger auf nullptr zeigen. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die Methode SetTemplateWeakPtr() auf dem referenzierten Objekt (falls vorhanden) auf. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein Null-Pointer [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder wandelt den rohen Zeiger in ein [SmartPtr](../../system/smartptr/) um. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt bei Erlaubnis eine Typkonvertierung durch. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstruiert ein [SmartPtr](../../system/smartptr/)-Objekt. Tauscht im Wesentlichen zwei Zeiger, sofern beide im selben Modus sind. x kann nach dem Aufruf unbrauchbar sein. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typ-Cast gibt, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/), das Besitzinformationen mit dem ursprünglichen Wert von ptr teilt, jedoch einen nicht verwandten und nicht verwalteten Zeiger p enthält. |
|  [StackPtr](./stackptr/)() | Erzeugt einen Null-Zeiger. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Erstellt einen Zeiger, der auf einen bestimmten Stack verweist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger mit static_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger auf [Object](../../system/object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzschrift, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, verringert es den Referenzzähler des referenzierten Objekts und löscht das Objekt. |

## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)