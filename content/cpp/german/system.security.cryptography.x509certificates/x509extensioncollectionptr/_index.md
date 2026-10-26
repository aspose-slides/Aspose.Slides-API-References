---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides für C++ API-Referenz
description: Zeiger auf eine Sammlung von X509-Erweiterungen. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte im Stack alloziert werden und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 170
url: /de/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr Klasse


Pointer to collection of X509 extensions. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsmethode für [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsmethode für [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den Basistyp um mittels static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ um mittels dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in den abgeleiteten Typ um mittels dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsmethode für [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsmethode für [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei const_cast auf das referenzierte Objekt angewendet wird. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei dynamic_cast auf das referenzierte Objekt angewendet wird. |
| auto [end](../../system/smartptr/end/)() | Zugriffsmethode für [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsmethode für [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Komiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Ermittelt den Zeigermodus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, stellt jedoch sicher, dass der Zeiger im geteilten Modus ist. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Ermittelt die Anzahl der existierenden geteilten Zeiger auf das referenzierte Objekt, einschließlich des aktuellen. Stellt sicher, dass der aktuelle Zeiger im geteilten Modus ist. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleich wie [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleich wie [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem abgeleiteten Typ ist. Folgt der C#-Semantik von 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das eigene zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im geteilten Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im schwachen Modus ist. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Stellt sicher, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Bietet eine weniger-als-Vergleichssemantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Bietet eine weniger-als-Vergleichssemantik für die [SmartPtr](../../system/smartptr/)-Klasse. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-zuweist das [SmartPtr](../../system/smartptr/)-Objekt. x wird unbrauchbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt zu. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist dem [SmartPtr](../../system/smartptr/)-Objekt einen rohen Zeiger zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | Zugriffsmethode. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er dasselbe Objekt verwaltet (falls geteilt) oder verfolgt (falls schwach). |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt auf (falls vorhanden). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erzeugt ein [SmartPtr](../../system/smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein Nullzeiger-[SmartPtr](../../system/smartptr/)-Objekt des erforderlichen Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt, falls zulässig, eine Typkonvertierung durch. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstruiert ein [SmartPtr](../../system/smartptr/)-Objekt. Tauscht effektiv zwei Zeiger, sofern beide denselben Modus haben. x kann nach dem Aufruf unbrauchbar sein. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typumwandlung gibt, die in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Codekonstrukte zu übersetzen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/), das Besitzinformationen mit dem ursprünglichen Wert von ptr teilt, aber einen unabhängigen und nicht verwalteten Zeiger p enthält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger in einen anderen Typ um, wobei static_cast auf das referenzierte Objekt angewendet wird. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert beliebige Zeigertypen zu einem Zeiger auf [Object](../../system/object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzform, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | Nullzeiger-Konstruktor. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, verringert es den Referenzzähler des referenzierten Objekts und löscht das Objekt. |

## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Security::Cryptography::X509Certificates](../)
* Bibliothek [Aspose.Slides](../../)