---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides für C++ API-Referenz
description: Zeiger auf eine Sammlung von X509-Zertifikaten. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack angelegt und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.
type: docs
weight: 66
url: /de/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr Klasse

Zeiger auf eine Sammlung von X509-Zertifikaten. Dieser Typ ist ein Zeiger, um das Löschen anderer Objekte zu verwalten. Er sollte auf dem Stack angelegt und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| auto [begin](../../system/smartptr/begin/)() const | Zugriffsfunktion für die [begin()](../../system/smartptr/begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](../../system/smartptr/begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels static_cast in den Basistyp um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Zugriffsfunktion für die [cbegin()](../../system/smartptr/cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](../../system/smartptr/cbegin/)-Methode ist. |
| auto [cend](../../system/smartptr/cend/)() const | Zugriffsfunktion für die [cend()](../../system/smartptr/cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](../../system/smartptr/cend/)-Methode ist. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Wandelt den Zeiger mithilfe von const_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Wandelt den Zeiger mithilfe von dynamic_cast auf das referenzierte Objekt in einen anderen Typ um. |
| auto [end](../../system/smartptr/end/)() | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| auto [end](../../system/smartptr/end/)() const | Zugriffsfunktion für die [end()](../../system/smartptr/end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](../../system/smartptr/end/)-Methode ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Gibt den Zeigermodus zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Gibt das referenzierte Objekt zurück, prüft jedoch, dass sich der Zeiger im geteilten Modus befindet. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Gibt die Anzahl der vorhandenen Shared-Pointer auf das referenzierte Objekt zurück, inklusive des aktuellen. Prüft, dass sich der aktuelle Zeiger im geteilten Modus befindet. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Ruft [GetHashCode()](../../system/smartptr/gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichbedeutend mit [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichbedeutend mit [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das referenzierte Objekt vom angegebenen Typ oder einem davon abgeleiteten Typ ist. Folgt den C#-'is'-Semantiken. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das Eigentumsobjekt zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Prüft, ob der Zeiger im geteilten Modus ist. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Prüft, ob der Zeiger im schwachen Modus ist. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Prüft, dass der Zeiger nicht null ist. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Stellt die Vergleichssemantik 'less' für die [SmartPtr](../../system/smartptr/)-Klasse bereit. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Stellt die Vergleichssemantik 'less' für die [SmartPtr](../../system/smartptr/)-Klasse bereit. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-zuweist das [SmartPtr](../../system/smartptr/)-Objekt. x wird danach unbrauchbar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Kopiert das [SmartPtr](../../system/smartptr/)-Objekt. Führt notwendige Typumwandlungen durch. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Weist einen rohen Zeiger dem [SmartPtr](../../system/smartptr/)-Objekt zu. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | Zugriffsfunktion. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei geteiltem Modus) das gleiche Objekt verwaltet oder (bei schwachem Modus) nachverfolgt. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](../../system/smartptr/reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt auf (falls vorhanden). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein null-Pointer [SmartPtr](../../system/smartptr/)-Objekt im gewünschten Modus. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Erstellt ein [SmartPtr](../../system/smartptr/)-Objekt, das auf das angegebene Objekt zeigt, oder wandelt einen rohen Zeiger in [SmartPtr](../../system/smartptr/) um. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen anschließend auf dasselbe Objekt. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Kopiert ein [SmartPtr](../../system/smartptr/)-Objekt. Beide Zeiger zeigen anschließend auf dasselbe Objekt. Führt, falls zulässig, eine Typumwandlung durch. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstruiert ein [SmartPtr](../../system/smartptr/)-Objekt. Tauscht im Wesentlichen zwei Zeiger, sofern sie im gleichen Modus sind. x kann nach dem Aufruf unbrauchbar sein. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn in C# ein Array-Typcast vorhanden ist, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Codekonstrukte zu übersetzen. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Konstruiert ein [SmartPtr](../../system/smartptr/), das die Besitzinformationen mit dem Anfangswert von ptr teilt, aber einen unabhängigen, nicht verwalteten Zeiger p hält. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Wandelt den Zeiger mittels static_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Konvertiert jeden Zeigertyp in einen Zeiger auf [Object](../../system/object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Kurzform, um das [System::TypeInfo](../../system/typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | Null-Zeiger-Konstruktor. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Zerstört das [SmartPtr](../../system/smartptr/)-Objekt. Falls nötig, verringert den Referenzzähler des referenzierten Objekts und löscht das Objekt. |

## Siehe auch

* Klasse [SmartPtr](../../system/smartptr/)
* Namensraum [System::Security::Cryptography::X509Certificates](../)
* Bibliothek [Aspose.Slides](../../)