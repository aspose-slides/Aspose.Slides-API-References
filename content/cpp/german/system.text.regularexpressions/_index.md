---
title: "System::Text::RegularExpressions"
second_title: "Aspose.Slides für C++ API-Referenz"
description: 
type: docs
weight: 989
url: /de/system.text.regularexpressions/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Capture](./capture/) | Ergebnis einer Einzelunterausdrucks-Übereinstimmung. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [CaptureCollection](./capturecollection/) | Liste von Captures, die von einer einzelnen Erfassungsgruppe durchgeführt wurden. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [Group](./group/) | Ergebnis einer Erfassung, die von einer einzelnen Erfassungsgruppe durchgeführt wurde. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [GroupCollection](./groupcollection/) | Liste von Erfassungsgruppen in einem einzelnen Treffer. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) Sammlungszeiger. Dieser Typ ist ein Zeiger, um die Löschung anderer Objekte zu verwalten. Er sollte auf dem Stack alloziert und an Funktionen entweder per Wert oder per const-Referenz übergeben werden. |
| [Match](./match/) | [Single](../system/single/) Treffer eines regulären Ausdrucks im String. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [MatchCollection](./matchcollection/) | Sammlung von Treffern, die durch wiederholtes Anwenden eines regulären Ausdrucks auf einen String entsteht. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
| [Regex](./regex/) | Regulärer Ausdruck mit C#-ähnlicher Syntax. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../system/makeobject/) allokiert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um sie als Argument an Funktionen zu übergeben. |
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Wrapper, um die Klasse MatchHolder ohne deren Einbindung sowie PCRE2 zu halten. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) Optionen. |
## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [UStringPtr](./ustringptr/) | Geteilter UnicodeString, um Kopieren zu vermeiden. |
| [CapturePtr](./captureptr/) | Zeiger auf ein einzelnes Capture-Objekt. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Zeiger auf eine Capture-Sammlung. |
| [GroupPtr](./groupptr/) | Zeiger auf eine Gruppe. |
| [RegexPtr](./regexptr/) | [Regex](./regex/)-Zeiger. |
| [MatchPtr](./matchptr/) | [Match](./match/)-Zeiger. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/)-Sammlungszeiger. |
| [MatchEvaluator](./matchevaluator/) | Delegattyp, um ein Match auszuwerten. |