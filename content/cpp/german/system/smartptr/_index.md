---
title: SmartPtr
second_title: Aspose.Slides für C++ API Referenz
description: "Zeigerklasse zum Einhüllen von Typen, die auf dem Heap alloziert werden. Verwenden Sie sie, um den Speicher für Klassen zu verwalten, die Object erben. Dieser Zeigertyp folgt den Intrusive-Pointer-Semantiken. Der Referenzzähler wird entweder im Object selbst oder in einer Zählerstruktur gespeichert, die eng mit der Object-Instanz verbunden ist. In jedem Fall bilden alle SmartPtr-Instanzen eine einzige Besitzgruppe, unabhängig davon, wie sie erstellt wurden, was sich vom Verhalten der std::shared_ptr-Klasse unterscheidet. Das Konvertieren eines rohen Zeigers zu SmartPtr ist sicher, solange andere SmartPtr-Instanzen geteilte Referenzen auf dasselbe Objekt halten. Eine SmartPtr-Klasseninstanz kann sich in einem von zwei Zuständen befinden: Shared-Pointer und Weak-Pointer. Damit ein Objekt am Leben bleibt, muss die Anzahl der geteilten Referenzen darauf positiv sein. Sowohl Weak- als auch Shared-Pointer können verwendet werden, um auf das referenzierte Objekt zuzugreifen (Methoden aufzurufen, Felder zu lesen oder zu schreiben usw.), aber Weak-Pointer nehmen nicht am Referenzzählen der Shared-Pointer teil. Das Object wird gelöscht, wenn der letzte ‚shared‘ SmartPtr-Pointer darauf zerstört wird. Stellen Sie also sicher, dass dies nicht geschieht, wenn keine anderen Shared-SmartPtr-Pointer auf das Objekt existieren, z. B. während der Objekterstellung oder -zerstörung. Verwenden Sie System::Object::ThisProtector-Wächterobjekte (im C++-Code) oder das CppCTORSelfReference- bzw. CppSelfReference-Attribut (im zu übersetzenden C#-Code), um dieses Problem zu beheben. Ähnlich sollten Sie Schleifenreferenzen durch die Verwendung der System::WeakPtr-Zeigerklasse oder des System::SmartPtrMode::Weak-Zeigermodus (im C++-Code) bzw. des CppWeakPtr-Attributs (im zu übersetzenden C#-Code) auflösen. Wenn zwei oder mehr Objekte sich gegenseitig über ‚shared‘-Pointer referenzieren, werden sie nie gelöscht. Sollte der Zeigertyp (weak oder shared) zur Laufzeit umgeschaltet werden müssen, verwenden Sie die System::SmartPtr<T>::set_Mode()-Methode oder die System::DynamicWeakPtr-Klasse. Die SmartPtr-Klasse enthält keine virtuellen Methoden. Sie sollten sie nur erben, wenn Sie eine eigene Speicherverwaltungsstrategie erstellen. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack allokiert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden."
type: docs
weight: 1236
url: /de/system/smartptr/
---
## SmartPtr Klasse

Pointer-Klasse zum Einhüllen von Typen, die auf dem Heap zugewiesen werden. Verwenden Sie sie, um den Speicher für Klassen zu verwalten, die [Object](../object/) erben. Dieser Zeigertyp folgt den Intrusive-Pointer-Semantiken. Der Referenzzähler wird entweder in [Object](../object/) selbst oder in einer Zählerstruktur gespeichert, die eng mit der [Object](../object/)-Instanz verbunden ist. In jedem Fall bilden alle [SmartPtr](./)-Instanzen eine einzige Besitzgruppe, unabhängig davon, wie sie erstellt wurden, was sich vom Verhalten der std::shared_ptr-Klasse unterscheidet. Das Konvertieren eines rohen Zeigers zu [SmartPtr](./) ist sicher, solange andere [SmartPtr](./)-Instanzen geteilte Referenzen auf dasselbe Objekt halten. Eine [SmartPtr](./)-Klasseninstanz kann sich in einem von zwei Zuständen befinden: Shared-Pointer und Weak-Pointer. Damit ein Objekt am Leben bleibt, muss die Anzahl der geteilten Referenzen darauf positiv sein. Sowohl Weak- als auch Shared-Pointer können verwendet werden, um auf das referenzierte Objekt zuzugreifen (Methoden aufzurufen, Felder zu lesen oder zu schreiben usw.), aber Weak-Pointer nehmen nicht am Referenzzählen der Shared-Pointer teil. [Object](../object/) wird gelöscht, wenn der letzte ‚shared‘ [SmartPtr](./)-Pointer darauf zerstört wird. Stellen Sie also sicher, dass dies nicht geschieht, wenn keine anderen Shared-[SmartPtr](./)-Pointer auf das Objekt existieren, z. B. während der Objekterstellung oder -zerstörung. Verwenden Sie System::Object::ThisProtector-Wächterobjekte (im C++-Code) oder das CppCTORSelfReference- bzw. CppSelfReference-Attribut (im zu übersetzenden C#-Code), um dieses Problem zu beheben. Ähnlich sollten Sie Schleifenreferenzen mithilfe der [System::WeakPtr](../weakptr/)-Pointer-Klasse oder des [System::SmartPtrMode::Weak](../smartptrmode/)-Pointer-Modus (im C++-Code) bzw. des CppWeakPtr-Attributs (im zu übersetzenden C#-Code) auflösen. Wenn zwei oder mehr Objekte sich gegenseitig über ‚shared‘-Pointer referenzieren, werden sie niemals gelöscht. Wenn der Zeigertyp (weak oder shared) zur Laufzeit umgeschaltet werden soll, verwenden Sie die [System::SmartPtr<T>::set_Mode()](./set_mode/)-Methode oder die [System::DynamicWeakPtr](../dynamicweakptr/)-Klasse. Die [SmartPtr](./)-Klasse enthält keine virtuellen Methoden. Sie sollten sie nur erben, wenn Sie eine eigene Speicherverwaltungsstrategie entwickeln. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack allokiert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden.

```cpp
template<class T>class SmartPtr
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des referenzierten Objekts. Muss entweder [System::Object](../object/) sein oder davon abgeleitet. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| auto [begin](./begin/)() | Zugriffsmethode für die [begin()](./begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](./begin/)-Methode ist. |
| auto [begin](./begin/)() const | Zugriffsmethode für die [begin()](./begin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [begin()](./begin/)-Methode ist. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Wandelt den Zeiger in seinen eigenen Typ um. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Wandelt den Zeiger mittels static_cast in den Basistyp um. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Wandelt den Zeiger mittels dynamic_cast in den abgeleiteten Typ um. |
| auto [cbegin](./cbegin/)() const | Zugriffsmethode für die [cbegin()](./cbegin/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cbegin()](./cbegin/)-Methode ist. |
| auto [cend](./cend/)() const | Zugriffsmethode für die [cend()](./cend/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [cend()](./cend/)-Methode ist. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Wandelt den Zeiger mittels const_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Wandelt den Zeiger mittels dynamic_cast auf das referenzierte Objekt in einen anderen Typ um. |
| auto [end](./end/)() | Zugriffsmethode für die [end()](./end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](./end/)-Methode ist. |
| auto [end](./end/)() const | Zugriffsmethode für die [end()](./end/)-Methode einer zugrunde liegenden Sammlung. Kompiliert nur, wenn SmartPtr_ ein Spezialisierungstyp mit der [end()](./end/)-Methode ist. |
| [Pointee_](./pointee_/) * [get](./get/)() const | Gibt das referenzierte Objekt zurück. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Gibt den Zeigermodus zurück. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Gibt das referenzierte Objekt zurück, verlangt jedoch, dass der Zeiger im Shared-Modus ist. |
| int [get_shared_count](./get_shared_count/)() const | Ermittelt die Anzahl bestehender Shared-Pointer auf das referenzierte Objekt, inklusive des aktuellen. Verlangt, dass der aktuelle Zeiger im Shared-Modus ist. |
| int [GetHashCode](./gethashcode/)() const | Ruft [GetHashCode()](./gethashcode/) auf dem referenzierten Objekt auf. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Gibt das aktuell referenzierte Objekt zurück (falls vorhanden) oder wirft eine Ausnahme. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichbedeutend zu [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Gibt das referenzierte Objekt zurück. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Gibt das referenzierte Objekt zurück (falls vorhanden) oder nullptr. Gleichbedeutend zu [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Prüft, ob das referenzierte Objekt von einem bestimmten Typ oder einem davon abgeleiteten Typ ist. Folgt den C#-'is'-Semantiken. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Prüft, ob der Zeiger auf ein anderes Objekt als das Eigentum-Objekt zeigt (erstellt durch einen Alias-Konstruktor). |
| **bool** [IsShared](./isshared/)() const | Prüft, ob der Zeiger im Shared-Modus ist. |
| **bool** [IsWeak](./isweak/)() const | Prüft, ob der Zeiger im Weak-Modus ist. |
| explicit  [operator bool](./operator_bool/)() const | Prüft, ob der Zeiger nicht null ist. |
| **bool** [operator!](./operator_not/)() const | Prüft, ob der Zeiger null ist. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Gibt eine Referenz auf das referenzierte Objekt zurück. Verlangt, dass der Zeiger nicht null ist. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Ermöglicht den Zugriff auf Mitglieder des referenzierten Objekts. |
| **bool** [operator<](./operator_less/)(Y *) const | Stellt eine Vergleichs-<-Semantik für die [SmartPtr](./)-Klasse bereit. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Stellt eine Vergleichs-<-Semantik für die [SmartPtr](./)-Klasse bereit. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Verschiebt das [SmartPtr](./)-Objekt per Move-Assign. x wird unbenutzbar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Kopiert das [SmartPtr](./)-Objekt per Copy-Assign. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Kopiert das [SmartPtr](./)-Objekt per Copy-Assign. Führt erforderliche Typkonvertierungen durch. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Weist dem [SmartPtr](./)-Objekt einen rohen Zeiger zu. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Setzt den Zeigerwert auf nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Prüft, ob der Zeiger auf nullptr zeigt. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Entfernt das Alias (erstellt durch einen Alias-Konstruktor) vom Zeiger und stellt sicher, dass er (bei shared) verwaltet oder (bei weak) verfolgt, dasselbe Objekt wie vorher referenziert. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Setzt das referenzierte Objekt. |
| void [reset](./reset/)() | Setzt den Zeiger auf nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Setzt den Zeigermodus. Kann die Referenzzähler des referenzierten Objekts ändern. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Ruft die SetTemplateWeakPtr()-Methode auf dem referenzierten Objekt (falls vorhanden) auf. |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Erstellt ein [SmartPtr](./)-Objekt des gewünschten Modus. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Erstellt ein null-Pointer [SmartPtr](./)-Objekt des gewünschten Modus. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Erstellt ein [SmartPtr](./)-Objekt, das auf das angegebene Objekt zeigt, oder konvertiert einen rohen Zeiger zu [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](./)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Kopiert ein [SmartPtr](./)-Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt eine Typumwandlung durch, falls erlaubt. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Verschiebt ein [SmartPtr](./)-Objekt. Tauscht im Wesentlichen zwei Zeiger, sofern beide denselben Modus haben. x kann nach dem Aufruf unbenutzbar sein. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Konvertiert den Typ des referenzierten Arrays, indem ein neues Array des anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typ-Cast gibt, der in C++ nicht unterstützt wird. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Initialisiert ein leeres Array. Wird verwendet, um einige C#-Code-Konstrukte zu übersetzen. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Konstruiert ein [SmartPtr](./), das die Besitzinformationen des ursprünglichen ptr-Werts teilt, aber einen nicht verwandten und nicht verwalteten Zeiger p hält. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Wandelt den Zeiger mittels static_cast auf das referenzierte Objekt in einen anderen Typ um. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Konvertiert einen beliebigen Zeigertyp in einen Zeiger auf [Object](../object/). Erfordert nicht, dass der Pointee_-Typ vollständig ist. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Kurzschreiben, um das [System::TypeInfo](../typeinfo/)-Objekt für den Pointee_-Typ zu erhalten. |
|  [~SmartPtr](./~smartptr/)() | Zerstört das [SmartPtr](./)-Objekt. Falls nötig, wird der Referenzzähler des referenzierten Objekts verringert und das Objekt gelöscht. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [Pointee_](./pointee_/) | Referenzierter Typ. |
| [SmartPtr_](./smartptr_/) | Spezialisierter Smart-Pointer-Typ. |
| [ArrayType](./arraytype/) | Entspricht Pointee_, falls es eine Spezialisierung von [System::Array](../array/) ist, sonst void. |
| [ValueType](./valuetype/) | Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von [System::Array](../array/) ist. |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.Slides](../../)