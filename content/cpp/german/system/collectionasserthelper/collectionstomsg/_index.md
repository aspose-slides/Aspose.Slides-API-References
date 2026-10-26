---
title: CollectionsToMsg()
second_title: Aspose.Slides für C++ API-Referenz
description: Serialisiert zwei Sammlungen für die Nachrichtenrepräsentation.
type: docs
weight: 53
url: /de/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) Methode

Serialisiert zwei Sammlungen für die Nachrichtenrepräsentation.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | Erwarteter Typ des Sammlungselements. |
| T2 | Tatsächlicher Typ des Sammlungselements. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Eine benutzerdefinierte Zeichenfolge, die vor dem erwarteten Wert in der resultierenden Meldung eingefügt wird |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Erwartete Sammlung. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Tatsächliche Sammlung. |

### Rückgabewert

Benutzerfreundliche Meldung zum Inhalt der Sammlungen.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [CollectionAssertHelper](../)
* Namespace [System](../../)
* Bibliothek [Aspose.Slides](../../../)