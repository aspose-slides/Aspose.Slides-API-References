---
title: CollectionAssertHelper
second_title: Aspose.Slides für C++ API-Referenz
description: Hilfs-API für sammlungsbezogene Vorgänge.
type: docs
weight: 1548
url: /de/system/collectionasserthelper/
---
## CollectionAssertHelper Struktur


Hilfs-API für sammlungsbezogene Vorgänge.

```cpp
class CollectionAssertHelper
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Überprüft, dass alle Elemente der Sammlung dem Prädikat entsprechen. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Überprüft, dass irgendein Element der Sammlung dem Prädikat entspricht. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serialisiert zwei Sammlungen für die Nachrichtenrepräsentation. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Konvertiert die Sammlung in einen String, indem die Stringdarstellungen der Elemente zusammengefügt werden. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Berechnet das 'diff' zwischen zwei Sammlungen. Für jedes Element jeder Sammlung als Schlüssel ist der resultierende Wert positiv, wenn das Element häufiger in der \"expected\"-Sammlung vorkommt, negativ, wenn es häufiger in der \"actual\"-Sammlung vorkommt, und null, wenn das Element in beiden Sammlungen gleich oft vorkommt. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formatiert einen String, der als Nachrichtentext verwendet wird. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)