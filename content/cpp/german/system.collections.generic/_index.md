---
title: "System::Collections::Generic"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 326
url: /de/system.collections.generic/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [_KeyCollection](./_keycollection/) | Sammlung von [Dictionary](./dictionary/)-Schlüsseln. Referenzsammlung, kopiert nichts. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [_KeyList](./_keylist/) | Implementiert Liste von Dictionary-Schlüsseln. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [_ValueCollection](./_valuecollection/) | Sammlung von [Dictionary](./dictionary/)-Werten. Referenzsammlung, kopiert nichts. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [_ValueList](./_valuelist/) | Implementiert Liste von Dictionary-Werten. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BaseDictionary](./basedictionary/) | Implementiert gemeinsamen Code für verschiedene dictionary-ähnliche Datenstrukturen (z. B. [Dictionary](./dictionary/), [SortedDictionary](./sorteddictionary/)). Sollte nicht direkt verwendet werden, außer bei Vererbung beim Definieren von Containern. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BaseEnumerator](./baseenumerator/) | Enumerator-Definition, um STL-ähnliche Typen für C#-artige Nutzung zu umschließen. Macht keine Assertions zur Containerstruktur, außer der Existenz eines sequentiellen Iterators. Verwendet begin() und end() Funktionen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BaseKVCollection](./basekvcollection/) | Enthält gemeinsamen Code für Sammlungen von Schlüsseln oder Werten. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BaseSet](./baseset/) |  |
| [Comparer](./comparer/) | Bietet eine Basisklasse für Implementierungen des generischen Interfaces [System.Collections.Generic.IComparer](./icomparer/). |
| [DefaultComparer](./defaultcomparer/) | Standardvergleichsklasse. Verwendet operator < und operator ==, um Werte zu vergleichen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [Details_KeyNotFoundException](./details_keynotfoundexception/) |  |
| [Dictionary](./dictionary/) | Vorwärtsdeklaration der Klasse [Dictionary](./dictionary/). |
| [DictionaryIterator](./dictionaryiterator/) | [Dictionary](./dictionary/)-Iterator, der [KeyValuePair](./keyvaluepair/)-Notation liefert. |
| [DictionaryPtr](./dictionaryptr/) | [Dictionary](./dictionary/)-Pointerklasse mit Operatorüberladungen. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [EnumerableExt](./enumerableext/) |  |
| [EnumeratorWrapperIterator](./enumeratorwrapperiterator/) | Iterator, der den vorab erstellten Enumerator umschließt und alle Aufrufe an ihn weiterleitet. |
| [HashDictionary](./hashdictionary/) | Stub für die Klasse [HashDictionary](./hashdictionary/) (derzeit nicht implementiert). Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [HashSet](./hashset/) | Vorwärtsdeklaration der Klasse [HashSet](./hashset/). |
| [HashSetPtr](./hashsetptr/) | Zeiger zur Aufbewahrung von [HashSet](./hashset/)-Referenzen. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [ICollection](./icollection/) | Interface einer Sammlung von Elementen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IComparer](./icomparer/) | Interface, das zwei Objekte im größer-gleich-kleiner Sinne vergleicht. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IDictionary](./idictionary/) | Interface für dictionary-ähnliche Container. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IEnumerable](./ienumerable/) | Interface eines Objekts, das einen Enumerator für die enthaltenen Elemente bereitstellt. |
| [IEnumerator](./ienumerator/) | Interface eines Enumerators, der zum Durchlaufen einiger Elemente verwendet werden kann. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IEqualityComparer](./iequalitycomparer/) | Interface, das Mittel zum Vergleich zweier Objekte auf Gleichheit bietet. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IKVCollection](./ikvcollection/) | Interface eines Containers, der Schlüssel oder Werte des dictionary-ähnlichen Containers enthält. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IList](./ilist/) | Interface eines indizierten Containers von Elementen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [ISet](./iset/) | Interface einer Sammlung, die eine Menge eindeutiger Elemente enthält. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [KeyIterator](./keyiterator/) | [Dictionary](./dictionary/)-Iterator, der Schlüsselzugriff bietet. |
| [KeyValuePair](./keyvaluepair/) | Paar aus Schlüssel und Wert. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../system/smartptr/), um Objekte dieses Typs zu verwalten. |
| [KVPairIterator](./kvpairiterator/) | Adaptierender Iterator, der std::pair in das von [Dictionary](./dictionary/) erwartete KVPair umschließt. |
| [LinkedList](./linkedlist/) | Vorwärtsdeklaration von [LinkedList](./linkedlist/). |
| [LinkedListNode](./linkedlistnode/) | Knoten einer verketteten Liste. Implementiert einen Wrapper über einen Iterator von std::list, der in einer verketteten Liste eingeschlossen ist. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [List](./list/) | Vorwärtsdeklaration von [List](./list/). |
| [ListExt](./listext/) | generische [List](./list/)-Klasse, die das Interface [IListWrapper](../system.collections/ilistwrapper/) implementiert |
| [ListPtr](./listptr/) | [List](./list/)-Pointer mit Zugriffsoperatoren. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [Queue](./queue/) | Vorwärtsdeklaration der Klasse [Queue](./queue/). |
| [QueuePtr](./queueptr/) | [Queue](./queue/)-Pointer. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [ReverseEnumerator](./reverseenumerator/) | Enumerator, der den Container rückwärts iteriert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SimpleEnumerator](./simpleenumerator/) | Iteratorklasse für einfache Container, die Elemente direkt mittels rbegin() und rend() Funktionen halten. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SortedDictionary](./sorteddictionary/) | Vorwärtsdeklaration des Typs Sorted Dictionary. |
| [SortedDictionaryPtr](./sorteddictionaryptr/) | Sorted Dictionary-Pointer mit Zugriffsoperatoren. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [SortedList](./sortedlist/) | Sortierte Liste, die die FlatMap-Struktur umschließt. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../system/makeobject/) alloziert werden. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Pointer und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [SortedListHelper](./sortedlisthelper/) | Diese Hilfsklasse wird verwendet, um die virtuellen Funktionen get_Keys und get_Values, die vom Interface [IDictionary](./idictionary/) kommen, zu maskieren und durch Funktionen mit anderem Rückgabetyp zu ersetzen. |
| [SortedSet](./sortedset/) | Vorwärtsdeklaration der Klasse [SortedSet](./sortedset/). |
| [SortedSetPtr](./sortedsetptr/) | Zeiger zur Aufbewahrung von [SortedSet](./sortedset/)-Referenzen. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [Stack](./stack/) | Vorwärtsdeklaration der Klasse [Stack](./stack/). |
| [StackPtr](./stackptr/) | [Stack](./stack/)-Pointer. Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder als const-Referenz übergeben werden. |
| [ValueIterator](./valueiterator/) | [Dictionary](./dictionary/)-Iterator, der Wertzugriff bietet. |

## Strukturen

| Struktur | Beschreibung |
| --- | --- |
| [ComparerAdapter](./compareradapter/) | Adapter zur Verwendung von [IComparer](./icomparer/) in einer STL-Umgebung. Verwendet [IComparer](./icomparer/), falls gesetzt; andernfalls verwendet er operator < (falls verfügbar) oder gibt false zurück (falls nicht). |
| [DictionaryHashSelector](./dictionaryhashselector/) | Hash-Funktionsauswahl für die Klasse [Dictionary](./dictionary/). Diese Implementierung verwendet STL-Hashing, sofern keine Alternative bereitgestellt wird. |
| [EqualityComparerAdapter](./equalitycompareradapter/) | Adapter, der die Verwendung von [IEqualityComparer](./iequalitycomparer/) mit STL-artigen Sammlungen und Algorithmen ermöglicht. Verwendet [IEqualityComparer](./iequalitycomparer/), falls gesetzt. Wenn nicht gesetzt, verwendet er operator ==, [Object::Equals](../system/object/equals/) oder T::Equals, je nachdem, was verfügbar ist. |
| [EqualityComparerHashAdapter](./equalitycomparerhashadapter/) | Adapter zur Verwendung von [IEqualityComparer](./iequalitycomparer/) zum Hashing. Verwendet ein Comparator-Objekt, falls gesetzt; andernfalls wird die verfügbare Hash-Methode verwendet, die über die Struktur [DictionaryHashSelector](./dictionaryhashselector/) ausgewählt wird. |

## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Vergleicht zwei Schlüssel-Wert-Paare nach 'equals'-Semantik. Verwendet operator == oder die EqualsTo-Methode für sowohl Schlüssel als auch Werte, je nachdem, was definiert ist. |
| **bool** [operator!=](./operator_not_equal/)(const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Vergleicht zwei Schlüssel-Wert-Paare nach inverser 'equals'-Semantik. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Fügt Daten in den Stream ein unter Verwendung von UTF-8-Kodierung. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [KeyValuePair](./keyvaluepair/)\<TKey, TValue\>\&) | Fügt Daten in den Stream ein. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [KeyNotFoundException](./keynotfoundexception/) |  |