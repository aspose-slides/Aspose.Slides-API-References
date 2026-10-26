---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 287
url: /de/system.boxedvaluedetail/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Comparable](./comparable/) | Einfache Implementierung von IComparable<> |
| [NonComparable](./noncomparable/) | Dummy-Basistyp für verpackte Typen, die IComparable<> nicht implementieren |
## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Template-Prädikat, das prüft, ob das verpackte Objekt das gegebene Interface selbst implementieren soll. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementiert [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Template-Prädikat, das prüft, ob das verpackte Objekt das [IComparable](../system/icomparable/) Interface selbst implementieren soll. |
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bestimmt die Gleichheit des angegebenen Wertes mithilfe von [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bestimmt die Gleichheit des angegebenen Wertes mithilfe der Methode [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Vergleicht zwei Gleitkommawerte einfacher Genauigkeit. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Vergleicht zwei Gleitkommawerte doppelter Genauigkeit. |